# Vioneta Agro Community Add-on: InfluxDB

[![GitHub Release][releases-shield]][releases]
![Project Stage][project-stage-shield]
[![License][license-shield]](LICENSE.md)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[![Github Actions][github-actions-shield]][github-actions]
![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]

Scalable datastore for metrics, events, and real-time analytics.

## About

InfluxDB is an open source time series database optimized for high-write-volume.
It's useful for recording metrics, sensor data, events,
and performing analytics. It exposes an HTTP API for client interaction and is
often used in combination with Grafana to visualize the data.

This add-on comes with Chronograf & Kapacitor pre-installed as well. Which
gives you a nice InfluxDB admin interface for managing your users, databases,
data retention settings, and lets you peek inside the database using the
Data Explorer.

[:books: Read the full add-on documentation][docs]

## License

MIT License

Copyright (c) 2018-2024 Vioneta

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[commits-shield]: https://img.shields.io/github/commit-activity/y/Vioneta/addon-influxdb.svg
[commits]: https://github.com/Vioneta/addon-influxdb/commits/main
[docs]: https://github.com/Vioneta/addon-influxdb/blob/main/influxdb/DOCS.md
[github-actions-shield]: https://github.com/Vioneta/addon-influxdb/workflows/CI/badge.svg
[github-actions]: https://github.com/Vioneta/addon-influxdb/actions
[i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[license-shield]: https://img.shields.io/github/license/Vioneta/addon-influxdb.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2024.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[releases-shield]: https://img.shields.io/github/release/Vioneta/addon-influxdb.svg
[releases]: https://github.com/Vioneta/addon-influxdb/releases
