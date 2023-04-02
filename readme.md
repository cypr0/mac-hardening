![Maintenance](https://img.shields.io/maintenance/yes/2023?style=flat-square)
![GitHub](https://img.shields.io/github/license/cypr0/mac-hardening?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/cypr0/mac-hardening?style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/cypr0/mac-hardening?style=flat-square)
![macOS](https://svgshare.com/i/ZjP.svg)

# Hardening your Mac.

A quick way to make your Mac a bit more secure is to use configuration profiles.

This repo contains configuration profiles for macOS 13 (Ventura) and the browsers Chrome and Safari which are based on the corresponding CIS Benchmarks:

| Software            | CIS Benchmark                           | Version             |
| ------------------- | --------------------------------------- | ------------------- |
| macOS 13 (Ventura)  | CIS Apple macOS 13.0 Ventura Benchmark  | v1.0.0 - 11-14-2022 |
| macOS Safari        | CIS macOS Safari Benchmark              | v2.0.0 - 11-28-2017 |
| Google Chrome       | CIS Google Chrome Benchmark             | v2.1.0 - 12-21-2021 |

The Benchmarks are coming with two profile definitions:

Level 1: Items in this profile intend to:

* be practical and prudent;
* provide a clear security benefit; and
* not inhibit the utility of the technology beyond acceptable means.

Level 2: This profile extens the "Level 1" profile. Items in this profile exhibit one or more of the following charactteristics:

* are intended for environments or use cases where security is paramount.
* acts as defense in depth measure.
* may negatively inhibit the utility or performance of the technology.

Whereas the settings for Ventura, Safari and Chrome are only compatible with Mac systems, Firefox' hardening config can also be applied to Linux or Windows systems.

## Howto install the profiles

1. Copy the hardening profiles you want to use onto your Mac.

2. Open your system settings and search for "profile".

3. Add your desired hardening profile by clicking on the "+" and selecting the corresponding file.

## Recommended reading

[Apple Support - Howto use configuration profiles](https://support.apple.com/en-us/guide/mac-help/mh35561/mac)

[CIS Apple macOS 13.0 Ventura Benchmark](https://www.cisecurity.org/cis-benchmarks#:~:text=Apple-,macOS,-DOWNLOAD%20THE%20BENCHMARK)

[CIS macOS Safari Benchmark](https://www.cisecurity.org/cis-benchmarks#:~:text=Safari-,Browser,-DOWNLOAD%20THE%20BENCHMARK)

[CIS Google Chrome Benchmark](https://www.cisecurity.org/cis-benchmarks#:~:text=Google-,Chrome,-DOWNLOAD%20THE%20BENCHMARK)

## Contributing

Do you want to contribute? That’s great! Contributions are always welcome, no matter how large or small. If you found something odd, feel free to [submit a new issue](https://github.com/cypr0/mac-hardening/issues/), improve the code by [creating a pull request](https://github.com/cypr0/mac-hardening/pulls/), or by [sponsoring this project](https://github.com/sponsors/cypr0/).