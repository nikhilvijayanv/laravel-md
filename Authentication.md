# Authentication

https://laravel.com/docs/11.x/authentication

At its core, Laravel's authentication facilities are made up of `"guards"` and `"providers"`. Guards define how users are authenticated for each request. For example, Laravel ships with a session guard which maintains state using session storage and cookies.

Providers define how users are retrieved from your persistent storage. Laravel ships with support for retrieving users using Eloquent and the database query builder. However, you are free to define additional providers as needed for your application.

Your application's authentication configuration file is located at config/auth.php. This file contains several well-documented options for tweaking the behavior of Laravel's authentication services.

>Guards and providers should not be confused with "roles" and "permissions". To learn more about authorizing user actions via permissions, please refer to the authorization documentation.

