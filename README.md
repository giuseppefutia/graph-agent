# graph-agent
Implementation of a ReAct Agent using Knowledge Graphs.

## How to Use the Code of this Repository
To use this repository, you need a running instance of Neo4j and information access to ChatGPT APIs.

Update the [config.ini](config.ini) file with the relevant Neo4j credentials and the OpenAI API keys.

It is recommended to set up a Python virtual environment for this project. For example:
```shell
$ python -m venv venv
```

Unless otherwise stated, the code in this repo is tested with Python version 3.8/3.9/3.10.

Modules make use of a `MakeFiles` based approach to simplfy operations, make sure you can run 
the make command:

```shell
$ make -version
```

Generally the `GNU make` is available on many package managers for a wide range of OSes.

```shell
$ choco install make # Windows Os
$ apt install make # Debian & derivated OSes (including ubuntu)
$ yum install make # Centos 
```

macOS's users should have `make` available through XCode - Command line tools:

```shell
$ xcode-select --install
```
alteratively  `GNU Make` can be installed via brew
```shell
brew install make
```

For further information, please refere to the README.md available in each modules's (MD) directory.
