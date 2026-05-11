# **Team Fortress 2 scripts**

A collection of advanced configuration scripts and automation for Team Fortress 2, with specific class enhancements and improved engine logic.

---

## **Purpose**

**This project is designed to enhance the Team Fortress 2 experience by providing:**

- Advanced movement logic (null-cancelling strafe, jump duck, etcetera).
- Improved slot management and weapon tracking.
- Class-specific automation (Rocket jump, Sentry jump, Medic radar, etcetera).
- Optimized key bindings for faster reactions and consolidated actions.

---

## **Features**

### **Core logic (autoexec.cfg)**

**Base scripts that improve the engine's movement and interaction logic:**

- **Null-cancelling strafe script:** prevents movement locks when pressing opposing direction keys (A and D, and W and S) simultaneously.
- **Jump duck script:** automates crouching while jumping to ensure maximum height and mobility with a single key press.
- **Slot tracker script:** enhanced weapon switching logic that tracks the previous weapon.
- **Medic request / Spy alert script:** consolidated voice commands based on tap and hold key press (tap for Medic request, hold for Spy alert).

### **Scout scripts (scout.cfg)**

**Enhanced projectile management and fast-switch combat:**

- **Quick Flying Guillotine / Mad Milk throw script:** automated secondary throw that immediately returns to the previous weapon.
- **Quick Wrap Assassin / Sandman ball throw script:** automated melee projectile throw with quick weapon return logic.

### **Soldier scripts (soldier.cfg)**

**Advanced mobility tools:**

- **Rocket jump script:** automated rocket jumping script with integrated current slot tracking (instant if slot Nº 1 is active, delayed if other slot is active).

### **Pyro scripts (pyro.cfg)**

**Optimized utility usage and mobility enhancements:**

- **Quick melee attack script:** quick melee attack that automatically returns to the previous weapon.
- **Flare Gun / Thermal Thruster automation script:** consolidated secondary primary attack (Tap for Flare Gun, Hold for Thermal Thruster) that automatically returns to the previous weapon.
- **Flare jump script:** toggleable automated flare jumping with integrated current slot tracking (instant if slot Nº 2 is active, delayed if other slot is active).

### **Demoman scripts (demoman.cfg)**

**Simplified mobility:**

- **Sticky jump script:** automated sticky jumping.

### **Heavy scripts (heavyweapons.cfg)**

**Optimized food management:**

- **Quick consume / throw food script:** consolidated food management based on tap and hold key press (Tap to consume, Hold to throw to teammates), with toggable delay and current slot tracking (in case you're using Fists of Steel or Gloves of Running Urgently) with automatic previous weapon return.

### **Engineer scripts (engineer.cfg)**

**A comprehensive suite for building management and improved mobility and combat:**

- **Quick build / destroy script:** consolidated building logic using tap and hold behavior for sentries, dispensers, and teleporters.
- **Quick Eureka Effect teleport script:** optimized teleportation to spawn or teleporter exit using the Eureka Effect with a single key.
- **Quick Short Circuit energy ball / Wrangler shield/rocket script:** Short Circuit and Wrangler logic for quick projectile destruction and shielding.
- **Sentry jump script:** toggleable sentry jump script.

### **Medic scripts (medic.cfg)**

**Tools for improved team support and battlefield awareness:**

- **Quick Crusader's Crossbow heal script:** fast-switch healing script that fires the Crusader's Crossbow and immediately returns to the previous weapon.
- **Radar script:** toggleable high/normal autocall threshold based radar to locate all teammates at any moment.
- **ÜberCharge ready alert script:** quick team notification for ÜberCharge readiness.

### **Sniper scripts (sniper.cfg)**

**Advanced precision tools and utility automation:**

- **Quick Jarate throw script:** quick Jarate throw with immediate return to the previous weapon.
- **Quick scope script:** automated quick-scoping logic for faster precision shots.

### **Spy scripts (spy.cfg)**

**Toggable auto-disguise:**

- **Auto-disguise script:** toggable automated redisguising after attacking with the revolver or knife to maintain stealth.

---

## **Installation**

1. Go to the "Releases" section.
2. Go to the latest release.
3. Download the scripts (scripts.zip).
4. Unzip the downloaded file.
5. Open the resulting folder (scripts).
6. Copy the contents of the "scripts" folder to your Team Fortress 2 configuration directory (usually "C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\cfg").
7. Replace existing files if asked.