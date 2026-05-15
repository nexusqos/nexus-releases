# Qos Releases

Public download host for [Qos](https://nexusqos.com) installers. Code lives in private repos; only the built binaries land here.

## Latest

| Platform | Stable URL |
|---|---|
| Windows | https://github.com/nexusqos/qos-releases/releases/latest/download/Qos-Setup.exe |
| macOS (Apple Silicon) | https://github.com/nexusqos/qos-releases/releases/latest/download/Qos.dmg |

Or visit https://nexusqos.com/download to grab the right installer for your OS automatically.

## Versioning

Tags are `v<N>` where `N` is the qos-service `git rev-list --count HEAD`. Same number returned by the running service's `/ping` endpoint as `version`.
