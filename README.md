# Sentry Laravel Example

This shows how to use Sentry in Laravel to capture errors/exceptions

# Setup
0. Make sure mysql DB is created (as per .env)
1. `$ compose install`
2. Set your DSN key + projectID in `.env`
3. Run server. `$ php artisan serve`
4. Go to http://localhost:8000 to trigger error. You should see issue/event within Sentry project

# Resources:
- https://sentry.io/for/laravel/
- https://docs.sentry.io/clients/php/
