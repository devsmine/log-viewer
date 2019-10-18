# Configure

Add the following to the main composer.json

```json
"repositories": [
    {
        "type": "path",
        "version": "dev-master",
        "url": "/home/nghi/log-viewer"
    }
],
"require": [
    "devsmine/log-viewer": "dev-master",
]

```

Then add the service to config/app.php

Then 
```sh
php artisan config:cache
```
