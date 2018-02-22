Media manager 
===============

Media manager for `local` disk.

## Installation

```
$ composer require linnella/media-manager:dev-master

$ php artisan admin:import media-manager
```
Add a disk config in `config/admin.php`:

```php

    'extensions' => [
        'media-manager' => [
            // Select a local disk that you configured in `config/filesystem.php`
            'disk' => 'uploads'
        ],
    ],

```


Open `http://localhost/admin/media`.

License
------------
Licensed under [The MIT License (MIT)](LICENSE).
