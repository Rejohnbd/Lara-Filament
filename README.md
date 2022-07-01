
## About Laravel

Laravel is a web application framework 9 install with filament.php

- [Filament php](https://filamentphp.com/).
- composer require filament/filament:"^2.0"
- php artisan migrate
- php artisan make:filament-user
- php artisan make:model Category -m
- php artisan make:model Post -m 
- php artisan make:model Tag -m
- php artisan make:migration CreatePostTagTable
- php artisan migrate
- php artisan make:filament-resource CategoryResource
- php artisan make:filament-resource PostResource
- php artisan make:filament-resource TagResource
- [Filament Spatie Media Library](https://filamentphp.com/plugins/spatie-media-library)
- composer require filament/spatie-laravel-media-library-plugin:"^2.0"
- php artisan vendor:publish --provider="Spatie\MediaLibrary\MediaLibraryServiceProvider" --tag="migrations"
- php artisan migrate
- [documentation of spatie media library](https://spatie.be/docs/laravel-medialibrary/v10/basic-usage/preparing-your-model)

