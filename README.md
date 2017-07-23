[![Build][build-badge]][build-url]
[![Issues][issues-badge]][issues-url]
[![Gitter][gitter-badge]][gitter-url]

Work in progress:
* Development notes: [DEVELOPMENT.md](DEVELOPMENT.md)
* Wiki: https://github.com/Azure/device-simulation-dotnet/wiki
* Simulation specs: https://github.com/Azure/device-simulation-dotnet/wiki/Device-Types

Device Simulation
=================

This service allows to manage a pool of simulated devices, to test the end-to-end flow of device-to-cloud (D2C) telemetry, invoking cloud-to-device (C2D) commands, methods, etc.

The microservice provides a RESTful endpoint to create a simulation (only one), to start and stop the simulation. Each simulation is composed by a set of virtual devices, of different types, sending telemetry and receiving commands.

The complete documentation is available in the wiki [here](https://github.com/Azure/device-simulation-dotnet/wiki).

Other documents
===============

* [Contributing and Development setup](CONTRIBUTING.md)
* [Development setup, scripts and tools](DEVELOPMENT.md)

[build-badge]: https://img.shields.io/travis/Azure/device-simulation-dotnet.svg
[build-url]: https://travis-ci.org/Azure/device-simulation-dotnet
[issues-badge]: https://img.shields.io/github/issues/azure/device-simulation-dotnet.svg
[issues-url]: https://github.com/azure/device-simulation-dotnet/issues
[gitter-badge]: https://img.shields.io/gitter/room/azure/iot-pcs.js.svg
[gitter-url]: https://gitter.im/azure/iot-pcs