# Sonos2mqtt

[![npm](https://img.shields.io/npm/v/sonos2mqtt.svg?style=flat-square)](https://www.npmjs.com/package/sonos2mqtt)
[![docker pulls][badge_docker]][link_docker]
[![Support me on Github][badge_sponsor]][link_sponsor]
[![github issues][badge_issues]][link_issues]
[![Run build and publish][badge_build]][link_build]
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-4-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
[![mqtt-smarthome](https://img.shields.io/badge/mqtt-smarthome-blue.svg?style=flat-square)](https://github.com/mqtt-smarthome/mqtt-smarthome)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=flat-square)](https://github.com/semantic-release/semantic-release)

This node application is a bridge between the Sonos and a mqtt server. The status of all your sonos devices will be published to mqtt and you can control the sonos speakers over mqtt.

It's intended as a building block in heterogenous smart home environments where an MQTT message broker is used as the centralized message bus. See [MQTT Smarthome on Github](https://github.com/mqtt-smarthome/mqtt-smarthome) for a rationale and architectural overview.

Check out the other bridges in the [software list](https://github.com/mqtt-smarthome/mqtt-smarthome/blob/master/Software.md)

## Documentation

See: [https://svrooij.github.io/sonos2mqtt](https://svrooij.github.io/sonos2mqtt)

## Node-sonos-ts

This library depends on [node-sonos-ts](https://github.com/svrooij/node-sonos-ts/) which I also developed. All other libraries using node-sonos-ts should also be able to implemented all the nice features included there. Like **notifications**  or **text-to-speech** which are the coolest new additions for **sonos2mqtt**!

## Beer or Coffee

I'm a big fan of beer and coffee. To provide something extra to everybody who is sponsoring me, I'll provide a hosted TTS server for all my sponsors.

This bridge and the [sonos package](https://github.com/svrooij/node-sonos-ts) took me a lot of hours to build, so I invite everyone using it to at least have a look at my [Sponsor page](https://github.com/sponsors/svrooij). Even though the sponsoring tiers are monthly you can also cancel anytime :wink:

## Special thanks

The latest version of this bridge is inspired on [hue2mqtt.js](https://github.com/hobbyquaker/hue2mqtt.js) by [Sabastian Raff](https://github.com/hobbyquaker). That was a great sample on how to create a globally installed, command-line, something2mqtt bridge.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://svrooij.nl"><img src="https://avatars2.githubusercontent.com/u/1292510?v=4" width="100px;" alt=""/><br /><sub><b>Stephan van Rooij</b></sub></a><br /><a href="https://github.com/svrooij/sonos2mqtt/commits?author=svrooij" title="Code">💻</a> <a href="https://github.com/svrooij/sonos2mqtt/commits?author=svrooij" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/cheanrod"><img src="https://avatars3.githubusercontent.com/u/35066927?v=4" width="100px;" alt=""/><br /><sub><b>Sven Werner</b></sub></a><br /><a href="#platform-cheanrod" title="Packaging/porting to new platform">📦</a> <a href="https://github.com/svrooij/sonos2mqtt/commits?author=cheanrod" title="Code">💻</a></td>
    <td align="center"><a href="https://mi.o-o.im"><img src="https://avatars0.githubusercontent.com/u/7872104?v=4" width="100px;" alt=""/><br /><sub><b>Matthias Burgfried</b></sub></a><br /><a href="https://github.com/svrooij/sonos2mqtt/commits?author=matthias-burgfried" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/mqtt-fan"><img src="https://avatars1.githubusercontent.com/u/32242849?v=4" width="100px;" alt=""/><br /><sub><b>mqtt-fan</b></sub></a><br /><a href="https://github.com/svrooij/sonos2mqtt/commits?author=mqtt-fan" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification.
Contributions of any kind welcome!

[badge_sponsor]: https://img.shields.io/badge/Sponsor-on%20Github-red
[badge_issues]: https://img.shields.io/github/issues/svrooij/sonos2mqtt
[badge_docker]: https://img.shields.io/docker/pulls/svrooij/sonos2mqtt
[badge_build]: https://github.com/svrooij/sonos2mqtt/workflows/Run%20tests%20and%20publish/badge.svg

[link_sponsor]: https://github.com/sponsors/svrooij
[link_issues]: https://github.com/svrooij/sonos2mqtt/issues
[link_build]: https://github.com/svrooij/sonos2mqtt/actions
[link_docker]: https://hub.docker.com/r/svrooij/sonos2mqtt

