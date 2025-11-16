# 🎯 GrepoHelper Features Documentation

Complete documentation of all 22+ automation features available in GrepoHelper.

---

## 🏗️ Buildings & Infrastructure

### Auto-Build
**Category:** Buildings & Infrastructure  
**Priority:** High

Automatically constructs buildings in your cities based on your predefined build queues. Set your desired building sequence and let the bot handle the construction timing, resource management, and queue optimization.

**Key Features:**
- Smart resource validation before actions
- Queue optimization and duplicate prevention
- Randomized timing for natural gameplay patterns
- Population and capacity management

**Configuration:**
- Custom build queues per city
- Resource thresholds
- Priority system
- Skip options for specific buildings

---

### Auto City Builder
**Category:** Buildings & Infrastructure  
**Priority:** High

Select a perfect city state template and apply it to 100+ cities in one click instantly. Manages building construction and research queues across your entire empire.

**Key Features:**
- Template-based city development
- Bulk city management
- Instant application to multiple cities
- Configurable templates

**Use Cases:**
- Starting new cities
- Standardizing city layouts
- Quick empire expansion

---

### Auto-Research
**Category:** Buildings & Infrastructure  
**Priority:** High

Automatically conducts Academy research according to your predefined research queue. The bot checks for available research points and initiates new research when resources are sufficient.

**Key Features:**
- Automatically research in cities all technologies that you added in bot queue
- Research point validation
- Priority-based research queue
- Resource management

**Configuration:**
- Research priorities
- Resource thresholds
- Skip options

---

### Auto-Recruit
**Category:** Buildings & Infrastructure  
**Priority:** High

Automatically trains units in your barracks/harbor without manual intervention. Add queue for your preferred unit types and quantities.

**Key Features:**
- Optimized unit production schedules
- Population limit respect
- Resource availability checks
- Multi-unit type support

---

### Auto-Culture
**Category:** Buildings & Infrastructure  
**Priority:** Medium

Automatically increase cultural level by participating in cultural activities. The bot monitors culture-related events, ensuring you never miss valuable culture points.

**Key Features:**
- Automatic culture point collection
- Event monitoring
- City slot maximization

---

## ⚔️ Combat & Military

### Attack Planner
**Category:** Combat & Military  
**Priority:** High

Advanced coordination system for planning and executing complex attack strategies. Schedule coordinated strikes, manage multiple attack waves, and synchronize timing across different cities.

**Key Features:**
- Multi-city coordination
- Attack scheduling
- Wave management
- Timing synchronization

**Use Cases:**
- Coordinated city attacks
- Alliance warfare
- Strategic conquests

---

### Auto CS Destroyer
**Category:** Combat & Military  
**Priority:** High

Bot automatically detect if there is a colonisation ship in the attack. If feature is enabled, it automatically plan attacks from your other cities to snipe it.

**Key Features:**
- CS detection system
- Multi-city response
- Naval, mythic, and land unit support
- Attack Planner integration

**Configuration:**
- Response cities
- Unit types
- Detection sensitivity

---

### Bandit Camp
**Category:** Combat & Military  
**Priority:** Medium

Automatically attacks bandit camps. Configure minimum unit requirements and attack intervals to maintain a good rhythm while protecting your valuable troops.

**Key Features:**
- Automatically attack bandit camps when available, and store rewards in the inventory
- Unit requirement checks
- Attack interval management
- Risk assessment

---

### Auto Dodge
**Category:** Combat & Military  
**Priority:** High

Intelligent defensive system that automatically moves your units to safety when incoming attacks are detected.

**Key Features:**
- Attack detection
- Smart dodging strategies
- Unit protection
- Multi-city support

---

### Auto Units Creator
**Category:** Combat & Military  
**Priority:** High

Sophisticated unit management system with advanced creation algorithms. Optimizes unit production across multiple cities.

**Key Features:**
- Advanced creation algorithms
- Multi-city optimization
- Unit type balancing
- Strategic development

---

### Auto Favor Farm
**Category:** Combat & Military  
**Priority:** Medium

Automatically farm favor from enemy cities using Harpy (Hera) and Manticore (Zeus).

**Key Features:**
- Island and Manual targeting modes
- Intelligent blacklist system
- Attack Planner integration
- Favor optimization

---

### Auto Farm BP
**Category:** Combat & Military  
**Priority:** Medium

Automatically farm battle points (BP) from enemy cities using configured units.

**Key Features:**
- Round-robin rotation
- Island and Manual targeting modes
- Per-city unit configuration
- Intelligent blacklist system

---

## 💰 Resource Management

### Auto Farm
**Category:** Resource Management  
**Priority:** High

Automatically collects resources from villages to maintain steady resource income. Uses random delays, random village skips, and varied timing patterns to simulate human-like behavior.

**Key Features:**
- Smart village resource collection
- Human-like patterns
- Random delays and skips
- Natural gameplay simulation

**Configuration:**
- Farm intervals
- Randomization settings
- Village selection

---

### Auto Village Upgrade
**Category:** Resource Management  
**Priority:** Medium

Automatically handles village development. The bot unlocks new villages when battle points are available and upgrades existing villages to higher levels.

**Key Features:**
- Automatic village unlocking
- Upgrade management
- BP monitoring
- Economic base expansion

---

