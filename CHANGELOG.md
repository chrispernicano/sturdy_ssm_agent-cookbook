sturdy_ssm_agent cookbook
===================

v2.1.2
------
* logrotate cookbook not supported on windows. 

v2.1.1
------
* Windows provider does not support :upgrade. Switch to :install

v2.1.0
------
* Support snap & package installs (defaulting to snap)

v2.0.0
------
* Change default service behavior to install/start

v1.1.0
------
* Preliminary SUSE Linux support

v1.0.1
------
* Preliminary Windows support (no more attribute evaluation errors on Windows)
* Fix test-kitchen cookbook name
* Add dokken kitchen.yaml

v1.0.0
------
* Fork to new name
* Foodcritic cleanup
* Fix Chef 13 warning/errors
* Fix Amazon Linux support
* Allow installation without Ohai `ec2` plugin data

v0.1.0
------
* Initial release
