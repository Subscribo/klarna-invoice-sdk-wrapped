## Changelog

**Note: development version and not mentioned releases may contain changes not reflected in this CHANGELOG.**

### Version 1.0.3

* 2015-06-01 Slavo removed previous changes (private method Klarna::_fixMessageEncoding() and its use)
  and modified protected method Klarna::xmlrpc_call()
  - setting XML RPC Client global variables specifying encoding before the call

### Version 1.0.2

* 2015-05-20 Slavo changed and renamed private method Klarna::fixMessageEncoding() to Klarna::_fixMessageEncoding().


### Version 1.0.1

* 2015-05-13 Slavo added private method fixMessageEncoding() and its usage in Klarna.php (commit: 0d2de63) - fix
  for problem  with (possibly) invalid characters in thrown exception

### Version 1.0.0

* 2015-05-12 Slavo published version 1.0.0 of package Subscribo / Klarna Invoice SDK Wrapped containing files from
  [3.2.0 version of Klarna SDK](https://cdn.klarna.com/1.0/code/integration/library/server/api/klarna_php_3.2.0.zip)
