# Appendix A - Constants Reference [![Edit in GitHub](https://img.shields.io/badge/Edit_in_GitHub--gray.svg?style=social)](https://github.com/wp-core-bootstrap/documentation/edit/master/a-constants-reference.md)

[PHP Constants](http://php.net/manual/en/language.constants.php) used throughout WordPress Core.

* **`ABSPATH`**

	_Set in_: `wp-load.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22ABSPATH%22+filename%3Awp-load.php), `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22ABSPATH%22+filename%3Awp-config-sample.php)

	_Default value_: `dirname( __FILE__ )`

	_Description_: Stores the absolute path to the WordPress root folder.

* **`ADMIN_COOKIE_PATH`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22ADMIN_COOKIE_PATH%22+filename%3Adefault-constants.php)

	_Default Value_: `SITECOOKIEPATH . 'wp-admin'`

	_Description_: Admin backend path to store the cookie under.

* **`AUTH_COOKIE`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22AUTH_COOKIE%22+filename%3Adefault-constants.php)

	_Default Value_: `'wordpress_' . COOKIEHASH`

	_Description_: Name of the cookie storing whether the user is authenticated over HTTP.

* **`AUTH_KEY`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22AUTH_KEY%22+filename%3Awp-config-sample.php)

	_Description_: Authentication key used to generate an authentication cookie on HTTP connections.

* **`AUTH_SALT`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22AUTH_SALT%22+filename%3Awp-config-sample.php)

	_Description_: Salt used on the authentication key for generating an authentication cookie on HTTP connections.

* **`AUTOSAVE_INTERVAL`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22AUTOSAVE_INTERVAL%22+filename%3Adefault-constants.php)

	_Default Value_: `60`

	_Description_: Interval between automatic saves in seconds.

* **`COOKIE_DOMAIN`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22COOKIE_DOMAIN%22+filename%3Adefault-constants.php)

	_Default Value_: `false`

	_Description_: Domain store the cookie under.

* **`COOKIE_HASH`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22COOKIE_HASH%22+filename%3Adefault-constants.php)

	_Default Value_: `md5( $siteurl )`

	_Description_: Used to guarantee unique cookie hashes.

* **`COOKIEPATH`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22COOKIEPATH%22+filename%3Adefault-constants.php)

	_Default Value_: `preg_replace('|https?://[^/]+|i', '', get_option('home') . '/' )`

	_Description_: Home path to store the cookie under.

* **`DB_CHARSET`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22DB_CHARSET%22+filename%3Awp-config-sample.php)

	_Default value_: `'utf8'`

	_Description_: Database Charset to use in creating database tables.

* **`DB_COLLATE`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22DB_COLLATE%22+filename%3Awp-config-sample.php)

	_Default value_: `''`

	_Description_: The Database Collate type.

* **`DB_HOST`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22DB_HOST%22+filename%3Awp-config-sample.php)

	_Default value_: `'localhost'`

	_Description_: MySQL hostname.

* **`DB_NAME`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22DB_NAME%22+filename%3Awp-config-sample.php)

	_Description_: The name of the database for WordPress.

* **`DB_PASSWORD`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22DB_PASSWORD%22+filename%3Awp-config-sample.php)

	_Description_: MySQL database password.

* **`DB_USER`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22DB_USER%22+filename%3Awp-config-sample.php)

	_Description_: MySQL database username.

* **`DAY_IN_SECONDS`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22DAY_IN_SECONDS%22+filename%3Adefault-constants.php)

	_Value_: `24 * HOUR_IN_SECONDS`

	_Description_: Constant for expressing human-readable intervals in their respective number of seconds.

* **`EMPTY_TRASH_DAYS`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22EMPTY_TRASH_DAYS%22+filename%3Adefault-constants.php)

	_Default Value_: `30`

	_Description_: Interval between automatic removal of trashed elements in days.

* **`FORCE_SSL_ADMIN`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22FORCE_SSL_ADMIN%22+filename%3Adefault-constants.php)

	_Default Value_: `true|false` based on `get_option('siteurl')` scheme

	_Description_: Whether to force the admin backend to always require a secure connection.

* **`FORCE_SSL_LOGIN`**

	_Description_: Whether to force logged-in users to always require a secure connection.

* **`GB_IN_BYTES`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22GB_IN_BYTES%22+filename%3Adefault-constants.php)

	_Value_: `1024 * MB_IN_BYTES`

	_Description_: Constant for expressing human-readable data-sizes in their respective number of bytes.

* **`HOUR_IN_SECONDS`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22HOUR_IN_SECONDS%22+filename%3Adefault-constants.php)

	_Value_: `60 * MINUTE_IN_SECONDS`

	_Description_: Constant for expressing human-readable intervals in their respective number of seconds.

* **`KB_IN_BYTES`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22KB_IN_BYTES%22+filename%3Adefault-constants.php)

	_Value_: `1024`

	_Description_: Constant for expressing human-readable data-sizes in their respective number of bytes.

