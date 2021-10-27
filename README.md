# Saito-Game-Engine
Deliverables for Saito web3 foundation grant milestone two deliverables.

## Contents

### Documentation

* saito-game-engine.md 
* api.md
### /lib/
  gamengine.js library. This file contains extensive inline documentation of the core game and blockchain functions including move stack.

### /gametestsuite/

This folder is a full Saito Game. It is an example that exposes all the available functions and features of the Saito Game engine. These include UI elements and third party cryptocurrency integration.

---
## Testing

The functionality delivered in this milestone can all be viewed and tested using the [test game](/gametestsuite/) inluded. This folder contains local installation instructions.

This module is also install and accessible on the [Saito Arcade](https://saito.io/arcade).

Two browsers will be required to begin a game and test p2p features.

### Test with Westend Tokens

**Preparation**

Provide test clients with WND
1. Open two broswers to /arcade on the system being tested.
1. Expand the sidebar by clicking on the 'hamburger' menu.
2. Change the default crypto for the user in each browser to WND using the dropdown at the top of the Sidebar.
3. Fund both wallets with WND. (Public Keys will appear at the top of the sidebar, and be copied to the clipboard on click.)

Test web3 ecosystem integration
1. In a first browser select "GameTestSuite" from the menu to create a game invitation. <br />
  Make sure to select **Advanced** options and **select WND** as the crpyo for the game.
2. In the second browser, accept the invitation.
3. In both browsers follow the promts to initialise the game.
4. Enter the game. Request Payment, Make Payment and Check Balance routines can be checked against the live Westend network using the relevant buttons.
> Note: a log can be expanded from the right hand side of the screen to make test output and game actions visible.  