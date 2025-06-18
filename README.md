# DiscordSRV Alerts Configuration

![DiscordSRV Logo](https://i.imgur.com/J0wYVXt.png)

A comprehensive collection of DiscordSRV alert configurations for various Minecraft server events, designed to enhance your server's Discord integration.

## Features

- **Multiple Event Types**: Configure alerts for votes, punishments, fish catches, shop transactions, and more
- **Customizable Embeds**: Rich, visually appealing Discord embeds with thumbnails and colors
- **Flexible Triggers**: Supports various event triggers from different plugins
- **Easy Configuration**: Simple YAML format with clear documentation

## Supported Events

- **Votifier Events**: Player vote notifications with rewards information
- **Punishment Events**: Bans, mutes, warns with detailed information
- **Game Events**: 
  - Night skip notifications
  - Flint & steel usage tracking
  - Fishing activities (both default and EvenMoreFish)
- **Economy Events**:
  - Balance top rankings
  - Top voter rankings
- **Anti-Cheat Alerts**: Matrix and Spartan violation detection
- **Player Activities**:
  - Sign placements
  - Book writings
  - AFK status changes
  - Private messages
  - Gamemode changes
- **Shop Transactions**: ChestShop buy/sell/create/out-of-stock alerts
- **Admin Actions**: OP/DeOP commands, console commands, helpop requests
- **Death Events**: Player deaths with location information

## Installation

1. Ensure you have [DiscordSRV](https://www.spigotmc.org/resources/discordsrv.18494/) installed on your Minecraft server
2. Place the `alerts.yml` file in your DiscordSRV directory (usually `/plugins/DiscordSRV/`)
3. Restart your server or reload DiscordSRV

## Configuration

1. Replace all instances of `YOUR DISCORD CHANNEL ID` with your actual Discord channel IDs
2. Customize server names, IPs, and reward messages to match your server
3. Adjust emoji IDs to match your server's custom emojis
4. Modify colors and thumbnails as desired

## Customization Tips

- **Emojis**: Replace all `<:emoji_name:emoji_id>` with your server's custom emojis
- **Server Info**: Update all instances of `SERVER NAME` and `play.servername.com`
- **Rewards**: Edit the reward messages in the Votifier event section
- **Colors**: Change embed colors by modifying the hex color codes

## Plugin Dependencies

This configuration works best with these plugins:

- [DiscordSRV](https://www.spigotmc.org/resources/discordsrv.18494/)
- [AdvancedBan](https://www.spigotmc.org/resources/advancedban.8695/) (for punishment events)
- [Votifier](https://www.spigotmc.org/resources/votifier.27924/) (for vote events)
- [ChestShop](https://dev.bukkit.org/projects/chestshop) (for shop events)
- [EssentialsX](https://essentialsx.net/) (for economy and player commands)
- [Matrix](https://matrix.rip/) or [Spartan](https://www.spigotmc.org/resources/spartan-advanced-anti-cheat-hack-blocker.25638/) (for anti-cheat alerts)

## Support

For support or configuration help:
- Open an issue on this GitHub repository
- Join our [Discord support server](https://discord.gg/THNHYkh2aV)

## License

This configuration is provided under the MIT License.

## Credits

Created by [xfrogly](https://github.com/xfrogly)

---

**Note**: Remember to back up your existing `alerts.yml` before replacing it with this configuration!
