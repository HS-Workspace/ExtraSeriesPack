# ExtraSeriesPack

Repository to host the minimal configurations required to apply resource packs for some projects of the Extra Series.

## Structure

The folders are always structured in the following format:
```
<plugin>/<variant>/<version>/plugins
```
- `<plugin>`: the plugin name
- `<variant>`: the variant of the configuration
- `<version>`: the tested Minecraft version of the configuration

For example, you can bisect this folder structure:
```
ExtraStorage/ItemsAdder/1.21.4/plugins
```
- `ExtraStorage`: the configuration is for the plugin `ExtraStorage`
- `ItemsAdder`: the configuration is specifically for ItemsAdder
- `1.21.4`: the configuration is tested the Minecraft 1.21.4

> [!NOTE]
> You can use the configuration in the Minecraft versions higher than the tested one, but there is no guarantee it will work since resource packs are the field that can have breaking changes when a new version is released.

## Private Assets

Some assets are excluded from this public repository for obvious reasons.

If you want to get the private assets, join [the Discord server](https://discord.gg/5vpVM6g4SV) and get yourself verified.
