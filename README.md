# CrypticRespawn Plugin Documentation

## Introduction
CrypticRespawn is a versatile plugin designed to enhance the respawn experience on your Minecraft server. It offers various features such as customized respawn points, fast respawn options, death location tracking, and more. This documentation will guide you through the commands, permissions, and configuration required to get the most out of CrypticRespawn.

## Commands

### Help Command
- **/crypticrespawn help** - Show this help message.

### Admin Commands
- **/crypticrespawn reload <all|lang|config>** - Reload configurations.
- **/crypticrespawn version** - Show plugin version.
- **/setrespawn** - Sets the respawn point.

### Player Commands
- **/deathback** - Teleports you to your last death location.
- **/fastrespawn** - Respawns you immediately.

## Permissions

- **crypticrespawn.admin**: General administrative permission. Allows access to all administrative commands.
- **crypticrespawn.version**: Allows access to the command that shows the plugin version information.
- **crypticrespawn.reload**: Allows access to the command that reloads the plugin configurations.
- **crypticrespawn.setrespawn**: Allows access to the command that sets the respawn point.

- **crypticrespawn.deathback**: Allows players to use the `/deathback` command to teleport to their last death location.
- **crypticrespawn.deathback.other**: Allows players to send other players to their last death location using the `/deathback <player>` command.
- **crypticrespawn.deathback.costbypass**: Allows players to bypass the cost associated with using the `/deathback` command when Vault support is enabled.

- **crypticrespawn.fastrespawn**: Allows players to use the `/fastrespawn` command to respawn immediately after death.
- **crypticrespawn.fastrespawn.costbypass**: Allows players to bypass the cost associated with using the `/fastrespawn` command when Vault support is enabled.

- **crypticrespawn.instantrespawn**: Allows players to instantly respawn without waiting for the respawn timer.

## Configuration

### Configuring the Plugin
To configure CrypticRespawn, you need to edit the `config.yml` file located in the plugin's data folder [[View Here]](https://github.com/Madtrent/CrypticRespawn-Docs/blob/main/Config.md).

### Custom Language File
You can create your own language file by creating a YML file with all the necessary values and saving the name of that file in the `config.yml`. This allows you to customize the messages sent to players.

### Using Vault for Economy Features
CrypticRespawn integrates with Vault to provide economy-based features. Vault is a permissions, chat, and economy API that allows plugins to interact with various economy plugins. To use Vault with CrypticRespawn, you need to have Vault and an economy plugin (such as EssentialsX or CMI) installed on your server.

#### Setting Up Vault
1. **Install Vault**: Download and place the Vault plugin jar file into your server's `plugins` folder.
2. **Install an Economy Plugin**: Download and place the jar file of your preferred economy plugin (e.g., EssentialsX or CMI) into your server's `plugins` folder.
3. **Restart the Server**: Restart your server to load the plugins.

#### Configuring Vault in CrypticRespawn
In the `config.yml` file, ensure the following settings are configured:
- **support.vault** - Set to `true` to enable Vault support.
  
  ```
  support:
    vault: true
  ```
- **deathBack.vault.enabled** - Set to `true` to enable economy features for the death back command.
- **deathBack.vault.cost** - Set the cost for using the death back feature.
- **fastRespawn.vault.enabled** - Set to `true` to enable economy features for the fast Respawn function.
- **fastRespawn.vault.cost** - Set the cost for using the fast Respawn feature.

```
  vault:
    enabled: true
    cost: 100
```

## Conclusion
CrypticRespawn is a powerful plugin that can significantly enhance the gameplay experience on your server. By configuring it properly and using the available commands and permissions, you can provide a seamless and enjoyable respawn experience for your players. If you have any questions or need further assistance, please refer to the plugin's support channels. Happy respawning!
