# *trBot
trBot (trading Bot) is simple trading bot for eny trading market using java...!

#### -- - Modules
- trbot-application
- trbot-configuration 
- trbot-data 
- trbot-enumeration 
- trbot-exceptionhandl 
- trbot-formation 
- trbot-applinterface 
- trbot-Manage 
- trbot-mode 
- trbot-trade
#### -- - trBot Structure
```yaml
  trbot
  ├── trbot-application
  │	└──	src
  │   	├── main
  │   	│   ├── java
  │   	│   │   └── com
  │   	│   │       └── trbot
  │   	│   │           └── application
  │   	│   │               ├── TrBot.java
  │   	│   │               └── config
  │   	│   │                   ├── LogerManager.java
  │   	│   │                   ├── BrockerManager.java
  │   	│   │                   └── Manager.java
  │   	│   └── resources
  │   	│       └── banner.txt
  │   	└── test
  │   	    ├── java
  │   	    │   └── com
  │   	    │       └── trbot
  │   	    │           └── application
  │   	    │               ├── TestTrBot.java
  │   	    │               └── config
  │   	    │                   ├── TestLogerManager.java
  │   	    │                   ├── TestBrockerManager.java
  │   	    │                   └── TestManager.java
  │   	    └── resources
  │   	        └── log4j2-test.xml
  ├── trbot-mode
  │	└──	src
  │   	├── main
  │   	│   ├── java
  │   	│   │   └── com
  │   	│   │       └── trbot
  │   	│   │           └── modes
  │   	│   │               ├── LiveMode.java
  │   	│   │               ├── SimulationMode.java
  │   	│   │               ├── BacktestingMode.java
  │   	│   │               └── ClusterMode.java
  │   	│   └── resources
  │   	│       └── ModeResources.resour
  │   	└── test
  │   	    ├── java
  │   	    │   └── com
  │   	    │       └── trbot
  │   	    │           └── modes
  │   	    │               ├── TestLiveMode.java
  │   	    │               ├── TestSimulationMode.java
  │   	    │               ├── TestBacktestingMode.java
  │   	    │               └── TestClusterMode.java
  │   	    └── resources
  │   	        └── ModeResources.resour
  ├── trbot-configuration
  │	└──	src
  │   	├── main
  │   	│   ├── java
  │   	│   │   └── com
  │   	│   │       └── trbot
  │   	│   │           └── configurations
  │   	│   │               ├── ModeConfigure.java
  │   	│   │               ├── DatabaseConfigure.java
  │   	│   │               ├── TradingConfigure.java
  │   	│   │               ├── ApplicationConfigure.java
  │   	│   │               ├── NotifactionConfigure.java
  │   	│   │               └── StrategieConfigure.java
  │   	│   └── resources
  │   	│       └── ConfigureResources.resour
  │   	└── test
  │   	    ├── java
  │   	    │   └── com
  │   	    │       └── trbot
  │   	    │           └── configurations
  │   	    │               ├── TestModeConfigure.java
  │   	    │               ├── TestDatabaseConfigure.java
  │   	    │               ├── TestTradingConfigure.java
  │   	    │               ├── TestApplicationConfigure.java
  │   	    │               ├── TestNotifactionConfigure.java
  │   	    │               └── TestStrategieConfigure.java
  │   	    └── resources
  │   	        └── ConfigureResources.resour
  ├── trbot-formation
  │	└──	src
  │   	├── main
  │   	│   ├── java
  │   	│   │   └── com
  │   	│   │       └── trbot
  │   	│   │           └── formations
  │   	│   │               ├── DataFormatter.java
  │   	│   │               ├── DateTimeFormatter.java
  │   	│   │               ├── LogFormatter.java
  │   	│   │               ├── NotifactionFormatter.java
  │   	│   │               └── initialisation
  │   	│   │                   └── DateTimeInitializer.java
  │   	│   └── resources
  │   	│       └── InitialisatioResources.resour
  │   	└── test
  │   	    ├── java
  │   	    │   └── com
  │   	    │       └── trbot
  │   	    │           └── formations
  │   	    │               ├── TestDataFormatter.java
  │   	    │               ├── TestDateTimeFormatter.java
  │   	    │               ├── TestLogFormatter.java
  │   	    │               ├── NotifactionFormatter.java
  │   	    │               └── initialisation
  │   	    │                   └── TestDateTimeInitialisation.java
  │   	    └── resources
  │   	        └── InitialisatioResources.resour
  ├── trbot-Manage
  │	└──	src
  │   	├── main
  │   	│   ├── java
  │   	│   │   └── com
  │   	│   │       └── trbot
  │   	│   │           └── Managers
  │   	│   │               ├── DateTimeManager.java
  │   	│   │               ├── DataBaseManager.java
  │   	│   │               ├── DataManager.java
  │   	│   │               ├── NotificationManager.java
  │   	│   │               └── BotsManager.java
  │   	│   └── resources
  │   	│       └── StrategerResources.resour
  │   	└── test
  │   	    ├── java
  │   	    │   └── com
  │   	    │       └── trbot
  │   	    │           └── Managers
  │   	    │               ├── TestDateTimeManager.java
  │   	    │               ├── TestDataBaseManager.java
  │   	    │               ├── TestDataManager.java
  │   	    │               ├── TestNotificationManager.java
  │   	    │               └── TestBotsManager.java
  │   	    └── resources
  │   	        └── StrategerResources.resour
  ├── trbot-trade
  │	└──	src
  │   	├── main
  │   	│   ├── java
  │   	│   │   └── com
  │   	│   │       └── trbot
  │   	│   │           └── trades
  │   	│   │               ├── strategy
  │   	│   │               │   ├── StrategyToUseSg01.java
  │   	│   │               │   ├── StrategyToUseSg02.java
  │   	│   │               │   └── StrategyToUseSg031.java
  │   	│   │               ├── brokers
  │   	│   │               │   ├── BrokerToCallBk01.java
  │   	│   │               │   ├── BrokerToCallBk02.java
  │   	│   │               │   └── BrokerToCallBk03.java
  │   	│   │               ├── indexes
  │   	│   │               │   ├── IndexRSI.java
  │   	│   │               │   ├── IndexAMI.java
  │   	│   │               │   └── IndexUtil.java
  │   	│   │               └── TradeManager.java
  │   	│   └── resources
  │   	│       └── StrategerResources.resour
  │   	└── test
  │   	    ├── java
  │   	    │   └── com
  │   	    │       └── trbot
  │   	    │           └── trades
  │   	    │               ├── strategy
  │   	    │               │   ├── TestStrategyToUseSg01.java
  │   	    │               │   ├── TestStrategyToUseSg02.java
  │   	    │               │   └── TestStrategyToUseSg031.java
  │   	    │               ├── brokers
  │   	    │               │   ├── TestBrokerToCallBk01.java
  │   	    │               │   ├── TestBrokerToCallBk02.java
  │   	    │               │   └── TestBrokerToCallBk03.java
  │   	    │               ├── indexes
  │   	    │               │   ├── TestIndexRSI.java
  │   	    │               │   ├── TestIndexAMI.java
  │   	    │               │   └── TestIndexUtil.java
  │   	    │               └── TestTradeManager.java
  │   	    └── resources
  │   	        └── TestStrategerResources.resour
  ├── trbot-enumeration
  │	└──	src
  │   	├── main
  │   	│   ├── java
  │   	│   │   └── com
  │   	│   │       └── trbot
  │   	│   │           └── enumerations
  │   	│   │               └── Enumerator.java
  │   	│   └── resources
  │   	│       └── EnumeratorResources.resour
  │   	└── test
  │   	    ├── java
  │   	    │   └── com
  │   	    │       └── trbot
  │   	    │           └── enumerations
  │   	    │               └── TestEnumerator.java
  │   	    └── resources
  │   	        └── EnumeratorResources.resour
  ├── trbot-interface
  │	└──	src
  │   	├── main
  │   	│   ├── java
  │   	│   │   └── com
  │   	│   │       └── trbot
  │   	│   │           └── applinterface
  │   	│   │               └── Interface.java
  │   	│   └── resources
  │   	│       └── InterfaceResources.resour
  │   	└── test
  │   	    ├── java
  │   	    │   └── com
  │   	    │       └── trbot
  │   	    │           └── applinterface
  │   	    │               └── TestInterface.java
  │   	    └── resources
  │   	        └── InterfaceResources.resour
  ├── trbot-data
  │	└──	src
  │   	├── main
  │   	│   ├── java
  │   	│   │   └── com
  │   	│   │       └── trbot
  │   	│   │           └── data
  │   	│   │               ├── DataReader.java
  │   	│   │               ├── DataWriter.java
  │   	│   │               └── setting
  │   	│   │                   ├── DataReaderSetting.java
  │   	│   │                   ├── DataWriterSetting.java
  │   	│   │                   └── DataBaseSetting.java
  │   	│   │
  │   	│   └── resources
  │   	│       └── DbResources.resour
  │   	└── test
  │   	    ├── java
  │   	    │   └── com
  │   	    │       └── trbot
  │   	    │           └── data
  │   	    │               ├── TestDataReader.java
  │   	    │               ├── TestDataWriter.java
  │   	    │               └── setting
  │   	    │                   ├── TestDataReaderSetting.java
  │   	    │                   ├── TestDataWriterSetting.java
  │   	    │                   └── TestDataBaseSetting.java
  │   	    └── resources
  │   	        └── DbResources.resour
  ├── trbot-exceptionhandl
  │	└── src
  │   	├── main
  │   	│   ├── java
  │   	│   │   └── com
  │   	│   │       └── trbot
  │   	│   │           └── exceptionhandl
  │   	│   │               ├── exceptionHandler.java
  │   	│   │               └── exceptionResolver.java
  │   	│   └── resources
  │   	│       └── DbResources.resour
  │   	└── test
  │   	    ├── java
  │   	    │   └── com
  │   	    │       └── trbot
  │   	    │           └── exceptionhandl
  │   	    │               ├── TestExceptionHandler.java
  │   	    │               ├── TestExceptionHandler.java
  │   	    │               └── TestExceptionHandler.java
  │   	    │                   ├── TestDataReaderSetting.java
  │   	    │                   └── TestDataBaseSetting.java
  │   	    └── resources
  │   	        └── DbResources.resour
  '... .. .
```