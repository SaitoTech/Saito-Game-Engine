
# Getting Started

This test suite is presented as a Saito game module.

# Installation

1. Install Saito Lite as per [the instructions](https://org.saito.tech/installation-instructions/).

1. Copy this (the gametestsuite) directory into /mods (should be there by default)

1. Edit/create /config/modules.config.js to include ```'gametestsuite/gametestsuite.js'``` and the crypto modules you want to test - eg ```'westend/westend.js'``` this module in both core/lite distributions<br />

1. recompile the javascript: ```npm run nuke```

1. restart the saito node: ```npm start```


---
## Example minimal modules.config.js for testing:

```
module.exports = {
  core: [
    'explorer/explorer.js',
    'registry/registry.js',
    'settings/settings.js',
    'arcade/arcade.js',
    'westend/westend.js'.
    'gametestsuite/gametestsuite.js'
  ],
  lite: [
    'registry/registry.js',
    'arcade/arcade.js',
    'westend/westend.js'.
  	'gametestsuite/gametestsuite.js'
    ]
}
```
> Note: DOT ```'polkadot/polkadot.js',``` and KSM ```kusama/kusama.js',``` entries into config/modules.config.js.
