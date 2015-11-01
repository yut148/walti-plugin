# Walti Plugin

This plugin enable to execute security scan by [Walti](https://walti.io/) after Jenkins has completed building.

## How to use

* Sign up [Walti](https://walti.io/) if you have not have an account yet.
* Install this plugin, then add "Execute scan by Walti" as post-build action in your project configuration.
* Input API key and secret, which are needed to execute scan.
* After you have inputted credentials, target candidates has been automatically refreshed. Select which server to scan.
* Check scan type you want to execute then click the save button.

## Related Repository

* [walti/walti-api-jar](https://github.com/walti/walti-api-jar)
