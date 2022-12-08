# nyaa-init
The program that sits between the services and the service manager.

# What is nyaa-init?
nyaa-init is a WIP (Work In Progress) program that sits between the service manager and the services you use. Think of it as a service manager for a service manager.
`init/service manager <-> nyaa-init <-> service`
The services are written in nyaa-init with a custom format, and nyaa-init takes care of the rest.

# Advantages of doing it like this
* Achieving full init system freedom without compromising on compatibility
* Less learning curve when switching to a new init system since commands are mainly on nyaa-init
* Services work as expected, as the init system handles the actual service management

# Disadvantages of doing it like this
* Init system spesific features wont be used (Like systemd-networkd for example)

# Supported init systems
* Runit 
* Systemd coming soon
* Openrc coming soon

# Installation
No installation instructions yet. This is very WIP and break your system, so it is not advised to use it yet.


