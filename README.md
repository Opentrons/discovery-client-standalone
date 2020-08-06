# discovery-client-standalone

Standalone version of the Opentrons [Discovery Client CLI][]

## installation

1. Download the [latest release][] for your OS
2. (Optional) Copy or symlink the executable into a directory in your `PATH`

## usage

This example uses macOS, but replace the executable with whatever file you downloaded. See the [discovery client cli][] documentation for more usage details.

```shell
# print help and usage
./discovery-client-macos --help

# browse for all robots
./discovery-client-macos browse

# find the IP address of a specific robot by its name
./discovery-client-macos find OT2P00000000A00
```

[discovery client cli]: https://github.com/Opentrons/opentrons/tree/edge/discovery-client#cli
[latest release]: https://github.com/Opentrons/discovery-client-standalone/releases/latest
