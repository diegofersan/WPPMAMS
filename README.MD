### After docker-compose up

##### Folder permissions
```language
sudo chown -R $USER (folder)
```

##### wp-config.php
```language
/**
* Enable directly updates and downloads
*/
define('FS_METHOD', 'direct');

/**
* Enable to show errors
*/
define( 'WP_DEBUG', true ); 
define( 'WP_DEBUG_LOG', true );
define( 'WP_DEBUG_DISPLAY', true );
@ini_set( 'display_errors', 0 );
define( 'SCRIPT_DEBUG', true );
```