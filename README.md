[![Build Status](https://travis-ci.org/intelsdi-x/snap-plugin-publisher-file.svg?branch=master)](https://travis-ci.org/intelsdi-x/snap-plugin-publisher-file)

# snap collector plugin - ScaleIO

This plugin supports collecting metrics from a ScaleIO cluster

It's used in the [snap framework](http://github.com/intelsdi-x/snap).

1. [Getting Started](#getting-started)
  * [System Requirements](#system-requirements)
  * [Installation](#installation)
  * [Configuration and Usage](#configuration-and-usage)
2. [Documentation](#documentation)
  * [Collected Metrics](#collected-metrics)
  * [Examples](#examples)
  * [Roadmap](#roadmap)
3. [Community Support](#community-support)
4. [Contributing](#contributing)
5. [License](#license)
6. [Acknowledgements](#acknowledgements)

## Getting Started

### System Requirements

* [golang 1.5+](https://golang.org/dl/) (needed only for building)

### Installation

#### Download File plugin binary:
You can get the pre-built binaries for your OS and architecture at snap's [GitHub Releases](https://github.com/intelsdi-x/snap/releases) page.

#### To build the plugin binary:
Fork https://github.com/intelsdi-x/snap-plugin-collector-scaleio
Clone repo into `$GOPATH/src/github.com/intelsdi-x/`:

```
$ git clone https://github.com/<yourGithubID>/snap-plugin-collector-scaleio.git
```

Build the plugin by running make within the cloned repo:
```
$ make
```
This builds the plugin in `./build/rootfs/`

### Configuration and Usage
* Set up the [snap framework](https://github.com/intelsdi-x/snap/blob/master/README.md#getting-started)
* Ensure `$SNAP_PATH` is exported  
`export SNAP_PATH=$GOPATH/src/github.com/intelsdi-x/snap/build`

## Documentation
<< @TODO

### Examples
<< @TODO

### Roadmap

There is currently in Alpha. Please let us know of any bugs you see.

If you have a feature request, please add it as an [issue](https://github.com/intelsdi-x/snap-plugin-collector-scaleio/issues/new) and/or submit a [pull request](https://github.com/intelsdi-x/snap-plugin-collector-scaleio/pulls).

## Community Support
This repository is one of **many** plugins in **snap**, a powerful telemetry framework. See the full project at http://github.com/intelsdi-x/snap To reach out to other users, head to the [main framework](https://github.com/intelsdi-x/snap#community-support)

## Contributing
We love contributions! 

There's more than one way to give back, from examples to blogs to code updates. See our recommended process in [CONTRIBUTING.md](CONTRIBUTING.md).

## License
[Snap](http://github.com/intelsdi-x/snap), along with this plugin, is an Open Source software released under the Apache 2.0 [License](LICENSE).

## Acknowledgements

* Author: [Taylor Thomas](https://github.com/thomastaylor312)

And **thank you!** Your contribution, through code and participation, is incredibly important to us.