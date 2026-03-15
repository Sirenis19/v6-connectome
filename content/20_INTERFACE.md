# 20_INTERFACE

**Parent: [[00_ROOT]]**

## [PROGRAMMER_QUICK_START]
This node defines the mechanical interaction between the User and the Connectome.

### [LOGIC_GATES]
- **Cyan Nodes (Core)**: These are "Read-Only" logic states. They represent stable systems theory.
- **Purple Nodes (Interface)**: These are "Interactive" nodes. This is where the game mechanics (dialogue trees, choice paths) live.
- **Red Nodes (Entropy)**: These are "Hazard" states. Entering these should trigger a "Signal Loss" UI effect.

### [MECHANICAL_TASKS]
1. **Graph Visualization**: Use `quartz.config.ts` to lock node colors (Cyan: #00ffff, Purple: #a200ff, Red: #ff0000).
2. **Pathfinding**: Ensure the `[GOTO: [[Node]]]` syntax in the README acts as a button-press in the web view.
3. **State Tracking**: (Future Phase) Implement a simple cookie or local storage to track which "Recovery Protocols" a user has unlocked.

---
[SYSTEM_LAW]
The code must be weightless. Prioritize speed and clarity over 
complex animations. The goal is neural plasticity, not distraction.