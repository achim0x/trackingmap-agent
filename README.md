# TBD Project Name


[![License](https://img.shields.io/badge/license-bsd-3.svg)](https://choosealicense.com/licenses/bsd-3-clause/) [![Repo Status](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [SW Documentation](#sw-documentation)
- [Issues, Ideas And Bugs](#issues-ideas-and-bugs)
- [License](#license)
- [Contribution](#contribution)

## Overview

This tool will connect to the The Things Network (TTN) via MQTT to collect informations from connected GPS Tracker (tested with SenseCAP Tracker T1000-B).
The latest location incl. the last way points and some addtional information will be shown on a map.

## Installation

>TODO

```bash
git clone https://github.com/achim0x/trackermap.git
cd trackermap
pip install .
```

create a .env file containig the credentials to access your TTN tenant with the following content:

```bash
TTN_APP_ID=my-lora-app
TTN_TENANT=ttn
TTN_REGION=eu1
TTN_API_KEY=NNSXS.…
```

## Usage

```bash
trackermap 
```

for mor detaild information use:

```bash
trackermap --verbose
```

## Examples

Check out the all the [Examples](./examples).

## SW Documentation

More information on the deployment and architecture can be found in the [documentation](./doc/README.md)

For Detailed Software Design run `$ /doc/detailed-design/make html` to generate the detailed design documentation that then can be found
in the folder `/doc/detailed-design/_build/html/index.html`

## Used Libraries

see [requirements.txt](requirements.txt)

## Issues, Ideas And Bugs

If you have further ideas or you found some bugs, great! Create an [issue](https://github.com/achim0x/tbd/issues) or if you are able and willing to fix it by yourself, clone the repository and create a pull request.

## License

The whole source code is published under [BSD-3-Clause](https://github.com/achim0x/template/blob/main/LICENSE).
Consider the different licenses of the used third party libraries too!

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, shall be licensed as above, without any additional terms or conditions.
