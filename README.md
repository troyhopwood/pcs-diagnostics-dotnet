[![Build][build-badge]][build-url]
[![Issues][issues-badge]][issues-url]
[![Gitter][gitter-badge]][gitter-url]

Diagnostics Micro Service
=================


Overview
========

The Diagnostics Service is designed to be used as part of the Azure IoT Solution Accelerators. If users have opted in, It allows for collecting user events to allow for understanding how people use and interact with various features. Events (e.g. simulation started, rule created, etc.) are collected by the diagnostics micro service, anonymized, and pushed to the specified endpoint. For deployments via AzureIoTSolutions.com, this endpoint is Microsoft. Users can opt in/out of sharing this anonymous data from within the solution's portal. 

For your solutions, you can use the diagnostics service to push data to an endpoint of your choosing so you can understand how your customers are using the solutions you create.


Contributing
============
Refer to our [contribution guidelines](docs/CONTRIBUTING.md)

License
=======
Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE) License.

[build-badge]: https://img.shields.io/travis/Azure/diagnostics-dotnet.svg
[build-url]: https://travis-ci.org/Azure/diagnostics-dotnet
[issues-badge]: https://img.shields.io/github/issues/azure/diagnostics-dotnet.svg
[issues-url]: https://github.com/azure/diagnostics-dotnet/issues
[gitter-badge]: https://img.shields.io/gitter/room/azure/iot-solutions.js.svg
[gitter-url]: https://gitter.im/azure/iot-solutions