* **`LOGGED_IN_COOKIE`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22LOGGED_IN_COOKIE%22+filename%3Adefault-constants.php)

	_Default Value_: `'wordpress_logged_in_' . COOKIEHASH`

	_Description_: Name of the cookie storing whether the user is logged in.

* **`LOGGED_IN_KEY`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22LOGGED_IN_KEY%22+filename%3Awp-config-sample.php)

	_Description_: Key used to generate the logged-in cookie.

* **`LOGGED_IN_SALT`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22LOGGED_IN_SALT%22+filename%3Awp-config-sample.php)

	_Description_: Salt used on the key for generating the logged-in cookie.

* **`MB_IN_BYTES`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22MB_IN_BYTES%22+filename%3Adefault-constants.php)

	_Value_: `1024 * KB_IN_BYTES`

	_Description_: Constant for expressing human-readable data-sizes in their respective number of bytes.

* **`MEDIA_TRASH`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22MEDIA_TRASH%22+filename%3Adefault-constants.php)

	_Default Value_: `false`

	_Description_: Use trashcan when deleting media files.

* **`MINUTE_IN_SECONDS`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22MINUTE_IN_SECONDS%22+filename%3Adefault-constants.php)

	_Value_: `60`

	_Description_: Constant for expressing human-readable intervals in their respective number of seconds.

* **`MONTH_IN_SECONDS`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22MONTH_IN_SECONDS%22+filename%3Adefault-constants.php)

	_Value_: `30 * DAY_IN_SECONDS`

	_Description_: Constant for expressing human-readable intervals in their respective number of seconds.

* **`MUPLUGINDIR`** (deprecated)

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22MUPLUGINDIR%22+filename%3Adefault-constants.php)

	_Default Value_: `wp-content/mu-plugins`

	_Description_: Path to the mu-plugins folder.

* **`NONCE_KEY`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22NONCE_KEY%22+filename%3Awp-config-sample.php)

	_Description_: Key used to generate a nonce.

* **`NONCE_SALT`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22NONCE_SALT%22+filename%3Awp-config-sample.php)

	_Description_: Salt used on the key for generating a nonce.

* **`PASS_COOKIE`** (deprecated)

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22PASS_COOKIE%22+filename%3Adefault-constants.php)

	_Default Value_: `'wordpresspass_' . COOKIEHASH`

	_Description_: Name of the cookie storing the user's double-hashed password.

* **`PLUGINDIR`** (deprecated)

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22PLUGINDIR%22+filename%3Adefault-constants.php)

	_Default Value_: `wp-content/plugins`

	_Description_: Path to the plugins folder.

* **`PLUGINS_COOKIE_PATH`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22PLUGINS_COOKIE_PATH%22+filename%3Adefault-constants.php)

	_Default Value_: `preg_replace('|https?://[^/]+|i', '', WP_PLUGIN_URL )`

	_Description_: Plugins folder path to store the cookie under.

* **`SCRIPT_DEBUG`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22SCRIPT_DEBUG%22+filename%3Adefault-constants.php)

	_Default Value_: `false`

	_Description_: Load of non-minified, non-concatenated scripts and stylesheets.

* **`SECURE_AUTH_COOKIE`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22AUTH_COOKIE%22+filename%3Adefault-constants.php)

	_Default Value_: `'wordpress_sec_' . COOKIEHASH`

	_Description_: Name of the cookie storing whether the user is authenticated over HTTPS.

* **`SECURE_AUTH_KEY`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22SECURE_AUTH_KEY%22+filename%3Awp-config-sample.php)

	_Description_: Authentication key used to generate an authentication cookie on HTTPS connections.

* **`SECURE_AUTH_SALT`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22SECURE_AUTH_SALT%22+filename%3Awp-config-sample.php)

	_Description_: Salt used on the authentication key for generating an authentication cookie on HTTPS connections.

* **`SHORTINIT`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22SHORTINIT%22+filename%3Adefault-constants.php)

	_Default Value_: `false`

	_Description_: Short-circuit the WordPress loading process to run a minimal system.

* **`SITECOOKIEPATH`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22SITECOOKIEPATH%22+filename%3Adefault-constants.php)

	_Default Value_: `preg_replace('|https?://[^/]+|i', '', get_option('siteurl') . '/' )`

	_Description_: Site URL path to store the cookie under.

* **`STYLESHEETPATH`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22STYLESHEETPATH%22+filename%3Adefault-constants.php)

	_Default Value_: `get_stylesheet_directory()`

	_Description_: Filesystem path to the current active template stylesheet directory.

* **`TB_IN_BYTES`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22TB_IN_BYTES%22+filename%3Adefault-constants.php)

	_Value_: `1024 * GB_IN_BYTES`

	_Description_: Constant for expressing human-readable data-sizes in their respective number of bytes.

* **`TEMPLATEPATH`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22TEMPLATEPATH%22+filename%3Adefault-constants.php)

	_Default Value_: `get_template_directory()`

	_Description_: Filesystem path to the current active template directory.

* **`TEST_COOKIE`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22TEST_COOKIE%22+filename%3Adefault-constants.php)

	_Default Value_: `'wordpress_test_cookie_' . COOKIEHASH`

	_Description_: Name of the cookie used to test whether the browser supports cookies.

