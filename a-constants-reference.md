# Appendix A - Constants Reference

[PHP Constants](http://php.net/manual/en/language.constants.php) used throughout WordPress Core.

* **`ABSPATH`**

	_Set in_: `wp-load.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22ABSPATH%22+filename%3Awp-load.php), `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22ABSPATH%22+filename%3Awp-config-sample.php)

	_Default value_: `dirname( __FILE__ )`

	_Description_: Stores the absolute path to the WordPress root folder.

* **`AUTH_KEY`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22AUTH_KEY%22+filename%3Awp-config-sample.php)

	_Description_: Authentication key used to generate an authentication cookie on HTTP connections.

* **`AUTH_SALT`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22AUTH_SALT%22+filename%3Awp-config-sample.php)

	_Description_: Salt used on the authentication key for generating an authentication cookie on HTTP connections.

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

* **`LOGGED_IN_KEY`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22LOGGED_IN_KEY%22+filename%3Awp-config-sample.php)

	_Description_: Key used to generate the logged-in cookie.

* **`LOGGED_IN_SALT`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22LOGGED_IN_SALT%22+filename%3Awp-config-sample.php)

	_Description_: Salt used on the key for generating the logged-in cookie.

* **`NONCE_KEY`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22NONCE_KEY%22+filename%3Awp-config-sample.php)

	_Description_: Key used to generate a nonce.

* **`NONCE_SALT`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22NONCE_SALT%22+filename%3Awp-config-sample.php)

	_Description_: Salt used on the key for generating a nonce.

* **`SECURE_AUTH_KEY`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22SECURE_AUTH_KEY%22+filename%3Awp-config-sample.php)

	_Description_: Authentication key used to generate an authentication cookie on HTTPS connections.

* **`SECURE_AUTH_SALT`**

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22SECURE_AUTH_SALT%22+filename%3Awp-config-sample.php)

	_Description_: Salt used on the authentication key for generating an authentication cookie on HTTPS connections.

* **`WP_DEBUG`**

	_Set in_: `index.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_DEBUG%22+filename%3Aindex.php)

	_Default value_: `false`

	_Description_: WordPress debugging mode.

* **`WP_USE_THEMES`**

	_Set in_: `index.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WP_USE_THEMES%22+filename%3Aindex.php)

	_Default value_: `true`

	_Description_: Tells WordPress to load the WordPress theme and output it.

* **`WPINC`**

	_Set in_: `wp-load.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22WPINC%22+filename%3Awp-load.php)

	_Default value_: `wp-includes`

	_Description_: Directory name of the folder that contains the includes.
