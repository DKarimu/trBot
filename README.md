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
  '... .. .
```