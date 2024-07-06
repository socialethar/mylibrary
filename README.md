![Ethar](https://media.licdn.com/dms/image/D4D03AQFaKEkW8yN-zQ/profile-displayphoto-shrink_200_200/0/1689366199990?e=2147483647&v=beta&t=H3QN_EO1k87EANramDXBdjLTNW8zsMWTWy0KMXu4z6o)

# It is a test project. 100% working
## Developer- Mohammed Ethar

### Use case
```Use case
require_once "vendor/autoload.php";
use MyLibrary\MyName;
MyName::introduce();
```


### Application main composer.json
```Application composer.json
"require": {
        "socialethar/mylibrary": "^1.0"
    },
```
## composer-raw-project\vendor\socialethar\mylibrary  ->Library root directory
### composer-raw-project\vendor\composer->autoload_psr4.php
```
return array(
    'MyLibrary\\' => array($vendorDir . '/socialethar/mylibrary/src'), //eta holo library dir
    'App\\' => array($baseDir . '/app'),
);
```
