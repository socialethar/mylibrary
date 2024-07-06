# It is test project.

```Use case
require_once "vendor/autoload.php";
use MyLibrary\MyName;
MyName::introduce();
```

```Application composer.json
"require": {
        "socialethar/mylibrary": "^1.0"
    },
```
## composer-raw-project\vendor\socialethar\mylibrary
### composer-raw-project\vendor\composer->autoload_psr4.php
```
return array(
    'MyLibrary\\' => array($vendorDir . '/socialethar/mylibrary/src'), //eta holo library dir
    'App\\' => array($baseDir . '/app'),
);
```
