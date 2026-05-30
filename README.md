# Nexus Releases

Public download host for [Nexus](https://hellonexus.com) installers. Code lives in private repos; only the built binaries land here.

## Latest

| Platform | Stable URL |
|---|---|
| Windows | https://github.com/hello-nexus/nexus-releases/releases/latest/download/Nexus-Setup.exe |
| macOS (Apple Silicon) | https://github.com/hello-nexus/nexus-releases/releases/latest/download/Nexus.dmg |

Or visit https://hellonexus.com/download to grab the right installer for your OS automatically.

## Versioning

Tags are `v<N>` where `N` is the nexus-service `git rev-list --count HEAD`. Same number returned by the running service's `/ping` endpoint as `version`.
