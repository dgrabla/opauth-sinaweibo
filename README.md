Opauth-Sina
=============
[Opauth][1] strategy for Sina Weibo authentication.

Implemented based on Opauth's Facebook Strategy

Getting started
----------------
0. Make sure your cake installation supports UTF8

1. Install Opauth-Sina:
   ```bash
   cd path_to_opauth/Strategy
   git clone git://github.com/dgrabla/opauth-sina.git Sina
   ```
2. Create Sina Weibo application at http://open.weibo.com/apps/
   - It is a web application
	 - Callback: http://path_to_opauth/sina_callback

3. Configure Opauth-Sina Weibo strategy with `key` and `secret`.

4. Direct user to `http://path_to_opauth/sina` to authenticate

Strategy configuration
----------------------

Required parameters:

```php
<?php
'Sina' => array(
	'key' => 'YOUR APP KEY',
	'secret' => 'YOUR APP SECRET'
)
```

License
---------
Opauth-Sina Weibo is MIT Licensed  
Copyright © 2012 U-Zyn Chua (http://uzyn.com)

[1]: https://github.com/uzyn/opauth
