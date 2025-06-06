---
id: index
title: Command Index
sidebar_label: Command Index
---

# 🤖 AimBob Discord Bot - Complete Command & Feature Index

## 📋 **Quick Reference Index**

---

## 🎯 **Slash Commands**

### 🎮 **Social & Gaming**
| Command | Access Level | Description |
|---------|-------------|-------------|
| `/gamefriends` | Authorized Users + God Users | Personal in-game friends notification system |
| `/diss` | Everyone | Throw some smack talk at another player |
| `/kbfact` | Everyone | Get random facts about the legendary KillerBob |
| `/flip` | Everyone | Flip a coin |
| `/mystats` | Registered Users | Show your in-game stats (must be registered) |
| `/register` | Everyone | Register your in-game account with Discord |

### 📊 **Statistics & Information**
| Command | Access Level | Description |
|---------|-------------|-------------|
| `/playercount` | Everyone (publish: In-Game Admin+) | Show player count statistics over time |
| `/stats` | Main Moderators + God Users | Internal administrative tool - server statistics |
| `/funstats` | Main Moderators + God Users | See fun bot usage statistics |
| `/lookup` | Moderators + God Users | Look up a player's stats from web dashboard |
| `/heatmap` | Unknown Access | Server activity heatmap |

### 🛡️ **Moderation & Admin**
| Command | Access Level | Description |
|---------|-------------|-------------|
| `/customlist` | Moderator Admin + God Users | Global watched players management |
| `/tox` | Moderators + In-Game Admin + God Users | Toxic player database management |
| `/badnamegame` | Unknown Access | Bad username detection game/management |

### 📚 **Information & Help**
| Command | Access Level | Description |
|---------|-------------|-------------|
| `/help` | Everyone | Shows command help and documentation |
| `/about` | Everyone (publish: Main Moderators+) | Information about AimBob Discord Bot |

---

## 🔄 **Automated Features**

### ⏱️ **Every 1 Minute**
| Feature | Function | Output |
|---------|----------|---------|
| **Bad Username Detection** | Scans all online players for offensive usernames | Admin notifications with action buttons |
| **Friends Online Monitoring** | Checks user friends' online status changes | Private DM notifications to users |
| **Custom List Monitoring** | Monitors watched players and toxic database | Admin channel notifications (2hr cooldown) |

### ⏱️ **Every 15 Minutes**
| Feature | Function | Output |
|---------|----------|---------|
| **All-Time High Monitoring** | Tracks server player count records | Public announcements for new records |
| **Milestone Tracking** | Monitors player achievement milestones | Celebration messages for achievements |

### ⏱️ **Every 24 Hours**
| Feature | Function | Output |
|---------|----------|---------|
| **Log Cleanup** | Removes old log files | System maintenance (no user output) |

---

## 🔐 **Permission Levels**

| Level | Access | Commands |
|-------|--------|----------|
| **God Users** | Full access | All commands + user authorization |
| **Main Moderators** | High-level moderation | `/stats`, `/funstats`, `/about` (publish), `/playercount` (publish) |
| **Moderators** | Standard moderation | `/customlist`, `/tox`, `/lookup`, username moderation buttons |
| **In-Game Admin** | Limited moderation | `/tox`, `/playercount` (publish), username moderation buttons |
| **Moderator Admin** | Custom list management | `/customlist` |
| **Authorized Users** | Social features | `/gamefriends` (except auth) |
| **Registered Users** | Personal stats | `/mystats` |
| **Everyone** | Basic commands | `/help`, `/about`, `/diss`, `/kbfact`, `/flip`, `/playercount`, `/register` |

---

## 💾 **Database Systems**

| Database | Purpose | Features |
|----------|---------|----------|
| **Friends DB** | Personal friend lists | User authorization, notification preferences, last seen tracking |
| **Custom List DB** | Global watch list | Watched players, notification cooldowns, life system |
| **Toxic Players DB** | Problem player tracking | Toxicity ratings, automatic watch list integration |
| **Username Game DB** | Moderation logging | Bad username detections, admin responses |
| **Registration DB** | User-game account linking | Discord to in-game account mapping |
| **Stats DB** | Bot usage tracking | Command usage, user interactions, fun statistics |

---

## 📱 **Interactive Elements**

| Type | Function | Access |
|------|----------|---------|
| **Username Moderation Buttons** | ✅ Mark OK / 🔨 Take Action | In-Game Admin + God Users |
| **Rich Embeds** | Status displays, player info, statistics | All authorized users |
| **Profile Integration** | AimXR API data fetching | Automatic system feature |
| **Cooldown Management** | Anti-spam protection | System-wide |
| **Visibility Controls** | Public/Private command responses | Role-based |

---

## 🎯 **Special Features**

### **Command Categories**
- **Fun**: Social commands, games, entertainment
- **Stats**: Player and server statistics
- **Admin**: Moderation and administrative tools
- **Game**: Game-related functionality
- **User**: General user commands
- **Utility**: Helper tools and utilities

### **Advanced Functionality**
- **Registration System**: Links Discord accounts to in-game profiles
- **Statistics Tracking**: Comprehensive bot usage analytics
- **Toxicity Management**: Multi-class player behavior tracking
- **Real-time Monitoring**: Live server and player status updates
- **Automated Notifications**: Smart alert system with cooldowns

---

**Missing from my original index:**
- 8 additional slash commands
- Registration system
- Statistics tracking database
- Advanced permission tiers
- Visibility controls
- Cooldown management systems

Would you like me to create detailed documentation for any specific section?