### Auto Trade
**Category:** Resource Management  
**Priority:** High

Intelligent resource trading system that balances resources across your cities. Automatically initiates trades when resource imbalances are detected.

**Key Features:**
- Inter-city resource balancing
- Imbalance detection
- Optimal distribution
- Trade automation

---

### Auto Village Trading
**Category:** Resource Management  
**Priority:** Medium

Specialized trading module focused on village trades. Manages resource exchanges with villages, executes profitable trades based on configurable ratios and timing.

**Key Features:**
- Village trade optimization
- Configurable ratios
- Timing optimization
- Economic efficiency

---

### Auto Silver Cave
**Category:** Resource Management  
**Priority:** Medium

Automatically store excess silver in cave. The bot monitors your resource levels and stores surplus depending on your setting to increase your spy capacities.

**Key Features:**
- Automatic silver storage
- Resource monitoring
- Spy capacity optimization

---

### Auto Complete Orders
**Category:** Resource Management  
**Priority:** Low

Automatically completes buildings below the 5 minutes remaining duration for free. The bot monitors for buildings below 5 minutes and completes them for free.

**Key Features:**
- Free instant builds
- 5-minute threshold
- Configurable skip chance

---

## 🛠️ System & Utilities

### Human Activity Detection
**Category:** System & Utilities  
**Priority:** Critical

Smart anti-detection system that automatically pauses all bot operations when you're actively playing. Detects mouse movement, keyboard input, clicks, and scrolling.

**Key Features:**
- Automatic pause on human activity
- Multi-input detection (mouse, keyboard, scroll)
- Seamless resume after inactivity
- Natural gameplay patterns

**Configuration:**
- Inactivity timeout (default: 10 seconds)
- Detection sensitivity

---

### Night Pause
**Category:** System & Utilities  
**Priority:** High

Intelligent scheduling system that pauses all bot activities during your specified sleep hours. Configure your preferred downtime window.

**Key Features:**
- Configurable sleep hours
- Automatic pause/resume
- Natural gameplay patterns
- Timezone support

---

### Queue Monitor
**Category:** System & Utilities  
**Priority:** Medium

Real-time dashboard displaying all active bot operations and pending actions. Monitor automated tasks from a centralized interface.

**Key Features:**
- Real-time operation display
- Centralized monitoring
- Conflict prevention
- Operational visibility

---

### Discord/Telegram Notifications
**Category:** System & Utilities  
**Priority:** High

Real-time alerts delivered directly to your Discord or Telegram account. Get instant notifications for critical events.

**Key Features:**
- Real-time alerts
- Discord/Telegram integration
- Customizable notifications
- Per-account preferences

**Notification Types:**
- Incoming attacks (with CS detection)
- Captcha detection
- Critical bot events
- Custom alerts

---

## 📊 Feature Comparison

| Feature | Category | Priority | Multi-City | Requires Config |
|---------|----------|----------|------------|-----------------|
| Auto-Build | Buildings | High | ✅ | ✅ |
| Auto City Builder | Buildings | High | ✅ | ✅ |
| Auto-Research | Buildings | High | ✅ | ✅ |
| Auto-Recruit | Buildings | High | ✅ | ✅ |
| Auto-Culture | Buildings | Medium | ✅ | ✅ |
| Attack Planner | Combat | High | ✅ | ✅ |
| Auto CS Destroyer | Combat | High | ✅ | ✅ |
| Bandit Camp | Combat | Medium | ✅ | ✅ |
| Auto Dodge | Combat | High | ✅ | ✅ |
| Auto Units Creator | Combat | High | ✅ | ✅ |
| Auto Favor Farm | Combat | Medium | ✅ | ✅ |
| Auto Farm BP | Combat | Medium | ✅ | ✅ |
| Auto Farm | Resources | High | ✅ | ✅ |
| Auto Village Upgrade | Resources | Medium | ✅ | ✅ |
| Auto Trade | Resources | High | ✅ | ✅ |
| Auto Village Trading | Resources | Medium | ✅ | ✅ |
| Auto Silver Cave | Resources | Medium | ✅ | ✅ |
| Auto Complete Orders | Resources | Low | ✅ | ✅ |
| Human Activity Detection | System | Critical | ✅ | ✅ |
| Night Pause | System | High | ✅ | ✅ |
| Queue Monitor | System | Medium | ✅ | ❌ |
| Notifications | System | High | ✅ | ✅ |

---

## 🎯 Feature Recommendations by Playstyle

### 🏙️ City Builder Focus
- Auto-Build
- Auto City Builder
- Auto-Research
- Auto-Recruit
- Auto-Culture

### ⚔️ Military Focus
- Attack Planner
- Auto CS Destroyer
- Auto Dodge
- Auto Units Creator
- Auto Farm BP

### 💰 Economy Focus
- Auto Farm
- Auto Trade
- Auto Village Trading
- Auto Village Upgrade
- Auto Silver Cave

### 🛡️ Safety Focus
- Human Activity Detection
- Night Pause
- Queue Monitor
- Discord/Telegram Notifications

---

## 📝 Notes

- All features support multi-city management
- Features can be enabled/disabled per city
- Most features require initial configuration
- Human Activity Detection is recommended for all users
- Notification system works with Discord and Telegram

---

*Last updated: 2025*

