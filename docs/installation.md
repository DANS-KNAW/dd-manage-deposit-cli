Installation
============

Currently this project is built as an RPM package for RHEL8 and later. The RPM will install the binaries to
`/opt/dans.knaw.nl/dd-manage-deposit-cli` and the configuration files to `/etc/opt/dans.knaw.nl/dd-manage-deposit-cli`.

Building from source
--------------------

Prerequisites:

* Java 21 or higher
* Maven 3.8.7 or higher
* RPM

Steps:

```bash
git clone https://github.com/DANS-KNAW/dd-manage-deposit-cli.git
cd dd-manage-deposit-cli 
mvn clean install
```
