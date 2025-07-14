
MiniSBC Install
--------------------------------------
A quick install guide & scripts for installing MiniSBC. It is recommended to start with a minimal install of the operating system. Notes on further tweaking your configuration are at end of the file.

## Operating Systems

### Debian
Debian is the preferred operating system by the FreeSWITCH developers. It supports the latest video dependencies and should be used if you want to do video mixing. Download Debian at https://cdimage.debian.org/cdimage/release/current/


### Ubuntu


## Security Considerations
Fail2ban is installed and pre-configured for all operating systems this repository works on, but the default settings may not be ideal depending on your needs. Please take a look at the jail file (/etc/fail2ban/jail.local on Debian) to configure it to suit your application and security model!

