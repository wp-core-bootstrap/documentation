# Appendix C - Pluggable Functionality Reference [![Edit in GitHub](https://img.shields.io/badge/Edit_in_GitHub--gray.svg?style=social)](https://github.com/wp-core-bootstrap/documentation/edit/master/c-pluggable-functionality-reference.md)

## Drop-ins (pluggable files)

These files can be dropped into `WP_CONTENT_DIR` to replace the provided default implementation.

 * **`advanced-cache.php`** - Advanced caching plugin (only when `WP_CACHE=true`)
 * **`blog-deleted.php`** - Custom site deleted message
 * **`blog-inactive.php`** - Custom site inactive message
 * **`blog-suspended.php`** - Custom site suspended message
 * **`db.php`** - Custom database class
 * **`db-error.php`** - Custom database error message
 * **`install.php`** - Custom install script
 * **`maintenance.php`** - Custom maintenance message
 * **`object-cache.php`** - External object cache
 * **`sunrise.php`** - Executed before Multisite is loaded (only when `SUNRISE=true`)

## Pluggable functions

These are located in `WPINC\pluggable.php`. If one of these is already declared, the default declaration is skipped.

 * **`_wp_sanitize_utf8_in_redirect`** - Performs a safe (local) redirect, using wp_redirect() [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+_wp_sanitize_utf8_in_redirect%22+filename%3Apluggable.php)
 * **`auth_redirect`** - Checks if a user is logged in, if not it redirects them to the login page [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+auth_redirect%22+filename%3Apluggable.php)
 * **`cache_users`** - Retrieve info for user lists to prevent multiple queries by get_userdata() [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+cache_users%22+filename%3Apluggable.php)
 * **`check_admin_referer`** - Makes sure that a user was referred from another admin page [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+check_admin_referer%22+filename%3Apluggable.php)
 * **`check_ajax_referer`** - Verifies the Ajax request to prevent processing requests external of the blog [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+check_ajax_referer%22+filename%3Apluggable.php)
 * **`get_avatar`** - Retrieve the avatar &lt;img&gt; tag for a user [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+get_avatar%22+filename%3Apluggable.php)
 * **`get_user_by`** - Retrieve user info by a given field [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+get_user_by%22+filename%3Apluggable.php)
 * **`get_userdata`** - Retrieve user info by user ID [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+get_userdata%22+filename%3Apluggable.php)
 * **`is_user_logged_in`** - Checks if the current visitor is a logged in user [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+is_user_logged_in%22+filename%3Apluggable.php)
 * **`wp_authenticate`** - Authenticate a user, confirming the login credentials are valid [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_authenticate%22+filename%3Apluggable.php)
 * **`wp_check_password`** - Checks the plaintext password against the encrypted password [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_check_password%22+filename%3Apluggable.php)
 * **`wp_clear_auth_cookie`** - Removes all of the cookies associated with authentication [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_clear_auth_cookie%22+filename%3Apluggable.php)
 * **`wp_create_nonce`** - Creates a cryptographic token tied to a specific action, user, user session and window of time [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_create_nonce%22+filename%3Apluggable.php)
 * **`wp_generate_auth_cookie`** - Generate authentication cookie contents [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_generate_auth_cookie%22+filename%3Apluggable.php)
 * **`wp_generate_password`** - Generates a random password drawn from the defined set of characters [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_generate_password%22+filename%3Apluggable.php)
 * **`wp_get_current_user`** - Retrieve the current user object [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_get_current_user%22+filename%3Apluggable.php)
 * **`wp_hash_password`** - Create a hash (encrypt) of a plain text password [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_hash_password%22+filename%3Apluggable.php)
 * **`wp_hash`** - Get hash of given string [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_hash%22+filename%3Apluggable.php)
 * **`wp_logout`** - Log the current user out [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_logout%22+filename%3Apluggable.php)
 * **`wp_mail`** - Send mail, similar to PHP's mail [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_mail%22+filename%3Apluggable.php)
 * **`wp_new_user_notification`** - Email login credentials to a newly-registered user [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_new_user_notification%22+filename%3Apluggable.php)
 * **`wp_nonce_tick`** - Get the time-dependent variable for nonce creation [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_nonce_tick%22+filename%3Apluggable.php)
 * **`wp_notify_moderator`** - Notifies the moderatorabout a new comment that is awaiting approval [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_notify_moderator%22+filename%3Apluggable.php)
 * **`wp_notify_postauthor`** - Notify an author (and/or others) of a comment/trackback/pingback on a post [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_notify_postauthor%22+filename%3Apluggable.php)
 * **`wp_parse_auth_cookie`** - Parse a cookie into its components [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_parse_auth_cookie%22+filename%3Apluggable.php)
 * **`wp_password_change_notification`** - Notify the blog admin of a user changing password, normally via email [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_password_change_notification%22+filename%3Apluggable.php)
 * **`wp_rand`** - Generates a random number [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_rand%22+filename%3Apluggable.php)
 * **`wp_redirect`** - Redirects to another page [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_redirect%22+filename%3Apluggable.php)
 * **`wp_safe_redirect`** - Performs a safe (local) redirect, using wp_redirect() [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_safe_redirect%22+filename%3Apluggable.php)
 * **`wp_salt`** - Get salt to add to hashes [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_salt%22+filename%3Apluggable.php)
 * **`wp_sanitize_redirect`** - Sanitizes a URL for use in a redirect [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_sanitize_redirect%22+filename%3Apluggable.php)
 * **`wp_set_auth_cookie`** - Log in a user by setting authentication cookies [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_set_auth_cookie%22+filename%3Apluggable.php)
 * **`wp_set_current_user`** - Change the current user by ID or name [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_set_current_user%22+filename%3Apluggable.php)
 * **`wp_set_password`** - Updates the user's password with a new encrypted one [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_set_password%22+filename%3Apluggable.php)
 * **`wp_text_diff`** - Display a human readable difference between two strings [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_text_diff%22+filename%3Apluggable.php)
 * **`wp_validate_auth_cookie`** - Validates authentication cookie [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_validate_auth_cookie%22+filename%3Apluggable.php)
 * **`wp_validate_redirect`** - Validates a URL for use in a redirect [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_validate_redirect%22+filename%3Apluggable.php)
 * **`wp_verify_nonce`** - Verify that correct nonce was used with time limit [:mag:](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=%22function+wp_verify_nonce%22+filename%3Apluggable.php)
