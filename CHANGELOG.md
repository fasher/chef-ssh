# CHANGELOG for ssh
## 0.10.2
* Update the README
* Fix some spec tests
* Fix bug in `config` that did not allow `HostName` directive

## 0.10.0
* MAJOR rewrite, but no breaking changes known of.

## 0.6.5

* Add an option for the ssh port number to known_hosts (Scott Arthur)

## 0.6.4

* Use OHAI to determine the user's $HOME (Tom Duckering)

## 0.6.3:

* Fixed libary to make /root instead of /home/root work (Vincent Gijsen)
* Correct default action for config resource (joelwurtz)
* Use the correct user and path for the remove action (roderik)

## 0.6.0:

* Initial release of ssh
