description: Install Pantheon from binary distribution
<!--- END of page meta data -->

# Install Binary Distribution

## Mac OS with Homebrew

### Prerequisites

* [Homebrew](https://brew.sh/)

### Install Using Homebrew

```bash
$ brew tap pegasyseng/pantheon
$ brew install pantheon
```
Display Pantheon command line help to confirm installation: 

```bash
$ pantheon --help
```

## Windows with Chocolatey 

### Prerequisites

* [Chocolatey](Install-Chocolatey.md)

### Install Using Chocolatey

To install from [Chocolatey package](https://chocolatey.org/packages/pantheon/): 

```bat
choco install pantheon
``` 

Display Pantheon command line help to confirm installation: 

```bat
pantheon --help
```

## Linux / Unix / Windows without Chocolatey

### Prerequisites 

* [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html)

!!!attention
    Pantheon requires Java 8+ to compile; earlier versions are not supported.
    Pantheon is currently supported only on 64-bit versions of Windows, and requires a 64-bit version of JDK/JRE. 
    We recommend that you also remove any 32-bit JDK/JRE installations.

### Install from Packaged Binaries

Download the Pantheon [packaged binaries](https://bintray.com/consensys/pegasys-repo/pantheon/_latestVersion#files).

Unpack the downloaded files and change into the `pantheon-<release>` directory. 

Display Pantheon command line help to confirm installation: 

```bash tab="Linux/macOS"
$ bin/pantheon --help
```

```bat tab="Windows"
bin\pantheon --help
```