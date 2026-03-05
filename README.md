# WitchWizardWonders
Landing page for Witch and Wizard Wonders Unity projects

## Coming Soon
**Cozy Core**

A lightweight framework that covers the fundementals of Cozy game development.
Cozy Core includes:

### Runtime Systems
- **GameContext**  
  Composition root for Runtime systems (inventory, crafting, save/load).
- **Inventory**
  - Item catalog support
  - Capacity limits
  - Change notifications
- **Crafting**
  - Recipe definitions
  - Crafting service with validation
- **Interaction**
  - `IInteractable` contract
  - `Interactor` for focus + interaction flow
- **Save / Load**
  - Simple versioned save data
  - Explicit save triggers
  - Player position support

### UI (View Layer)
- Abstract **ViewBase / ModelView<T>** pattern
- Explicit bind / unbind lifecycle (no `Find()` calls inside views)
- Included views:
  - PromptView
  - InventoryView
  - CraftingView
- Demo UI binder showing one recommended wiring approach

## In Development
**VCCG Core**

A lightweight framework that covers the fundementals of Card game development.

**Cozy NPCs**

An NPC and Dialogue plugin for Cozy Core