* **`USER_COOKIE`** (deprecated)

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22USER_COOKIE%22+filename%3Adefault-constants.php)

	_Default Value_: `'wordpressuser_' . COOKIEHASH`

	_Description_: Name of the cookie storing the user name.

* **`WEEK_IN_SECONDS`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WEEK_IN_SECONDS%22+filename%3Adefault-constants.php)

	_Value_: `7 * DAY_IN_SECONDS`

	_Description_: Constant for expressing human-readable intervals in their respective number of seconds.

* **`WP_CACHE`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_CACHE%22+filename%3Adefault-constants.php)

	_Default Value_: `false`

	_Description_: Cache generated WordPress output.

* **`WP_CONTENT_DIR`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_CONTENT_DIR%22+filename%3Adefault-constants.php)

	_Default Value_: `ABSPATH . 'wp-content'`

	_Description_: Path to the content folder.

* **`WP_CONTENT_URL`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_CONTENT_URL%22+filename%3Adefault-constants.php)

	_Default Value_: `get_option('siteurl') . '/wp-content'`

	_Description_: URL location of the content folder.

* **`WP_CRON_LOCK_TIMEOUT`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_CRON_LOCK_TIMEOUT%22+filename%3Adefault-constants.php)

	_Default Value_: `60`

	_Description_: Timeout for the lock file for cron scripts in seconds.

* **`WP_DEBUG`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_DEBUG%22+filename%3Awp-config-sample.php), `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_DEBUG%22+filename%3Adefault-constants.php)

	_Default value_: `false`

	_Description_: WordPress debugging mode.

* **`WP_DEBUG_DISPLAY`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_DEBUG_DISPLAY%22+filename%3Adefault-constants.php)

	_Default value_: `true`

	_Description_: Display PHP errors.

* **`WP_DEBUG_LOG`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_DEBUG_LOG%22+filename%3Adefault-constants.php)

	_Default value_: `false`

	_Description_: Log PHP errors to `WP_CONTENT_DIR/debug.log`.

* **`WP_DEFAULT_THEME`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_DEFAULT_THEME%22+filename%3Adefault-constants.php)

	_Default Value_: `'twentyseventeen'` (as of WordPress 4.8)

	_Description_: Default theme to pick if none was set.

* **`WP_FEATURE_BETTER_PASSWORDS`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_FEATURE_BETTER_PASSWORDS%22+filename%3Adefault-constants.php)

	_Default Value_: `true`

	_Description_: Constant for "Better Passwords"-feature added to WordPress that should short-circuit its plugin implementation.

* **`WP_MAX_MEMORY_LIMIT`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_MAX_MEMORY_LIMIT%22+filename%3Adefault-constants.php)

	_Default Value_: `256M`

	_Description_: PHP process maximum memory limit.

* **`WP_MEMORY_LIMIT`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_MEMORY_LIMIT%22+filename%3Adefault-constants.php)

	_Default Value_: `40M` (`64M` on multisite)

	_Description_: PHP process default memory limit.

* **`WP_PLUGIN_DIR`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_PLUGIN_DIR%22+filename%3Adefault-constants.php)

	_Default Value_: `WP_CONTENT_DIR . '/plugins'`

	_Description_: Path to the plugins folder.

* **`WP_PLUGIN_URL`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_PLUGIN_URL%22+filename%3Adefault-constants.php)

	_Default Value_: `WP_CONTENT_URL . '/plugins'`

	_Description_: URL location of the plugins folder.

* **`WP_POST_REVISIONS`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_POST_REVISIONS%22+filename%3Adefault-constants.php)

	_Default Value_: `true`

	_Description_: Whether to store multiple versioned revisions for edited posts.

* **`WP_USE_THEMES`**

	_Set in_: `index.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_USE_THEMES%22+filename%3Aindex.php)

	_Default value_: `true`

	_Description_: Tells WordPress to load the WordPress theme and output it.

* **`WPINC`**

	_Set in_: `wp-load.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WPINC%22+filename%3Awp-load.php)

	_Default value_: `'wp-includes'`

	_Description_: Directory name of the folder that contains the includes.

* **`WPMU_PLUGIN_DIR`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WPMU_PLUGIN_DIR%22+filename%3Adefault-constants.php)

	_Default Value_: `WP_CONTENT_DIR . '/mu-plugins'`

	_Description_: Path to the mu-plugins folder.

* **`WPMU_PLUGIN_URL`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WPMU_PLUGIN_URL%22+filename%3Adefault-constants.php)

	_Default Value_: `WP_CONTENT_URL . '/mu-plugins'`

	_Description_: URL location of the mu-plugins folder.

* **`YEAR_IN_SECONDS`**

	_Set in_: `default-constants.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22YEAR_IN_SECONDS%22+filename%3Adefault-constants.php)

	_Value_: `365 * DAY_IN_SECONDS`

	_Description_: Constant for expressing human-readable intervals in their respective number of seconds.
