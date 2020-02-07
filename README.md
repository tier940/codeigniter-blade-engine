# CodeIgniter Blade Engine

This repository is a library that allows You to use The Blade, the template engine used by Laravel, with Codeigniter.

## Requirements

* PHP 5.3.7 or later
* `composer` command (See [Composer Installation](https://getcomposer.org/doc/00-intro.md))
* Codeigniter3

## How to Use

### Install CodeIgniter Blade Engine

Install the following in your Codeigniter.

`composer require xiaoler/blade`

`composer require-dev symfony/debug`

Place libraries/Blade.php in your Codeigniter libraries.

Changes `application/config/autoload.php`

~~~
$autoload['libraries'] = '';
↓
$autoload['libraries'] = array('blade');
~~~

You can use it by calling the following in the Controller.

~~~
$this->load->view('*.php');
↓
$this->blade->view('*.blade.php');
~~~

Documentation: [https://readouble.com/laravel/5.4/ja/blade.html](https://readouble.com/laravel/5.4/ja/blade.html)

Thanks for Laravel and it authors. That is a great project.
