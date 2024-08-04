install plugin Redis Object Cache

edit wp-config.php

```
// Redis Configuration
define('WP_REDIS_HOST', 'redis'); // Nama layanan Redis
define('WP_REDIS_PORT', 6379);
define('WP_REDIS_PASSWORD', 'myredispassword'); // Password Redis
define('WP_REDIS_DATABASE', 0);
```
