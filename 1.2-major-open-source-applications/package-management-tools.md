# Package Management Tools

## Package
- A collection of files needed to install an application

## Package Management 
- How installation packages are tracked and managed

# Debian Based Systems
- Debian 
- Ubuntu

## Dpkg
- Short for Debian package, is a package archive format that contains package metadata.  
- DEB files are package installation files for Debian based Linux distributions.
- Debian based systems that use dpkg files for package installation can take advantage of APT (Advanced Package Tool) for managing packages and their dependencies.
- To install a Dpkg package:
    - `sudo dpkg -i package_name`

- To uninstall a Dpkg package:
    - `sudo dpkg --remove application_name`

## apt-get
- Advanced Package Tool (APT) is a free and open source interface that works with core libraries to handle the installation and removal of software packages on Debian based systems
- APT automates the retrieval and validation of softwware packages as well as other dependancies.
- APT allows users to search for and install packages from repositories.
- Various GUI front-ends are available for with APT, such as Synaptic or Ubuntu Software Center.

# Red Hat Based Systems
- Red Hat
- Fedora
- CentOS
- SUSE

## RPM
- Red Hat Package Manager
- Red Hat Package Manager is widely used package management system
- Red Hat based systems that use .rpm files for package installation can take advantage of YUM for managing packages and their dependencies.
- To install a RPM package
    - `sudo rpm -i package_name`

- To uninstall a RPM package:
    - `sudo rpm -e application_name`

## yum
- Yellowdog Updater Modified
- Free and open source package management utility for RPM based systems
- YUM allows for automated updates and package dependancy management
- Fedora uses a rewrite of YUM named DNF


## Compiling from Source
1. Extract files
    - `tar xzf file_name`
2. `cd` into extracted file folder
    - `cd file_folder`
3. Configure the files using the `configure` script
    - `./configure`
4. Compile the source code
    - `make`
5. Install the binaries
    - `sudo make install`
6. Run the application
    - `application_name`
7. Uninstall the application
    - `sudo make uninstall`
