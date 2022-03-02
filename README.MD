# FNC - Flux Networks Chat

FNC is used to correct formatting issues created by other plugins and configurations.

## Installation

You can install his plugin by visiting the spigot page [Coming Soon]() to install FNC.

## Configuration

```
# FNC Configuration
#
# Placeholders:
# {message} - the chat message
# {name} - the player's name
# {displayname} - the player's display name / nickname
# {world} - the world name of the player's current world
# {prefix} - the player's highest priority prefix
# {suffix} - the player's highest priority suffix
# {prefixes} - the player's prefixes sorted by the highest priority
# {suffixes} - the player's suffixes sorted by the highest priority
# {username-color} - the player's or the group's username color
# {message-color} - the player's or the group's message color
#
# To reload the configuration, run '/fnc reload' command. Make sure you have the 'fnc.reload' permission assigned.
chat-format: "{prefix}{name}&r: {message}"

# Set the format per group.
# Note: Option for more advanced users. Remove comments to run.
group-formats:
#  default: "[default] {name}&r: {message}"
#  admin: "[admin] {name}&r: {message}"
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.