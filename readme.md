### FEDC

## install

composer create-project laravel/laravel FEDC 5.0.* --prefer-dist

php artisan fresh

##php artisan app:name FEDC

php artisan help migrate

php artisan --version


#####################################################################################################################
#####################################################################################################################

composer require "pingpong/sky:~2.0"

composer require pingpong/admin ^2.0.*

php artisan vendor:publish --provider="Pingpong\Admin\AdminServiceProvider"

        'Pingpong\Admin\Providers\SupportServiceProvider',
        'Pingpong\Admin\AdminServiceProvider',



#####################################################################################################################
#####################################################################################################################

###############################################################################################################
## Addon


php artisan vendor:publish



#####################################################################################################################


php artisan migrate --path="vendor/jacapo/laravel-authentication-acl/database/migrations"

php artisan authentication:install

#####################################################################################################################

composer require pingpong/admin ^2.0.*

php artisan vendor:publish --provider="Pingpong\Admin\AdminServiceProvider"

        'Pingpong\Admin\Providers\SupportServiceProvider',
        'Pingpong\Admin\AdminServiceProvider',

#####################################################################################################################
#####################################################################################################################



[![Build Status](https://travis-ci.org/laravel/framework.svg)](https://travis-ci.org/laravel/framework)
[![Total Downloads](https://poser.pugx.org/laravel/framework/downloads.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Stable Version](https://poser.pugx.org/laravel/framework/v/stable.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Unstable Version](https://poser.pugx.org/laravel/framework/v/unstable.svg)](https://packagist.org/packages/laravel/framework)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as authentication, routing, sessions, queueing, and caching.

Laravel is accessible, yet powerful, providing powerful tools needed for large, robust applications. A superb inversion of control container, expressive migration system, and tightly integrated unit testing support give you the tools you need to build any application with which you are tasked.

## Official Documentation

Documentation for the framework can be found on the [Laravel website](http://laravel.com/docs).

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](http://laravel.com/docs/contributions).

### License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
