## Installation

```git clone git@github.com:agencetwogether/filament-issue-richeditor.git```

```cd filament-issue-richeditor```

```composer install```

```cp .env.example .env```

```php artisan key:generate```

```php artisan migrate --seed```

```php artisan storage:link```

```php artisan serve```

Go to ```http://127.0.0.1:8000```, credentials are prefilled, then in Post form, upload and image and try to align (left, center, right) image with corresponding buttons.

With ```->resizableImages()``` no effect, whereas without works
