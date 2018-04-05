
Changelog
=========

0.2.2 (2016-01-28)
------------------
* First release on PyPI.

0.3.0 (2016-04-12)
------------------
* Added Tests
* Added Filter Methods on Components
* Renamed *[component]_data_dict* in *data_dict* (backward incompatibility)
* Bug Fix

0.3.1 (2017-01-30)
------------------
* Added Added create_or_update_recipient to provider

0.3.2 (2017-02-17)
------------------
* Added Exception handler: requests.exceptions.ConnectionError, OpenSSL.SSL.SysCallError

0.3.3 (2017-03-10)
------------------
* Added Exception handler: Exception. A message with detail is logged

0.3.4 (2017-03-27)
------------------
* Added Exception during retrieve access token

0.3.5 (2017-03-27)
------------------
* Added ClientAuthenticationException that war raised when authentication fails (response 400)
