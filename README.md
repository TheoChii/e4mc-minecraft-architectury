# e4mc

[![Modrinth Downloads](https://img.shields.io/modrinth/dt/qANg5Jrr?color=%2300af5c&logo=modrinth&style=for-the-badge)](https://modrinth.com/project/qANg5Jrr)
[![Modrinth Followers](https://img.shields.io/modrinth/followers/qANg5Jrr?color=00af5c&logo=modrinth&style=for-the-badge)](https://modrinth.com/project/qANg5Jrr)
[![CurseForge Downloads](https://img.shields.io/curseforge/dt/849519?style=for-the-badge&logo=curseforge&logoColor=f16436&color=f16436)](https://curseforge.com/minecraft/mc-mods/e4mc)

Open a LAN server to anyone, anywhere, anytime.

## Custom-domain fork

The `custom-domain-6.0.6` branch extends e4mc 6.0.6 with authenticated custom-domain requests for a compatible QUIClime relay.

Set `useBroker = false`, point `relayHost` and `relayPort` at the self-hosted relay, then set `customDomain` and `customDomainToken` in the generated e4mc configuration. Leave `customDomain` blank to keep the normal random-domain behavior.

The relay must run the matching custom-domain fork and be configured to allow the requested hostname. The shared token is only sent over the QUIC control connection and is never intended to be exposed to Minecraft players.

## Install

[Modrinth](https://modrinth.com/project/qANg5Jrr)

### Maven

e4mc is available in [Skyeven](https://maven.skye.vg) under the coordinates `link.e4mc:e4mc_minecraft-[platform]:[version]`.

## Usage

Open to LAN as normal

## Contributing

Please contribute

## License

[MIT](LICENSE)
