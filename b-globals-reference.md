# Appendix B - Globals Reference [![Edit in GitHub](https://img.shields.io/badge/Edit_in_GitHub--gray.svg?style=social)](https://github.com/wp-core-bootstrap/documentation/edit/master/b-globals-reference.md)

[PHP global variables](http://php.net/manual/en/language.variables.scope.php#language.variables.scope.global) used throughout WordPress Core.

* **`$blog_id`**

	_Type_: integer

	_Set in_: `wp-settings.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22$blog_id%22+filename%3Awp-settings.php)

	_Default value_: `1`

	_Description_: Current site ID.

* **`$required_mysql_version`**

	_Type_: string

	_Set in_: `wp-settings.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22$required_mysql_version%22+filename%3Awp-settings.php)

	_Description_: Holds the required MySQL version.

* **`$required_php_version`**

	_Type_: string

	_Set in_: `wp-settings.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22$required_php_version%22+filename%3Awp-settings.php)

	_Description_: Holds the required PHP version.

* **`$tinymce_version`**

	_Type_: string

	_Set in_: `wp-settings.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22$tinymce_version%22+filename%3Awp-settings.php)

	_Description_: Holds the TinyMCE version.

* **`$wp_db_version`**

	_Type_: string

	_Set in_: `wp-settings.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22$wp_db_version%22+filename%3Awp-settings.php)

	_Description_: Holds the WordPress DB revision, increments when changes are made to the WordPress DB schema.

* **`$wp_local_package`**

	_Type_: string

	_Set in_: `wp-settings.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22$wp_local_package%22+filename%3Awp-settings.php)

* **`$table_prefix`**

	_Type_: string

	_Set in_: `wp-config-sample.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22$table_prefix%22+filename%3Awp-config-sample.php)

	_Default value_: `'wp_'`

	_Description_: WordPress database table prefix. Must only contain numbers, letters, and underscores.

* **`$wp_version`**

	_Type_: string

	_Set in_: `wp-settings.php` [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22$wp_version%22+filename%3Awp-settings.php)

	_Description_: The WordPress version string.
