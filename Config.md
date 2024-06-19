
# Config File Preview
```
# ╔══╗   ╔═══╗   ╔╗╔╗   ╔═══╗   ╔════╗   ╔══╗   ╔══╗         ╔══╗    ╔═══╗   ╔╗╔╗   ╔═══╗   ╔╗     ╔══╗   ╔═══╗   ╔╗  ╔╗   ╔═══╗   ╔╗ ╔╗   ╔════╗
# ║╔═╝   ║╔═╗║   ║║║║   ║╔═╗║   ╚═╗╔═╝   ╚╗╔╝   ║╔═╝         ║╔╗╚╗   ║╔══╝   ║║║║   ║╔══╝   ║║     ║╔╗║   ║╔═╗║   ║║  ║║   ║╔══╝   ║╚═╝║   ╚═╗╔═╝
# ║║     ║╚═╝║   ║╚╝║   ║╚═╝║     ║║      ║║    ║║           ║║╚╗║   ║╚══╗   ║║║║   ║╚══╗   ║║     ║║║║   ║╚═╝║   ║╚╗╔╝║   ║╚══╗   ║╔╗ ║     ║║
# ║║     ║╔╗╔╝   ╚═╗║   ║╔══╝     ║║      ║║    ║║           ║║ ║║   ║╔══╝   ║╚╝║   ║╔══╝   ║║     ║║║║   ║╔══╝   ║╔╗╔╗║   ║╔══╝   ║║╚╗║     ║║
# ║╚═╗   ║║║║     ╔╝║   ║║        ║║     ╔╝╚╗   ║╚═╗         ║╚═╝║   ║╚══╗   ╚╗╔╝   ║╚══╗   ║╚═╗   ║╚╝║   ║║      ║║╚╝║║   ║╚══╗   ║║ ║║     ║║
# ╚══╝   ╚╝╚╝     ╚═╝   ╚╝        ╚╝     ╚══╝   ╚══╝         ╚═══╝   ╚═══╝    ╚╝    ╚═══╝   ╚══╝   ╚══╝   ╚╝      ╚╝  ╚╝   ╚═══╝   ╚╝ ╚╝     ╚╝


#  Created by: madtrent
#
#  Support:
#       Discord - https://discord.crypticmc.net
#       Website - https://crypticmc.net/support
#       Docs - https://github.com/Madtrent/CrypticRespawn-Docs

# Prefix for all plugin messages
prefix: "&5&lᴄʀʏᴘᴛɪᴄ ʀᴇѕᴘᴀᴡɴ &7&l»&f "

# Language file to use (default is 'en.yml')
lang: en

# Support settings
support:
  vault: true  # Set to true to enable Vault support for economy features

# Settings for the deathBack command
deathBack:
  enabled: true  # Enable or disable the deathBack feature
  needPermission: true  # Require permission to use the deathBack feature
  vault:
    enabled: true  # Enable or disable economy cost for deathBack
    cost: 100  # Cost for using deathBack, if Vault is enabled

# Respawn settings
respawn:
  delay: 5  # Delay in seconds before respawning
  title:
    enabled: true  # Enable or disable respawn titles
  fastRespawn:
    enabled: true  # Enable or disable fast respawn feature
    needPermission: true  # Require permission for fast respawn
    vault:
      enabled: true  # Enable or disable economy cost for fast respawn
      cost: 100  # Cost for fast respawn, if Vault is enabled
  worlds: # Worlds where the respawn settings apply
    - world
    - world_nether
    - world_the_end

# Settings for lightning strikes on death
deathLightning:
  player: true  # Enable lightning on player kills
  mob: false  # Enable lightning on mob kills
  environment: false  # Enable lightning on environmental deaths

# Default respawn location use /setrespawn in-game to set this
respawnLocation:
  world: world
  x: 0
  y: 0
  z: 0
  yaw: 0
  pitch: 0
```


