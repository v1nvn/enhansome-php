# Awesome PHP [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 436,352 | 🐛 69 | 📅 2026-01-28 with stars

A curated list of awesome PHP libraries, resources, and useful tools.

## Contributing and Collaborating

Please see [CONTRIBUTING](https://github.com/ziadoz/awesome-php/blob/master/CONTRIBUTING.md) ⭐ 32,363 | 🐛 68 | 📅 2026-01-17, [CODE-OF-CONDUCT](https://github.com/ziadoz/awesome-php/blob/master/CODE-OF-CONDUCT.md) ⭐ 32,363 | 🐛 68 | 📅 2026-01-17 and [COLLABORATING](https://github.com/ziadoz/awesome-php/blob/master/COLLABORATING.md) ⭐ 32,363 | 🐛 68 | 📅 2026-01-17 for details.

## Table of Contents

* [Awesome PHP](#awesome-php)
  * [Composer Repositories](#composer-repositories)
  * [Dependency Management](#dependency-management)
  * [Dependency Management Extras](#dependency-management-extras)
  * [Frameworks](#frameworks)
  * [Framework Extras](#framework-extras)
  * [Content Management Systems](#content-management-systems-cms)
  * [Components](#components)
  * [Micro Frameworks](#micro-frameworks)
  * [Micro Framework Extras](#micro-framework-extras)
  * [Routers](#routers)
  * [Templating](#templating)
  * [Static Site Generators](#static-site-generators)
  * [HTTP](#http)
  * [Scraping](#scraping)
  * [Middlewares](#middlewares)
  * [URL](#url)
  * [Email](#email)
  * [Files](#Files)
  * [Streams](#streams)
  * [Dependency Injection](#dependency-injection)
  * [Imagery](#imagery)
  * [Testing](#testing)
  * [Continuous Integration](#continuous-integration)
  * [Documentation](#documentation)
  * [Security](#security)
  * [Passwords](#passwords)
  * [Code Analysis](#code-analysis)
  * [Code Quality](#code-quality)
  * [Static Analysis](#static-analysis)
  * [Architectural](#architectural)
  * [Debugging and Profiling](#debugging-and-profiling)
  * [Error Tracking and Monitoring Services](#error-tracking-and-monitoring-services)
  * [Build Tools](#build-tools)
  * [Task Runners](#task-runners)
  * [Navigation](#navigation)
  * [Asset Management](#asset-management)
  * [Geolocation](#geolocation)
  * [Date and Time](#date-and-time)
  * [Event](#event)
  * [Logging](#logging)
  * [E-commerce](#e-commerce)
  * [PDF](#pdf)
  * [Office](#office)
  * [Database](#database)
  * [Migrations](#migrations)
  * [NoSQL](#nosql)
  * [Queue](#queue)
  * [Search](#search)
  * [Command Line](#command-line)
  * [Authentication and Authorization](#authentication-and-authorization)
  * [Markup and CSS](#markup-and-css)
  * [JSON](#json)
  * [Strings](#strings)
  * [Numbers](#numbers)
  * [Filtering, Sanitizing and Validation](#filtering-sanitizing-and-validation)
  * [API](#api)
  * [Caching and Locking](#caching-and-locking)
  * [Data Structure and Storage](#data-structure-and-storage)
  * [Notifications](#notifications)
  * [Deployment](#deployment)
  * [Internationalisation and Localisation](#internationalisation-and-localisation)
  * [Serverless](#serverless)
  * [Configuration](#configuration)
  * [LLMs](#llms)
  * [Third Party APIs](#third-party-apis)
  * [Extensions](#extensions)
  * [Miscellaneous](#miscellaneous)
* [Software](#software)
  * [PHP Installation](#php-installation)
  * [Development Environment](#development-environment)
  * [Virtual Machines](#virtual-machines)
  * [Text Editors and IDEs](#text-editors-and-ides)
  * [Web Applications](#web-applications)
  * [Infrastructure](#infrastructure)
* [Resources](#resources)
  * [PHP Websites](#php-websites)
  * [PHP Books](#php-books)
  * [PHP Videos](#php-videos)
  * [PHP Conferences](#php-conferences)
  * [PHP Podcasts](#php-podcasts)
  * [PHP Newsletters](#php-newsletters)
  * [PHP Reading](#php-reading)
  * [PHP Internals Reading](#php-internals-reading)

### Composer Repositories

*Composer Repositories.*

* [Firegento](https://packages.firegento.com/) - Magento Module Composer Repository.
* [Packagist](https://packagist.org/) - The PHP Package Repository.
* [Packalyst](https://packalyst.com/) - The Laravel package repository.
* [Private Packagist](https://packagist.com/) - Composer package archive as a service for PHP.
* [WordPress Packagist](https://wpackagist.org/) - Manage your plugins with Composer.

### Dependency Management

*Libraries for dependency and package management.*

* [Pie](https://github.com/php/pie) ⭐ 1,722 | 🐛 12 | 🌐 PHP | 📅 2026-02-09 - The official PHP installer for extensions.
* [Pickle](https://github.com/FriendsOfPHP/pickle) ⭐ 1,655 | 🐛 38 | 🌐 PHP | 📅 2023-09-29 - A PHP extension installer.
* [Composer Installers](https://github.com/composer/installers) ⭐ 1,438 | 🐛 23 | 🌐 PHP | 📅 2026-01-01 - A  multi-framework Composer library installer.
* [Composer](https://getcomposer.org/) - A package and dependency manager.
* [Phive](https://phar.io/) - A PHAR manager.

### Dependency Management Extras

*Extras related to dependency management.*

* [Satis](https://github.com/composer/satis) ⭐ 3,250 | 🐛 105 | 🌐 PHP | 📅 2026-02-09 - A static Composer repository generator.
* [Composer Patches](https://github.com/cweagans/composer-patches) ⭐ 1,677 | 🐛 52 | 🌐 PHP | 📅 2026-01-30 - A plugin for Composer to apply patches.
* [Composer Unused](https://github.com/composer-unused/composer-unused) ⭐ 1,651 | 🐛 9 | 🌐 PHP | 📅 2026-02-06 - A CLI Tool to scan for unused composer packages.
* [Composer Normalize](https://github.com/ergebnis/composer-normalize) ⭐ 1,104 | 🐛 11 | 🌐 PHP | 📅 2026-02-10 - A plugin for normalizing `composer.json` files.
* [Composer Merge Plugin](https://github.com/wikimedia/composer-merge-plugin) ⭐ 991 | 🐛 72 | 🌐 PHP | 📅 2026-01-23 - A composer plugin to merge several `composer.json` files.
* [Composer Require Checker](https://github.com/maglnet/ComposerRequireChecker) ⭐ 982 | 🐛 43 | 🌐 PHP | 📅 2026-02-08 - CLI tool to analyze composer dependencies and verify that no unknown symbols are used in the sources of a package.
* [Tooly](https://github.com/tommy-muehle/tooly-composer-script) ⭐ 103 | 🐛 8 | 🌐 PHP | 📅 2024-01-10 - A library to manage PHAR files in a project using Composer.
* [Composed](https://github.com/joshdifabio/composed) ⭐ 52 | 🐛 2 | 🌐 PHP | 📅 2016-11-14 - A library to parse your project's Composer environment at runtime.
* [Composer Prefer Lowest Validator](https://github.com/dereuromark/composer-prefer-lowest) ⭐ 22 | 🐛 1 | 🌐 PHP | 📅 2025-11-22 - A plugin to check if minimum dependencies can be installed and tested.
* [Repman](https://repman.io) - A private PHP package repository manager and Packagist proxy.
* [Toran Proxy](https://toranproxy.com) - A Composer proxy for speed and reliability. (:warning: Toran Proxy is being phased out.)

### Frameworks

*Web development frameworks.*

* [CakePHP](https://cakephp.org/) - A rapid application development framework.
* [CodeIgniter](https://codeigniter.com/) - A powerful PHP framework with a very small footprint.
* [Laminas](https://getlaminas.org/) - A framework comprised of individual components (previously Zend Framework).
* [Laravel](https://laravel.com/) - A web application framework with expressive, elegant syntax.
* [Nette](https://nette.org) - A web framework comprised of mature components.
* [Phalcon](https://phalcon.io/en-us) - A framework implemented as a C extension.
* [Spiral](https://spiral.dev/) - A high-performance PHP/Go framework.
* [Symfony](https://symfony.com/) - A set of reusable components and a web framework.
* [Yii2](https://github.com/yiisoft/yii2/) ⭐ 14,322 | 🐛 526 | 🌐 PHP | 📅 2026-02-07 - A fast, secure, and efficient web framework.

### Framework Extras

*Extras related to web development frameworks.*

* [LaravelS](https://github.com/hhxsv5/laravel-s) ⭐ 3,887 | 🐛 71 | 🌐 PHP | 📅 2026-01-19 - An out-of-the-box adapter between Laravel/Lumen and Swoole.
* [CakePHP CRUD](https://github.com/friendsofcake/crud) ⭐ 376 | 🐛 11 | 🌐 PHP | 📅 2026-01-13 - A Rapid Application Development (RAD) plugin for CakePHP.
* [Filament PHP](https://filamentphp.com/) - A powerful open source UI framework for Laravel.
* [Livewire](https://livewire.laravel.com/) - Powerful, dynamic, front-end UIs without leaving PHP.

### Content Management Systems (CMS)

*Tools for managing digital content.*

* [WordPress](https://github.com/WordPress/WordPress) ⭐ 20,876 | 🐛 9 | 🌐 PHP | 📅 2026-02-09 - A blogging platform and CMS.
* [Grav](https://github.com/getgrav/grav) ⭐ 15,381 | 🐛 455 | 🌐 PHP | 📅 2026-02-05 - A modern flat-file CMS.
* [Magento](https://github.com/magento/magento2) ⭐ 12,042 | 🐛 1,977 | 🌐 PHP | 📅 2026-02-06 - The most popular e-commerce platform.
* [CraftCMS](https://github.com/craftcms/cms) ⭐ 3,529 | 🐛 520 | 🌐 PHP | 📅 2026-02-09 - A flexible, user-friendly CMS for creating custom digital experiences on the web and beyond.
* [OpenMage](https://github.com/OpenMage/magento-lts) ⭐ 916 | 🐛 238 | 🌐 PHP | 📅 2026-02-09 - Fork of EoL Magento 1 e-commerce platform.
* [Backdrop](https://backdropcms.org) - A CMS targeting small-to-medium-sized business and non-profits (a fork of Drupal).
* [Concrete5](https://www.concretecms.com/) - A CMS targeting users with a minimum of technical skills.
* [Drupal](https://new.drupal.org/home) - An enterprise level CMS.
* [Joomla](https://www.joomla.org/) - Another leading CMS.
* [Kirby](https://getkirby.com/) - A flat-file CMS that adapts to any project.
* [Moodle](https://moodle.org/) - An open-source learning platform.
* [Pico CMS](https://picocms.org/) - A stupidly simple, blazing fast, flat file CMS.
* [Statamic](https://statamic.com/) - Build beautiful, easy-to-manage websites.
* [Sulu](https://sulu.io/) - A user and developer friendly focused CMS and Platform based on the Symfony Framework.
* [TYPO3](https://typo3.org) - An enterprise level CMS.

### Components

*Standalone components from web development frameworks and development groups.*

* [Aura](https://auraphp.com/) - Independent components, fully decoupled from each other and from any framework.
* [CakePHP Plugins](https://plugins.cakephp.org/) - A directory of CakePHP plugins.
* [Laravel Components](https://github.com/illuminate) - The Laravel Framework components.
* [League of Extraordinary Packages](https://thephpleague.com/) - A PHP package development group.
* [Spatie Open Source](https://spatie.be/open-source) - A collection of open-source PHP and Laravel packages.
* [Symfony Packages](https://symfony.com/packages) - Decoupled libraries for PHP applications.
* [Laminas Components](https://docs.laminas.dev/components/) - The components that make the Laminas Framework.

### Micro Frameworks

*Micro frameworks and routers.*

* [Minicli](https://github.com/minicli/minicli) ⭐ 1,073 | 🐛 0 | 🌐 PHP | 📅 2025-12-22 - Minimalist, dependency-free framework for building CLI-centric PHP applications.
* [Silly](https://github.com/mnapoli/silly) ⭐ 930 | 🐛 4 | 🌐 PHP | 📅 2024-10-30 - A micro-framework for CLI applications.
* [Laravel Zero](https://laravel-zero.com) - A micro-framework for console applications.
* [Mezzio](https://getexpressive.org/) - A micro-framework by Laminas.
* [Slim](https://www.slimframework.com/) - Another simple micro framework.

### Micro Framework Extras

*Extras related to micro frameworks and routers.*

* [Slim Skeleton](https://github.com/slimphp/Slim-Skeleton) ⭐ 1,622 | 🐛 18 | 🌐 PHP | 📅 2025-04-01 - A skeleton for Slim.
* [Slim Twig View](https://github.com/slimphp/Slim-Views) ⚠️ Archived - Integrate Twig into Slim.
* [Slim PHP View](https://github.com/slimphp/PHP-View) ⭐ 273 | 🐛 0 | 🌐 PHP | 📅 2025-11-04 - A simple PHP renderer for Slim.

### Routers

*Libraries for handling application routing.*

* [Fast Route](https://github.com/nikic/FastRoute) ⭐ 5,260 | 🐛 27 | 🌐 PHP | 📅 2025-06-18 - A fast routing library.
* [Klein](https://github.com/klein/klein.php) ⭐ 2,659 | 🐛 97 | 🌐 PHP | 📅 2024-01-30 - A flexible router.
* [Pux](https://github.com/c9s/Pux) ⭐ 1,265 | 🐛 23 | 🌐 C | 📅 2023-03-28 - Another fast routing library.
* [Route](https://github.com/thephpleague/route) ⭐ 663 | 🐛 6 | 🌐 PHP | 📅 2025-03-27 - A routing library built on top of Fast Route.
* [Aura.Router](https://github.com/auraphp/Aura.Router) ⭐ 502 | 🐛 3 | 🌐 PHP | 📅 2025-05-02 - A full-featured routing library.

### Templating

*Libraries and tools for templating and lexing.*

* [Mustache](https://github.com/bobthecow/mustache.php) ⭐ 3,276 | 🐛 35 | 🌐 PHP | 📅 2025-06-28 - A PHP implementation of the Mustache template language.
* [MtHaml](https://github.com/arnaud-lb/MtHaml) ⭐ 359 | 🐛 28 | 🌐 PHP | 📅 2022-10-23 - A PHP implementation of the HAML template language.
* [Latte](https://latte.nette.org/) - The safest and truly intuitive templates for PHP.
* [PHPTAL](https://phptal.org/) - A PHP implementation of the [TAL](https://en.wikipedia.org/wiki/Template_Attribute_Language) templating language.
* [Plates](http://platesphp.com/) - A native PHP templating library.
* [Smarty](https://www.smarty.net/) - A template engine to complement PHP.
* [Twig](https://twig.symfony.com/) - A comprehensive templating language.

### Static Site Generators

*Tools for pre-processing content to generate web pages.*

* [Couscous](http://couscous.io) - Couscous turns Markdown documentation into beautiful websites. It's GitHub Pages on steroids.
* [Jigsaw](https://jigsaw.tighten.com/) - Simple static sites with Laravel's Blade.
* [Sculpin](https://sculpin.io) - A tool that converts Markdown and Twig into static HTML.

### HTTP

*Libraries for working with HTTP.*

* [Guzzle](https://github.com/guzzle/guzzle) ⭐ 23,452 | 🐛 36 | 🌐 PHP | 📅 2025-08-23 - A comprehensive HTTP client.
* [Requests](https://github.com/WordPress/Requests) ⭐ 3,584 | 🐛 124 | 🌐 PHP | 📅 2026-02-02 - A simple HTTP library.
* [Symfony HTTP Client](https://github.com/symfony/http-client) ⭐ 2,028 | 🐛 0 | 🌐 PHP | 📅 2026-02-09 - A component to fetch HTTP resources synchronously or asynchronously.
* [Buzz](https://github.com/kriswallsmith/Buzz) ⭐ 1,925 | 🐛 11 | 🌐 PHP | 📅 2025-07-07 - Another HTTP client.
* [Nyholm PSR-7](https://github.com/Nyholm/psr7) ⭐ 1,263 | 🐛 5 | 🌐 PHP | 📅 2025-11-28 - A super lightweight PSR-7 implementation. Very strict and very fast.
* [Laminas Diactoros](https://github.com/laminas/laminas-diactoros) ⭐ 537 | 🐛 29 | 🌐 PHP | 📅 2026-02-09 - PSR-7 HTTP Message implementation.
* [Retrofit](https://github.com/tebru/retrofit-php) ⭐ 156 | 🐛 5 | 🌐 PHP | 📅 2024-07-12 - A library to ease creation of REST API clients.
* [HTTPlug](http://httplug.io) - An HTTP client abstraction without binding to a specific implementation.
* [PHP VCR](https://php-vcr.github.io/) - A library for recording and replaying HTTP requests.

### Scraping

*Libraries for scraping websites and detecting crawlers.*

* [Symfony Panther](https://github.com/symfony/panther) ⭐ 3,061 | 🐛 209 | 🌐 PHP | 📅 2026-01-08 - A browser testing and web crawling library for PHP and Symfony.
* [Chrome PHP](https://github.com/chrome-php/chrome) ⭐ 2,609 | 🐛 9 | 🌐 PHP | 📅 2025-12-27 - Instrument headless Chrome/Chromium instances from PHP.
* [CrawlerDetect](https://github.com/JayBizzle/Crawler-Detect) ⭐ 2,325 | 🐛 7 | 🌐 PHP | 📅 2026-02-09 - A PHP class for detecting bots/crawlers/spiders via the user agent.
* [DiDOM](https://github.com/Imangazaliev/DiDOM) ⭐ 2,207 | 🐛 28 | 🌐 PHP | 📅 2026-01-28 - A super-fast HTML scrapper and parser.
* [Embed](https://github.com/php-embed/Embed) ⭐ 2,141 | 🐛 72 | 🌐 PHP | 📅 2025-11-21 - An information extractor from any web service or page.
* [PHP Spider](https://github.com/mvdbos/php-spider) ⭐ 1,344 | 🐛 1 | 🌐 PHP | 📅 2026-02-01 - A configurable and extensible PHP web spider.

### Middlewares

*Libraries for building application using middlewares.*

* [PSR-15 Middlewares](https://github.com/middlewares/psr15-middlewares) ⭐ 413 | 🐛 0 | 📅 2025-04-05 - Inspiring collection of handy middlewares.
* [Relay](https://github.com/relayphp/Relay.Relay) ⭐ 328 | 🐛 0 | 🌐 PHP | 📅 2024-10-22 - A PHP 5.5 PSR-7 middleware dispatcher.
* [Laminas Stratigility](https://github.com/laminas/laminas-stratigility) ⭐ 57 | 🐛 2 | 🌐 PHP | 📅 2026-02-09 - Middleware for PHP built on top of PSR-7.
* [Stack](https://github.com/stackphp) - A library of stackable middleware for Symfony.

### URL

*Libraries for parsing URLs.*

* [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) ⭐ 1,224 | 🐛 0 | 🌐 PHP | 📅 2026-01-30 - A domain suffix parser library.
* [Uri](https://github.com/thephpleague/uri) ⭐ 1,117 | 🐛 0 | 🌐 PHP | 📅 2026-01-20 - Another URL manipulation library.
* [Purl](https://github.com/jwage/purl) ⚠️ Archived - A URL manipulation library.
* [sabre/uri](https://github.com/sabre-io/uri) ⭐ 294 | 🐛 3 | 🌐 PHP | 📅 2026-01-14 - A functional URI manipulation library.

### Email

*Libraries for sending and parsing email.*

* [PHPMailer](https://github.com/PHPMailer/PHPMailer) ⭐ 22,001 | 🐛 40 | 🌐 PHP | 📅 2026-02-05 - Another mailer solution.
* [Mautic](https://github.com/mautic/mautic) ⭐ 9,182 | 🐛 266 | 🌐 PHP | 📅 2026-02-06 - Email marketing automation
* [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) ⭐ 5,840 | 🐛 32 | 🌐 PHP | 📅 2026-01-06 - A library to inline CSS in email templates.
* [PHP IMAP](https://github.com/barbushin/php-imap) ⭐ 1,696 | 🐛 81 | 🌐 PHP | 📅 2024-04-25 - A library to access mailboxes via POP3, IMAP and NNTP.
* [Symfony Mailer](https://github.com/symfony/mailer) ⭐ 1,589 | 🐛 0 | 🌐 PHP | 📅 2026-02-09 - A powerful library for creating and sending emails.
* [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) ⭐ 648 | 🐛 11 | 🌐 PHP | 📅 2022-09-20 - An email reply parser library.
* [Fetch](https://github.com/tedious/Fetch) ⭐ 505 | 🐛 78 | 🌐 PHP | 📅 2024-01-11 - An IMAP library.
* [Stampie](https://github.com/Stampie/Stampie) ⭐ 294 | 🐛 2 | 🌐 PHP | 📅 2022-06-27 - A library for email services such as [SendGrid](https://sendgrid.com/en-us), [PostMark](https://postmarkapp.com), [MailGun](https://www.mailgun.com/) and [MailChimp](https://mailchimp.com/features/transactional-email/).
* [Email Validator](https://github.com/nojacko/email-validator) ⚠️ Archived - A small email address validation library.
* [SwiftMailer](https://swiftmailer.symfony.com/docs/introduction.html) - A mailer solution.

### Files

*Libraries for file manipulation and MIME type detection.*

* [Flysystem](https://github.com/thephpleague/Flysystem) ⭐ 13,556 | 🐛 99 | 🌐 PHP | 📅 2026-01-23 - Abstraction for local and remote filesystems.
* [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) ⭐ 5,003 | 🐛 326 | 🌐 PHP | 📅 2026-01-19 - A wrapper for the [FFmpeg](https://www.ffmpeg.org/) video library.
* [CSV](https://github.com/thephpleague/csv) ⭐ 3,464 | 🐛 2 | 🌐 PHP | 📅 2026-02-05 - A CSV data manipulation library.
* [Gaufrette](https://github.com/KnpLabs/Gaufrette) ⭐ 2,475 | 🐛 87 | 🌐 PHP | 📅 2025-09-25 - A filesystem abstraction layer.
* [UnifiedArchive](https://github.com/wapmorgan/UnifiedArchive) ⭐ 279 | 🐛 7 | 🌐 PHP | 📅 2025-08-25 - A unified reader and writer of compressed archives.
* [Parquet](https://github.com/flow-php/parquet) ⭐ 40 | 🐛 0 | 🌐 PHP | 📅 2026-02-04 - PHP implementation of Parquet file format

### Streams

*Libraries for working with streams.*

* [ByteStream](https://amphp.org/byte-stream) - An asynchronous stream abstraction.
* [Streamer](https://github.com/fzaninotto/Streamer) ⚠️ Archived - A simple object-orientated stream wrapper library.

### Dependency Injection

*Libraries that implement the dependency injection design pattern.*

* [Symfony DI](https://github.com/symfony/dependency-injection) ⭐ 4,171 | 🐛 0 | 🌐 PHP | 📅 2026-02-09 - A dependency injection container component.
* [Pimple](https://github.com/silexphp/Pimple) ⭐ 2,667 | 🐛 0 | 🌐 PHP | 📅 2026-01-08 - A tiny dependency injection container.
* [Container](https://github.com/thephpleague/container) ⭐ 862 | 🐛 5 | 🌐 PHP | 📅 2025-06-12 - Another flexible dependency injection container.
* [Auryn](https://github.com/rdlowrey/Auryn) ⭐ 726 | 🐛 3 | 🌐 PHP | 📅 2025-03-02 - A recursive dependency injector.
* [Aura.Di](https://github.com/auraphp/Aura.Di) ⭐ 353 | 🐛 1 | 🌐 PHP | 📅 2024-09-17 - A serializable dependency injection container with constructor and setter injection, interface and trait awareness, configuration inheritance, and much more.
* [Acclimate](https://github.com/AcclimateContainer/acclimate-container) ⭐ 219 | 🐛 6 | 🌐 PHP | 📅 2023-08-18 - A common interface to dependency injection containers and service locators.
* [Disco](https://github.com/bitExpert/disco) ⭐ 139 | 🐛 11 | 🌐 PHP | 📅 2026-01-27 - A PSR-11 compatible, annotation-based dependency injection container.
* [PHP-DI](https://php-di.org/) - A dependency injection container that supports autowiring.

### Imagery

*Libraries for manipulating images.*

* [Intervention Image](https://github.com/Intervention/image) ⭐ 14,320 | 🐛 19 | 🌐 PHP | 📅 2026-02-08 - Another image manipulation library.
* [Glide](https://github.com/thephpleague/glide) ⭐ 2,629 | 🐛 42 | 🌐 PHP | 📅 2025-12-10 - An on-demand image manipulation library.
* [PHP QR Code](https://github.com/chillerlan/php-qrcode/) ⭐ 2,308 | 🐛 2 | 🌐 PHP | 📅 2025-11-24 - QR Code generator and reader.
* [Image Hash](https://github.com/jenssegers/imagehash) ⭐ 2,042 | 🐛 38 | 🌐 PHP | 📅 2025-09-17 - A library for generating perceptual image hashes.
* [Color Extractor](https://github.com/thephpleague/color-extractor) ⭐ 1,317 | 🐛 7 | 🌐 PHP | 📅 2023-11-02 - A library for extracting colours from images.
* [Image Optimizer](https://github.com/psliwa/image-optimizer) ⭐ 913 | 🐛 9 | 🌐 PHP | 📅 2023-11-20 - A library for optimizing images.
* [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) ⭐ 859 | 🐛 23 | 🌐 PHP | 📅 2023-06-13 - Another image manipulation library.
* [Imagine](https://imagine.readthedocs.io/en/latest/index.html) - An image manipulation library.

### Testing

*Libraries for testing codebases and generating test data.*

* [PHPUnit](https://github.com/sebastianbergmann/phpunit) ⭐ 19,994 | 🐛 125 | 🌐 PHP | 📅 2026-02-09 - A unit testing framework.
* [Mockery](https://github.com/mockery/mockery) ⭐ 10,734 | 🐛 115 | 🌐 PHP | 📅 2026-01-28 - A mock object library for testing.
* [Prophecy](https://github.com/phpspec/prophecy) ⭐ 8,504 | 🐛 102 | 🌐 PHP | 📅 2026-02-09 - A highly opinionated mocking framework.
* [Codeception](https://github.com/Codeception/Codeception) ⭐ 4,854 | 🐛 165 | 🌐 PHP | 📅 2026-01-14 - A full stack testing framework.
* [Faker](https://github.com/fakerphp/faker) ⭐ 3,929 | 🐛 21 | 🌐 PHP | 📅 2026-02-04 - A fake data generator library.
* [Alice](https://github.com/nelmio/alice) ⭐ 2,540 | 🐛 54 | 🌐 PHP | 📅 2026-02-10 - An expressive fixture generation library.
* [ParaTest](https://github.com/paratestphp/paratest) ⭐ 2,444 | 🐛 4 | 🌐 PHP | 📅 2026-02-09 - A parallel testing library for PHPUnit.
* [Infection](https://github.com/infection/infection) ⭐ 2,168 | 🐛 194 | 🌐 PHP | 📅 2026-02-09 - An AST-based PHP Mutation testing framework.
* [PHPSpec](https://github.com/phpspec/phpspec) ⭐ 1,900 | 🐛 137 | 🌐 PHP | 📅 2026-02-09 - A design by specification unit testing library.
* [Atoum](https://github.com/atoum/atoum) ⭐ 1,445 | 🐛 74 | 🌐 PHP | 📅 2025-10-30 - A simple testing library.
* [VFS Stream](https://github.com/bovigo/vfsStream) ⭐ 1,440 | 🐛 37 | 🌐 PHP | 📅 2024-08-29 - A virtual filesystem stream wrapper for testing.
* [Kahlan](https://github.com/kahlan/kahlan) ⭐ 1,148 | 🐛 7 | 🌐 PHP | 📅 2026-01-23 - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support.
* [Foundry](https://github.com/zenstruck/foundry) ⭐ 771 | 🐛 26 | 🌐 PHP | 📅 2026-02-09 - A fixture factory generation library for Doctrine.
* [PHP MySQL Engine](https://github.com/vimeo/php-mysql-engine) ⭐ 560 | 🐛 10 | 🌐 PHP | 📅 2025-09-25 -  A MySQL engine written in pure PHP.
* [Nette Tester](https://github.com/nette/tester) ⭐ 481 | 🐛 22 | 🌐 PHP | 📅 2026-02-09 - A productive and enjoyable parallel unit testing framework.
* [Phake](https://github.com/phake/phake) ⭐ 475 | 🐛 19 | 🌐 PHP | 📅 2026-02-09 - Another mock object library for testing.
* [PHP-Mock](https://github.com/php-mock/php-mock) ⭐ 369 | 🐛 3 | 🌐 PHP | 📅 2026-02-06 - A mock library for built-in PHP functions (e.g. time()).
* [PHPUnit Polyfills](https://github.com/Yoast/PHPUnit-Polyfills/) ⭐ 183 | 🐛 4 | 🌐 PHP | 📅 2026-02-05 - Simplifies running PHPUnit tests on multiple PHPUnit versions.
* [Behat](https://docs.behat.org/en/latest/) - A behaviour driven development (BDD) testing framework.
* [Mink](https://mink.behat.org/en/latest/) - Web acceptance testing.
* [Pest](https://pestphp.com/) - A testing framework with a focus on simplicity.
* [PHPT](https://qa.php.net/write-test.php) - A test tool used by PHP itself.

### Continuous Integration

*Libraries and applications for continuous integration.*

* [Setup PHP](https://github.com/shivammathur/setup-php) ⭐ 3,177 | 🐛 4 | 🌐 TypeScript | 📅 2026-02-08 - A GitHub Action for PHP.
* [PHPCI](https://github.com/dancryer/phpci) ⚠️ Archived - An open-source continuous integration platform for PHP.
* [JoliCi](https://github.com/jolicode/JoliCi) ⚠️ Archived - A continuous integration client written in PHP and powered by Docker.
* [CircleCI](https://circleci.com) - A continuous integration platform.
* [GitlabCi](https://about.gitlab.com/solutions/continuous-integration/) - Let GitLab CI test, build, deploy your code. TravisCi like.
* [Jenkins](https://www.jenkins.io/) - A continuous integration platform with [PHP support](https://www.jenkins.io/solutions/php/).
* [SemaphoreCI](https://semaphore.io/) - A continuous integration platform for open-source and private projects.
* [Travis CI](https://www.travis-ci.com) - A continuous integration platform.

### Documentation

*Libraries for generating project documentation.*

* [zircote/swagger-php](https://github.com/zircote/swagger-php) ⭐ 5,288 | 🐛 16 | 🌐 PHP | 📅 2026-02-08 - Generate OpenAPI documentation for your RESTful API.
* [APIGen](https://github.com/apigen/apigen) ⭐ 2,167 | 🐛 24 | 🌐 PHP | 📅 2025-02-21 - Another API documentation generator.
* [daux.io](https://github.com/dauxio/daux.io) ⭐ 824 | 🐛 12 | 🌐 PHP | 📅 2026-02-07 - A documentation generator that uses Markdown files.
* [phpDocumentor](https://phpdoc.org/) - A documentation generator.
* [phpDox](https://phpdox.net/) - A documentation generator for PHP projects (that is not limited to API documentation).

### Security

*Libraries for generating secure random numbers, encrypting data and scanning and testing for vulnerabilities.*

* [SQLMap](https://github.com/sqlmapproject/sqlmap) ⭐ 36,565 | 🐛 57 | 🌐 Python | 📅 2026-02-05 - An automatic SQL injection and database takeover tool.
* [Zap](https://github.com/zaproxy/zaproxy) ⭐ 14,727 | 🐛 849 | 🌐 Java | 📅 2026-02-09 - An integrated penetration testing tool for web applications.
* [Halite](https://paragonie.com/project/halite) - A simple library for encryption using [libsodium](https://github.com/jedisct1/libsodium) ⭐ 13,446 | 🐛 1 | 🌐 C | 📅 2026-02-08.
* [random\_compat](https://github.com/paragonie/random_compat) ⭐ 8,174 | 🐛 5 | 🌐 PHP | 📅 2024-09-10 - PHP 5.x support for `random_bytes()` and `random_int()`
* [PHP Encryption](https://github.com/defuse/php-encryption) ⭐ 3,869 | 🐛 11 | 🌐 PHP | 📅 2024-01-02 - Secure PHP Encryption Library.
* [PHPGGC](https://github.com/ambionics/phpggc) ⭐ 3,732 | 🐛 13 | 🌐 PHP | 📅 2025-09-29 - A library of PHP unserializable payloads along with a tool to generate them.
* [Roave Security Advisories](https://github.com/Roave/SecurityAdvisories) ⭐ 2,870 | 🐛 1 | 📅 2026-02-10 - This package ensures that your application doesn't have installed dependencies with known security vulnerabilities.
* [Optimus](https://github.com/jenssegers/optimus) ⭐ 1,276 | 🐛 14 | 🌐 PHP | 📅 2024-03-27 - Id obfuscation based on Knuth's multiplicative hashing method.
* [AntiXSS](https://github.com/voku/anti-xss) ⭐ 704 | 🐛 37 | 🌐 PHP | 📅 2026-02-06 - A library that tries to preventing Cross-Site Scripting (XSS) attacks by blacklisting.
* [Secure Headers](https://github.com/BePsvPT/secure-headers) ⭐ 547 | 🐛 2 | 🌐 PHP | 📅 2025-11-24 - A package that adds security related headers to HTTP response.
* [OWASP](https://owasp.org/) - Explore the world of cyber security.
* [PHPSecLib](https://phpseclib.sourceforge.net) - A pure PHP secure communications library.

### Passwords

*Libraries and tools for working with and storing passwords.*

* [Password Compat](https://github.com/ircmaxell/password_compat) ⭐ 2,137 | 🐛 19 | 🌐 PHP | 📅 2024-02-05 - A compatibility library for the new PHP 5.5 password functions.
* [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) ⭐ 866 | 🐛 27 | 🌐 PHP | 📅 2025-02-24 - A realistic PHP password strength estimate library based on Zxcvbn JS.
* [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) ⭐ 373 | 🐛 11 | 🌐 PHP | 📅 2017-10-30 - A library for generating and validating passwords.
* [Password-Generator](https://github.com/hackzilla/password-generator) ⭐ 303 | 🐛 5 | 🌐 PHP | 📅 2024-09-01 - PHP library to generate random passwords.
* [Password Validator](https://github.com/jeremykendall/password-validator) ⭐ 142 | 🐛 3 | 🌐 PHP | 📅 2018-04-07 - A library for validating and upgrading password hashes.
* [GenPhrase](https://github.com/timoh6/GenPhrase) ⭐ 118 | 🐛 1 | 🌐 PHP | 📅 2025-02-17 - A library for generating secure random passphrases.
* [Password Policy](https://github.com/ircmaxell/password-policy) ⭐ 78 | 🐛 8 | 🌐 PHP | 📅 2016-09-07 - A password policy library for PHP and JavaScript.
* [phpass](https://www.openwall.com/phpass/) - A portable password hashing framework.

### Code Analysis

*Libraries and tools for analysing, parsing and manipulating codebases.*

* [PHP Parser](https://github.com/nikic/PHP-Parser) ⭐ 17,413 | 🐛 65 | 🌐 PHP | 📅 2025-12-06 - A PHP parser written in PHP.
* [Rector](https://github.com/rectorphp/rector) ⭐ 10,183 | 🐛 19 | 🌐 PHP | 📅 2026-02-09 - A tool to upgrade and refactor code.
* [GrumPHP](https://github.com/phpro/grumphp) ⭐ 4,269 | 🐛 5 | 🌐 PHP | 📅 2026-02-03 - A PHP code-quality tool.
* [PHPLOC](https://github.com/sebastianbergmann/phploc) ⚠️ Archived - A tool for quickly measuring the size of a PHP project.
* [Phpactor](https://github.com/phpactor/phpactor) ⭐ 1,802 | 🐛 292 | 🌐 PHP | 📅 2026-01-29 - PHP completion, refactoring and introspection tool.
* [Better Reflection](https://github.com/Roave/BetterReflection) ⭐ 1,232 | 🐛 22 | 🌐 PHP | 📅 2026-02-09 - AST-based reflection library that allows analysis and manipulation of code
* [PHP Magic Number Detector](https://github.com/povils/phpmnd) ⭐ 579 | 🐛 21 | 🌐 PHP | 📅 2026-01-06 - A library that detects magic numbers in code.
* [UBench](https://github.com/devster/ubench) ⭐ 564 | 🐛 3 | 🌐 PHP | 📅 2023-09-14 - A simple micro-benchmark library.
* [PHPQA](https://github.com/EdgedesignCZ/phpqa) ⭐ 561 | 🐛 1 | 🌐 XSLT | 📅 2025-11-22 - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
* [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to [scrutinise PHP code](https://github.com/scrutinizer-ci/php-analyzer) ⭐ 440 | 🐛 414 | 📅 2021-10-03.
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) ⭐ 434 | 🐛 39 | 🌐 PHP | 📅 2026-02-05 - A command line utility that compares two source sets and determines the appropriate semantic versioning to apply.
* [Editorconfig-Checker](https://github.com/editorconfig-checker/editorconfig-checker.php) ⭐ 74 | 🐛 6 | 🌐 PHP | 📅 2026-01-28 - A command line utility which verifies that your files implement your `.editorconfig` rules.
* [Code Climate](https://codeclimate.com) - An automated code review.
* [PHP AST Viewer](https://php-ast-viewer.com/) - A tool for viewing the Abstract Syntax Tree of PHP code.

### Code Quality

*Libraries for managing code quality, formatting and linting.*

* [PHP CS Fixer](https://github.com/PHP-CS-Fixer/PHP-CS-Fixer) ⭐ 13,456 | 🐛 87 | 🌐 PHP | 📅 2026-02-09 - A coding standards fixer library.
* [Laravel Pint](https://github.com/laravel/pint) ⭐ 3,085 | 🐛 21 | 🌐 PHP | 📅 2026-02-04 - A coding standards fixer library for Laravel.
* [PHP Mess Detector](https://github.com/phpmd/phpmd) ⭐ 2,414 | 🐛 102 | 🌐 PHP | 📅 2026-02-08 - A library that scans code for bugs, sub-optimal code, unused parameters and more.
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) ⚠️ Archived - A library that detects copied and pasted code.
* [PHP CodeSniffer](https://github.com/PHPCSStandards/PHP_CodeSniffer) ⭐ 1,463 | 🐛 174 | 🌐 PHP | 📅 2026-02-05 - A library that detects and can auto-fix PHP, CSS and JS coding standard violations.
* [CaptainHook](https://github.com/captainhook-git/captainhook) ⭐ 1,091 | 🐛 9 | 🌐 PHP | 📅 2026-02-08 - An easy-to-use and flexible Git hook library.
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) ⭐ 166 | 🐛 18 | 🌐 PHP | 📅 2022-12-09 - A tool to help adhere to certain coding conventions.
* [PHP CS Fixer Configurator](https://mlocati.github.io/php-cs-fixer-configurator/) - A web application to help configure PHP CS Fixer rule sets.

### Static Analysis

*Libraries for performing static analysis of PHP code.*

* [PHPStan](https://github.com/phpstan/phpstan) ⭐ 13,811 | 🐛 1,339 | 🌐 PHP | 📅 2026-02-09 - A PHP Static Analysis Tool.
* [Psalm](https://github.com/vimeo/psalm) ⭐ 5,801 | 🐛 1,942 | 🌐 PHP | 📅 2026-02-08 - A static analysis tool for finding errors in PHP applications.
* [phan](https://github.com/phan/phan) ⭐ 5,604 | 🐛 796 | 🌐 PHP | 📅 2026-02-09 - A static analyzer based on PHP 7+ and the php-ast extension.
* [PHP Metrics](https://github.com/phpmetrics/PhpMetrics) ⭐ 2,583 | 🐛 3 | 🌐 PHP | 📅 2025-09-25 - A static metric library.
* [PHPCompatibility](https://github.com/PHPCompatibility/PHPCompatibility) ⭐ 2,279 | 🐛 89 | 🌐 PHP | 📅 2026-02-05 - A PHP compatibility checker for PHP CodeSniffer.
* [PHPDoc Parser](https://github.com/phpstan/phpdoc-parser) ⭐ 1,512 | 🐛 16 | 🌐 PHP | 📅 2026-02-06 - Next-gen phpDoc parser with support for intersection types and generics
* [PHP Architecture Tester](https://github.com/carlosas/phpat) ⭐ 1,231 | 🐛 12 | 🌐 PHP | 📅 2026-01-27 - Easy-to-use architecture testing tool for PHP.
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) ⭐ 573 | 🐛 15 | 🌐 PHP | 📅 2023-12-03 - A tool to create customizable dependency graphs.
* [Mondrian](https://github.com/Trismegiste/Mondrian) ⭐ 394 | 🐛 9 | 🌐 PHP | 📅 2021-10-22 - A code analysis tool using Graph Theory.
* [Exakat](https://github.com/exakat/exakat) ⭐ 378 | 🐛 47 | 🌐 PHP | 📅 2022-03-24 - A static analysis engine for PHP.
* [PHP Migration](https://github.com/monque/PHP-Migration) ⭐ 203 | 🐛 4 | 🌐 PHP | 📅 2018-07-20 - A static analyzer for PHP version migration.
* [Deptrac](https://github.com/qossmic/deptrac) ⚠️ Archived - A static code analysis tool that helps to enforce rules for dependencies between software layers.

### Architectural

*Libraries related to design patterns, programming approaches and ways to organize code.*

* [Design Patterns PHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP) ⭐ 22,193 | 🐛 1 | 🌐 PHP | 📅 2025-02-03 - A repository of software patterns implemented in PHP.
* [Functional PHP](https://github.com/lstrojny/functional-php) ⭐ 1,985 | 🐛 23 | 🌐 PHP | 📅 2024-05-12 - A functional programming library.
* [Finite](https://github.com/yohang/Finite) ⭐ 1,339 | 🐛 0 | 🌐 PHP | 📅 2025-12-01 - A simple PHP finite state machine.
* [Iter](https://github.com/nikic/iter) ⭐ 1,144 | 🐛 15 | 🌐 PHP | 📅 2025-08-10 - A library that provides iteration primitives using generators.
* [Pipeline](https://github.com/thephpleague/pipeline) ⭐ 1,000 | 🐛 4 | 🌐 PHP | 📅 2025-02-06 - A pipeline pattern implementation.
* [RulerZ](https://github.com/K-Phoen/rulerz) ⭐ 880 | 🐛 26 | 🌐 PHP | 📅 2022-09-02 - A powerful rule engine and implementation of the Specification pattern.
* [Porter](https://github.com/ScriptFUSION/Porter) ⭐ 614 | 🐛 11 | 🌐 PHP | 📅 2026-01-08 - Data import abstraction library for consuming Web APIs and other data sources.
* [IterTools PHP](https://github.com/markrogoyski/itertools-php) ⭐ 149 | 🐛 1 | 🌐 PHP | 📅 2025-02-24 - A library that provides functionality for working with iterable entities (similar to itertools library in Python).

### Debugging and Profiling

*Libraries and tools for debugging errors and profiling code.*

* [Whoops](https://github.com/filp/whoops) ⭐ 13,251 | 🐛 9 | 🌐 PHP | 📅 2025-11-28 - A pretty error-handling library.
* [Symfony VarDumper](https://github.com/symfony/var-dumper) ⭐ 7,449 | 🐛 0 | 🌐 PHP | 📅 2026-01-29 - A variable dumper component.
* [xDebug](https://github.com/xdebug/xdebug) ⭐ 3,371 | 🐛 11 | 🌐 PHP | 📅 2026-02-03 - A debug and profile tool for PHP.
* [Kint](https://github.com/kint-php/kint) ⭐ 2,826 | 🐛 4 | 🌐 PHP | 📅 2026-01-18 - A debugging and profiling tool.
* [XHProf](https://github.com/phacility/xhprof) ⭐ 2,613 | 🐛 34 | 🌐 PHP | 📅 2019-05-28 - A profiling tool originally developed by Facebook.
* [PHPBench](https://github.com/phpbench/phpbench) ⭐ 1,980 | 🐛 36 | 🌐 PHP | 📅 2025-12-12 - A benchmarking Framework.
* [Tracy](https://github.com/nette/tracy) ⭐ 1,817 | 🐛 41 | 🌐 PHP | 📅 2026-02-09 - A simple error detection, logging and time measuring library.
* [PHPSpy](https://github.com/adsr/phpspy) ⭐ 1,478 | 🐛 17 | 🌐 C | 📅 2025-06-10 - A low-overhead sampling profiler.
* [Barbushin PHP Console](https://github.com/barbushin/php-console) ⭐ 1,339 | 🐛 56 | 🌐 PHP | 📅 2024-02-07 - Another web debugging console using Google Chrome.
* [PCOV](https://github.com/krakjoe/pcov) ⭐ 767 | 🐛 29 | 🌐 C | 📅 2025-09-15 - A self-contained code coverage compatible driver.
* [PHP Console](https://github.com/Seldaek/php-console) ⭐ 526 | 🐛 6 | 🌐 PHP | 📅 2021-03-14 - A web debugging console.
* [Metrics](https://github.com/beberlei/metrics) ⭐ 322 | 🐛 12 | 🌐 PHP | 📅 2026-01-13 - A simple metrics API library.
* [APM](https://pecl.php.net/package/APM) - Monitoring extension collecting errors and statistics into SQLite/MySQL/StatsD.
* [PHP Debug Bar](http://phpdebugbar.com/) - A debugging toolbar.
* [Z-Ray](https://www.zend.com/products/z-ray) - A debug and profile tool for Zend Server.

### Error Tracking and Monitoring Services

*Self-hosted or cloud-based application performance monitoring & error tracking tools*

* [Blackfire](https://www.blackfire.io) - A low-overhead code profiler.
* [BugSnag](https://www.bugsnag.com/) - Error and Real User Monitoring.
* [Honeybadger](https://www.honeybadger.io/) - Error Tracking & Application Monitoring for Developers.
* [Rollbar](https://rollbar.com/) - Error Logging & Tracking Service for Software Teams.
* [Sentry](https://sentry.io/welcome/) - Application Performance Monitoring & Error Tracking Software.
* [Tideways](https://tideways.com/) - Monitoring and profiling tool.

### Build Tools

*Project build and automation tools.*

* [Box](https://github.com/box-project/box) ⭐ 1,279 | 🐛 80 | 🌐 PHP | 📅 2026-02-09 - A utility to build PHAR files.
* [RMT](https://github.com/liip/RMT) ⭐ 458 | 🐛 22 | 🌐 PHP | 📅 2025-12-03 - A library for versioning and releasing software.
* [Construct](https://github.com/jonathantorres/construct) ⭐ 265 | 🐛 14 | 🌐 PHP | 📅 2023-01-22 - A PHP project/micro-package generator.
* [Phing](https://www.phing.info/) - A PHP project build system inspired by Apache Ant.

### Task Runners

*Libraries for automating and running tasks.*

* [Robo](https://github.com/consolidation/Robo) ⭐ 2,703 | 🐛 182 | 🌐 PHP | 📅 2025-11-14 - A PHP Task runner with object-orientated configurations.
* [Jobby](https://github.com/jobbyphp/jobby) ⭐ 1,049 | 🐛 36 | 🌐 PHP | 📅 2024-03-29 - A PHP cron job manager without modifying crontab.
* [Bldr](https://bldr.io/) - A PHP Task runner built on Symfony components.
* [Task](https://taskphp.github.io/) - A pure PHP task runner inspired by Grunt and Gulp.

### Navigation

*Tools for building navigation structures.*

* [KnpMenu](https://github.com/KnpLabs/KnpMenu) ⭐ 1,401 | 🐛 24 | 🌐 PHP | 📅 2025-12-09 - A menu library.
* [Menu](https://github.com/spatie/menu) ⭐ 759 | 🐛 0 | 🌐 PHP | 📅 2025-09-08 - A flexible menu library with a fluent interface.

### Asset Management

*Tools for managing, compressing and minifying website assets.*

* [Laravel Mix](https://github.com/laravel-mix/laravel-mix) ⭐ 5,249 | 🐛 272 | 🌐 JavaScript | 📅 2024-01-24 - An elegant wrapper around Webpack for the 80% use case.
* [Symfony Asset](https://github.com/symfony/asset) ⭐ 3,162 | 🐛 0 | 🌐 PHP | 📅 2026-02-09 - Manages URL generation and versioning of web assets.
* [Symfony Encore](https://github.com/symfony/webpack-encore) ⭐ 2,235 | 🐛 17 | 🌐 JavaScript | 📅 2025-11-18 - A simple but powerful API for processing and compiling assets built around Webpack.
* [JShrink](https://github.com/tedious/JShrink) ⭐ 762 | 🐛 14 | 🌐 PHP | 📅 2025-11-20 - A JavaScript minifier library.

### Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [Country List](https://github.com/umpirsky/country-list) ⭐ 5,249 | 🐛 12 | 🌐 HTML | 📅 2022-03-11 - A list of all countries with names and ISO 3166-1 codes.
* [PHPGeo](https://github.com/mjaschen/phpgeo) ⭐ 1,609 | 🐛 21 | 🌐 PHP | 📅 2026-01-21 - A simple geo library.
* [GeoTools](https://github.com/thephpleague/geotools) ⭐ 1,402 | 🐛 24 | 🌐 PHP | 📅 2025-06-12 - A library of geo-related tools.
* [GeoJSON](https://github.com/jmikola/geojson) ⭐ 304 | 🐛 10 | 🌐 PHP | 📅 2024-01-17 - A GeoJSON implementation.
* [GeoCoder](https://geocoder-php.org/) - A geocoding library.

### Date and Time

*Libraries for working with dates and times.*

* [Carbon](https://github.com/briannesbitt/Carbon) ⭐ 16,635 | 🐛 13 | 🌐 PHP | 📅 2026-02-09 - A simple DateTime API extension.
* [Chronos](https://github.com/cakephp/chronos) ⭐ 1,359 | 🐛 7 | 🌐 PHP | 📅 2026-02-08 - A DateTime API extension supporting both mutable and immutable date/time.
* [Yasumi](https://github.com/azuyalabs/yasumi) ⭐ 1,078 | 🐛 0 | 🌐 PHP | 📅 2026-02-06 - A library to help you calculate the dates and names of holidays.
* [Moment.php](https://github.com/fightbulc/moment.php) ⭐ 971 | 🐛 21 | 🌐 PHP | 📅 2025-07-27 - Moment.js inspired PHP DateTime handler with i18n support.
* [CalendR](https://github.com/yohang/CalendR) ⭐ 465 | 🐛 11 | 🌐 PHP | 📅 2025-12-02 - A calendar management library.

### Event

*Libraries that are event-driven or implement non-blocking event loops.*

* [Swoole](https://github.com/swoole/swoole-src) ⭐ 18,844 | 🐛 3 | 🌐 C++ | 📅 2026-02-09 - An event-driven asynchronous and concurrent networking communication framework with high performance for PHP written in C.
* [Workerman](https://github.com/walkor/Workerman) ⭐ 11,514 | 🐛 101 | 🌐 PHP | 📅 2026-02-02 - An event driven non-blocking I/O library.
* [ReactPHP](https://github.com/reactphp/reactphp) ⭐ 9,085 | 🐛 0 | 🌐 PHP | 📅 2024-11-25 - An event driven non-blocking I/O library.
* [Ratchet](https://github.com/ratchetphp/Ratchet) ⭐ 6,427 | 🐛 9 | 🌐 PHP | 📅 2025-10-25 - A web socket library.
* [Amp](https://github.com/amphp/amp) ⭐ 4,397 | 🐛 16 | 🌐 PHP | 📅 2025-10-04 - An event driven non-blocking I/O library.
* [RxPHP](https://github.com/ReactiveX/RxPHP) ⭐ 1,733 | 🐛 14 | 🌐 PHP | 📅 2025-10-27 - A reactive extension library.
* [Event](https://github.com/thephpleague/event) ⭐ 1,567 | 🐛 2 | 🌐 PHP | 📅 2025-03-14 - An event library with a focus on domain events.
* [Broadway](https://github.com/broadway/broadway) ⭐ 1,511 | 🐛 3 | 🌐 PHP | 📅 2026-01-27 - An event source and CQRS library.
* [Evenement](https://github.com/igorw/evenement) ⭐ 1,340 | 🐛 3 | 🌐 PHP | 📅 2025-12-26 - An event dispatcher library.
* [Pawl](https://github.com/ratchetphp/Pawl) ⭐ 614 | 🐛 26 | 🌐 PHP | 📅 2025-03-19 - An asynchronous web socket client.
* [Fast CGI Client](https://github.com/hollodotme/fast-cgi-client) ⭐ 563 | 🐛 14 | 🌐 PHP | 📅 2024-05-02 - A client to make synchronous/asynchronous requests through php-fpm socket.
* [Prooph Event Store](https://github.com/prooph/event-store) ⭐ 547 | 🐛 1 | 🌐 PHP | 📅 2025-04-21 - An event source component to persist event messages
* [PHP Defer](https://github.com/php-defer/php-defer) ⭐ 307 | 🐛 0 | 🌐 PHP | 📅 2023-09-21 - Golang's defer statement for PHP.
* [Elephant.io](https://github.com/ElephantIO/elephant.io) ⭐ 134 | 🐛 3 | 🌐 PHP | 📅 2026-02-02 - Yet another web socket library.
* [CakePHP Event](https://github.com/cakephp/event) ⭐ 22 | 🐛 0 | 🌐 PHP | 📅 2026-01-15 - An event dispatcher library.
* [FrankenPHP](https://frankenphp.dev/) - A modern PHP app server written in Go.

### Logging

*Libraries for generating and working with log files.*

* [Monolog](https://github.com/Seldaek/monolog) ⭐ 21,389 | 🐛 34 | 🌐 PHP | 📅 2026-02-01 - A comprehensive logger.

### E-commerce

*Libraries and applications for taking payments and building online e-commerce stores.*

* [OmniPay](https://github.com/thephpleague/omnipay) ⭐ 6,050 | 🐛 128 | 🌐 PHP | 📅 2025-10-05 - A framework agnostic multi-gateway payment processing library.
* [Money](https://github.com/moneyphp/money) ⭐ 4,812 | 🐛 5 | 🌐 PHP | 📅 2025-10-23 - A PHP implementation of Fowler's money pattern.
* [Shopware](https://github.com/shopware/shopware) ⭐ 3,274 | 🐛 1,439 | 🌐 PHP | 📅 2026-02-09 - Highly customizable e-commerce software
* [Payum](https://github.com/payum/payum) ⭐ 1,919 | 🐛 97 | 🌐 PHP | 📅 2026-01-25 - A payment abstraction library.
* [Brick Money](https://github.com/brick/money) ⭐ 1,877 | 🐛 11 | 🌐 PHP | 📅 2026-01-22 - A money library for PHP, with support for contexts, cash roundings, currency conversion.
* [Swap](https://github.com/florianv/swap) ⭐ 1,330 | 🐛 1 | 🌐 PHP | 📅 2025-03-06 - An exchange rates library.
* [Shopsys Framework](https://github.com/shopsys/shopsys/) ⭐ 346 | 🐛 145 | 🌐 PHP | 📅 2026-02-09 - An open source e-commerce platform for in-house development teams.
* [Sylius](https://sylius.com/) - An open source e-commerce solution.

### PDF

*Libraries and software for working with PDF files.*

* [Dompdf](https://github.com/dompdf/dompdf) ⭐ 11,065 | 🐛 542 | 🌐 PHP | 📅 2026-01-22 - A HTML to PDF converter.
* [Browsershot](https://github.com/spatie/browsershot) ⭐ 5,174 | 🐛 0 | 🌐 PHP | 📅 2026-02-09 - Convert HTML to an image, PDF or string.
* [Snappy](https://github.com/KnpLabs/snappy) ⭐ 4,471 | 🐛 21 | 🌐 PHP | 📅 2025-11-19 - A PDF and image generation library.
* [Gotenberg](https://github.com/gotenberg/gotenberg-php) ⭐ 359 | 🐛 1 | 🌐 PHP | 📅 2026-01-27 - A PHP client for interacting with Gotenberg.
* [TCPDF](https://tcpdf.org/) - An open source PHP class for generating PDF documents.

### Office

*Libraries for working with office suite documents.*

* [PHPSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet) ⭐ 13,889 | 🐛 99 | 🌐 PHP | 📅 2026-02-06 - A pure PHP library for reading and writing spreadsheet files (successor of PHPExcel).
* [PHPWord](https://github.com/PHPOffice/PHPWord) ⭐ 7,540 | 🐛 1,219 | 🌐 PHP | 📅 2025-07-26 - A library for working with Microsoft Word documents.
* [PHPPowerPoint](https://github.com/PHPOffice/PHPPresentation) ⭐ 1,362 | 🐛 258 | 🌐 PHP | 📅 2025-10-24 - A library for working with Microsoft PowerPoint Presentations.
* [OpenSpout](https://github.com/openspout/openspout) ⭐ 1,092 | 🐛 67 | 🌐 PHP | 📅 2026-02-09 - A community driven fork of `box/spout`, a PHP library to read and write spreadsheet files (CSV, XLSX and ODS), in a fast and scalable way.

### Database

*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

* [ProxyManager](https://github.com/Ocramius/ProxyManager) ⭐ 4,976 | 🐛 53 | 🌐 PHP | 📅 2026-02-02 - A set of utilities to generate proxy objects for data mappers.
* [Doctrine Extensions](https://github.com/doctrine-extensions/DoctrineExtensions) ⭐ 4,120 | 🐛 76 | 🌐 PHP | 📅 2026-02-09 - A collection of Doctrine behavioural extensions.
* [Laravel Eloquent](https://github.com/illuminate/database) ⭐ 2,757 | 🐛 7 | 🌐 PHP | 📅 2026-02-09 - A simple ORM.
* [Baum](https://github.com/etrepat/baum) ⭐ 2,232 | 🐛 159 | 🌐 PHP | 📅 2024-06-11 - A nested set implementation for Eloquent.
* [Cycle ORM](https://github.com/cycle/orm) ⭐ 1,326 | 🐛 85 | 🌐 PHP | 📅 2026-01-30 - PHP DataMapper, ORM.
* [Spot2](https://github.com/spotorm/spot2) ⭐ 599 | 🐛 67 | 🌐 PHP | 📅 2025-08-08 - A MySQL datamapper ORM.
* [Aura.Sql](https://github.com/auraphp/Aura.Sql) ⭐ 564 | 🐛 3 | 🌐 PHP | 📅 2026-01-05 - Provides an extension to the native PDO along with a profiler and connection locator.
* [Aura.SqlQuery](https://github.com/auraphp/Aura.SqlQuery) ⭐ 456 | 🐛 25 | 🌐 PHP | 📅 2025-12-24 - Independent query builders for MySQL, PostgreSQL, SQLite, and Microsoft SQL Server.
* [Atlas.Orm](https://github.com/atlasphp/Atlas.Orm) ⭐ 428 | 🐛 9 | 🌐 PHP | 📅 2021-05-30 - A data mapper implementation for your persistence model in PHP.
* [Slimdump](https://github.com/webfactory/slimdump) ⭐ 187 | 🐛 10 | 🌐 PHP | 📅 2026-02-04 - An easy dumper tool for MySQL.
* [Pomm](https://github.com/chanmix51/Pomm) ⭐ 164 | 🐛 0 | 🌐 PHP | 📅 2017-05-21 - An Object Model Manager for PostgreSQL.
* [CakePHP ORM](https://github.com/cakephp/orm) ⭐ 147 | 🐛 1 | 🌐 PHP | 📅 2026-01-15 - Object-Relational Mapper, implemented using the DataMapper pattern.
* [Doctrine](https://www.doctrine-project.org/) - A comprehensive DBAL and ORM.
* [RedBean](https://redbeanphp.com/index.php) - A lightweight, configuration-less ORM.

### Migrations

Libraries to help manage database schemas and migrations.

* [Phinx](https://github.com/cakephp/phinx) ⭐ 4,518 | 🐛 148 | 🌐 PHP | 📅 2026-02-09 - Another database migration library.
* [PHPMig](https://github.com/davedevelopment/phpmig) ⭐ 570 | 🐛 29 | 🌐 PHP | 📅 2025-04-29 - Another migration management library.
* [Ruckusing](https://github.com/ruckus/ruckusing-migrations) ⭐ 502 | 🐛 34 | 🌐 PHP | 📅 2025-01-08 - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite.
* [Migrations](https://github.com/icomefromthenet/Migrations) ⭐ 39 | 🐛 0 | 🌐 PHP | 📅 2016-10-06 - A migration management library.
* [Doctrine Migrations](https://www.doctrine-project.org/projects/migrations.html) - A migration library for Doctrine.

### NoSQL

*Libraries for working with "NoSQL" backends.*

* [Predis](https://github.com/predis/predis) ⭐ 7,750 | 🐛 27 | 🌐 PHP | 📅 2026-02-09 - A feature-complete Redis library.
* [MongoDB](https://github.com/mongodb/mongo-php-driver) ⭐ 919 | 🐛 16 | 🌐 PHP | 📅 2026-02-09 - MongoDB PHP Driver.
* [PHPMongo](https://github.com/sokil/php-mongo) ⭐ 239 | 🐛 42 | 🌐 PHP | 📅 2023-02-07 - A MongoDB ORM.

### Queue

*Libraries for working with event and task queues.*

* [PHP AMQP](https://github.com/php-amqplib/php-amqplib) ⭐ 4,598 | 🐛 22 | 🌐 PHP | 📅 2026-01-06 - A pure PHP AMQP library.
* [Enqueue](https://github.com/php-enqueue/enqueue-dev) ⭐ 2,215 | 🐛 60 | 🌐 PHP | 📅 2025-12-22 - A message queue packages for PHP that supports RabbitMQ, AMQP, STOMP, Amazon SQS, Redis and Doctrine transports.
* [Pheanstalk](https://github.com/pheanstalk/pheanstalk) ⭐ 1,926 | 🐛 7 | 🌐 PHP | 📅 2025-11-11 - A Beanstalkd client library.
* [Bernard](https://github.com/bernardphp/bernard) ⭐ 1,213 | 🐛 38 | 🌐 PHP | 📅 2023-07-31 - A multibackend abstraction library.
* [BunnyPHP](https://github.com/jakubkulhan/bunny) ⭐ 740 | 🐛 45 | 🌐 PHP | 📅 2026-01-24 - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library.
* [Thumper](https://github.com/php-amqplib/Thumper) ⭐ 276 | 🐛 8 | 🌐 PHP | 📅 2021-12-21 - A RabbitMQ pattern library.
* [Tarantool Queue](https://github.com/tarantool-php/queue) ⭐ 64 | 🐛 2 | 🌐 PHP | 📅 2025-03-08 - PHP bindings for Tarantool Queue.

### Search

*Libraries and software for indexing and performing search queries on data.*

* [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php) ⭐ 5,343 | 🐛 10 | 🌐 PHP | 📅 2026-02-09 - The official client library for [ElasticSearch](https://www.elastic.co/).
* [Elastica](https://github.com/ruflin/Elastica) ⭐ 2,271 | 🐛 102 | 🌐 PHP | 📅 2025-12-30 - A client library for ElasticSearch.
* [Solarium](https://www.solarium-project.org/) - A client library for [Solr](https://solr.apache.org/).
* [SphinxQL Query Builder](https://foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the [Sphinx](https://sphinxsearch.com/) and [Manticore](https://manticoresearch.com/) search engines.

### Command Line

*Libraries related to the command line.*

* [PsySH](https://github.com/bobthecow/psysh) ⭐ 9,833 | 🐛 32 | 🌐 PHP | 📅 2026-01-30 - Another PHP REPL.
* [Cron Expression](https://github.com/mtdowling/cron-expression) ⭐ 4,872 | 🐛 11 | 🌐 PHP | 📅 2024-04-19 - A library to calculate cron run dates.
* [CLI Menu](https://github.com/php-school/cli-menu) ⭐ 1,948 | 🐛 8 | 🌐 PHP | 📅 2025-08-11 - A library for building CLI menus.
* [CLImate](https://github.com/thephpleague/climate) ⭐ 1,884 | 🐛 14 | 🌐 PHP | 📅 2025-10-17 - A library for outputting colors and special formatting.
* [Commando](https://github.com/nategood/commando) ⭐ 802 | 🐛 35 | 🌐 PHP | 📅 2024-05-07 - Another simple command line opt parser.
* [ShellWrap](https://github.com/MrRio/shellwrap) ⭐ 738 | 🐛 9 | 🌐 PHP | 📅 2025-11-10 - A simple command line wrapper library.
* [Cilex](https://github.com/Cilex/Cilex) ⭐ 619 | 🐛 4 | 🌐 PHP | 📅 2023-12-14 - A micro framework for building command line tools.
* [CLIFramework](https://github.com/c9s/CLIFramework) ⭐ 437 | 🐛 43 | 🌐 PHP | 📅 2023-04-20 - A command-line framework supports zsh/bash completion generation, subcommands and option constraints. It also powers phpbrew.
* [GetOpt](https://github.com/getopt-php/getopt-php) ⭐ 342 | 🐛 4 | 🌐 PHP | 📅 2025-02-15 - A command line opt parser.
* [GetOptionKit](https://github.com/c9s/GetOptionKit) ⭐ 149 | 🐛 8 | 🌐 PHP | 📅 2025-01-04 - Another command line opt parser.
* [Aura.Cli](https://github.com/auraphp/Aura.Cli) ⭐ 102 | 🐛 2 | 🌐 PHP | 📅 2024-06-07 - Provides the equivalent of request ( Context ) and response ( Stdio ) objects for the command line interface, including Getopt support, and an independent Help object for describing commands.

### Authentication and Authorization

*Libraries for implementing user authentication and authorization.*

* [Json Web Token](https://github.com/lcobucci/jwt) ⭐ 7,474 | 🐛 7 | 🌐 PHP | 📅 2026-02-03 - Json Tokens to authenticate and transmit information.
* [TwitterOAuth](https://github.com/abraham/twitteroauth) ⭐ 4,305 | 🐛 9 | 🌐 PHP | 📅 2026-02-09 - A Twitter OAuth library.
* [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) ⭐ 3,780 | 🐛 57 | 🌐 PHP | 📅 2026-02-09 - An OAuth 2.0 client library.
* [Paseto](https://github.com/paragonie/paseto) ⭐ 3,367 | 🐛 1 | 🌐 PHP | 📅 2025-07-19 - Platform-Agnostic Security Tokens.
* [Opauth](https://github.com/opauth/opauth) ⭐ 1,638 | 🐛 33 | 🌐 PHP | 📅 2020-05-15 - A multi-provider authentication framework.
* [PHP oAuthLib](https://github.com/daviddesberg/PHPoAuthLib) ⭐ 1,080 | 🐛 167 | 🌐 PHP | 📅 2024-01-08 - Another OAuth library.
* [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) ⭐ 998 | 🐛 9 | 🌐 PHP | 📅 2024-12-10 - An OAuth 1.0 client library.
* [SocialConnect Auth](https://github.com/socialConnect/auth) ⭐ 562 | 🐛 36 | 🌐 PHP | 📅 2025-08-28 - An open source social sign (OAuth1\OAuth2\OpenID\OpenIDConnect).
* [Aura.Auth](https://github.com/auraphp/Aura.Auth) ⭐ 134 | 🐛 5 | 🌐 PHP | 📅 2026-01-13 - Provides authentication functionality and session tracking using various adapters.
* [OAuth2 Server](https://bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
* [OAuth2 Server](https://oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.
* [Sentinel Social](https://cartalyst.com/manual/sentinel-social/2.0) - A library for social network authentication.
* [Sentinel](https://cartalyst.com/manual/sentinel/2.0) - A framework agnostic authentication & authorisation library.

### Markup and CSS

*Libraries for working with markup and CSS formats.*

* [Parsedown](https://github.com/erusev/parsedown) ⭐ 15,010 | 🐛 184 | 🌐 PHP | 📅 2025-08-31 - Another Markdown parser.
* [PHP Markdown](https://github.com/michelf/php-markdown) ⭐ 3,463 | 🐛 99 | 🌐 PHP | 📅 2025-06-17 - A Markdown parser.
* [CommonMark PHP](https://github.com/thephpleague/commonmark) ⭐ 2,927 | 🐛 26 | 🌐 PHP | 📅 2026-02-10 - Highly-extensible Markdown parser which fully supports the [CommonMark spec](https://spec.commonmark.org/).
* [HTML to Markdown](https://github.com/thephpleague/html-to-markdown) ⭐ 1,857 | 🐛 23 | 🌐 PHP | 📅 2026-02-06 - Converts HTML into Markdown.
* [PHP CSS Parser](https://github.com/MyIntervals/PHP-CSS-Parser) ⭐ 1,819 | 🐛 158 | 🌐 PHP | 📅 2026-02-09 - A Parser for CSS Files written in PHP.
* [HTML5 PHP](https://github.com/Masterminds/html5-php) ⭐ 1,764 | 🐛 34 | 🌐 HTML | 📅 2025-07-25 - An HTML5 parser and serializer library.
* [Cebe Markdown](https://github.com/cebe/markdown) ⭐ 1,008 | 🐛 44 | 🌐 HTML | 📅 2022-10-04 - A fast and extensible Markdown parser.
* [Essence](https://github.com/essence/essence) ⭐ 770 | 🐛 24 | 🌐 PHP | 📅 2023-03-29 - A library for extracting web media.
* [VObject](https://github.com/sabre-io/vobject) ⭐ 593 | 🐛 100 | 🌐 PHP | 📅 2026-01-12 - A library for parsing VCard and iCalendar objects.
* [Embera](https://github.com/mpratt/Embera) ⭐ 353 | 🐛 6 | 🌐 PHP | 📅 2025-10-07 - An Oembed consumer library.
* [Shiki PHP](https://github.com/spatie/shiki-php) ⭐ 303 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-01 - A [Shiki](https://github.com/shikijs/shiki) ⭐ 12,895 | 🐛 90 | 🌐 TypeScript | 📅 2026-02-06 code highlighting package in PHP.
* [Decoda](https://github.com/milesj/decoda) ⭐ 192 | 🐛 9 | 🌐 PHP | 📅 2022-11-10 - A lightweight markup parser library.
* [Djot](https://github.com/php-collective/djot-php) ⭐ 20 | 🐛 7 | 🌐 PHP | 📅 2026-02-09 - A PHP parser for [Djot](https://djot.net/), a modern light markup language (successor of Markdown).

### JSON

*Libraries for working with JSON.*

* [JSON Lint](https://github.com/Seldaek/jsonlint) ⭐ 1,324 | 🐛 3 | 🌐 PHP | 📅 2024-08-28 - A JSON lint utility.
* [JSONMapper](https://github.com/JsonMapper/JsonMapper) ⭐ 218 | 🐛 9 | 🌐 PHP | 📅 2026-01-29 - A library for mapping JSON to PHP objects.

### Strings

*Libraries for parsing and manipulating strings.*

* [UUID](https://github.com/ramsey/uuid) ⭐ 12,623 | 🐛 19 | 🌐 PHP | 📅 2025-12-14 - A library for generating UUIDs.
* [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) ⭐ 10,686 | 🐛 33 | 🌐 PHP | 📅 2026-02-09 - A lightweight PHP class for detecting mobile devices (including tablets).
* [Agent](https://github.com/jenssegers/agent) ⭐ 4,733 | 🐛 85 | 🌐 PHP | 📅 2024-08-05 - A PHP desktop/mobile user agent parser, based on Mobiledetect.
* [SQL Formatter](https://github.com/jdorn/sql-formatter/) ⭐ 3,864 | 🐛 37 | 🌐 HTML | 📅 2023-05-26 - A library for formatting SQL statements.
* [Device Detector](https://github.com/matomo-org/device-detector) ⭐ 3,433 | 🐛 82 | 🌐 PHP | 📅 2026-02-07 - Another library for parsing user agent strings.
* [Slugify](https://github.com/cocur/slugify) ⭐ 2,907 | 🐛 31 | 🌐 PHP | 📅 2025-11-27 - A library to convert strings to slugs.
* [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) ⚠️ Archived - A library for parsing user agent strings.
* [Jieba-PHP](https://github.com/fukuball/jieba-php) ⭐ 1,374 | 🐛 4 | 🌐 PHP | 📅 2025-12-16 - A PHP port of Python's jieba. Chinese text segmentation for natural language processing.
* [URLify](https://github.com/jbroadway/urlify) ⭐ 676 | 🐛 6 | 🌐 PHP | 📅 2025-04-03 - A PHP port of Django's URLify.js.
* [Portable ASCII](https://github.com/voku/portable-ascii) ⭐ 571 | 🐛 27 | 🌐 PHP | 📅 2026-02-06 - A library to convert strings to ASCII.
* [Portable UTF-8](https://github.com/voku/portable-utf8) ⭐ 519 | 🐛 22 | 🌐 PHP | 📅 2026-02-06 - A string manipulation library with UTF-8 safe replacement methods.
* [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) ⭐ 285 | 🐛 7 | 🌐 PHP | 📅 2024-11-22 - A library for manipulating and converting colors.
* [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) ⭐ 252 | 🐛 12 | 🌐 PHP | 📅 2025-05-02 - An ANSI to HTML5 converter library.
* [Stringy](https://github.com/voku/Stringy) ⭐ 177 | 🐛 7 | 🌐 PHP | 📅 2025-01-17 - A string manipulation library with multibyte support.
* [Url highlight](https://github.com/vstelmakh/url-highlight) ⭐ 100 | 🐛 1 | 🌐 PHP | 📅 2025-10-04 - A library for parsing URLs from text and converting them into clickable links.
* [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) ⭐ 79 | 🐛 1 | 🌐 PHP | 📅 2022-07-12 - A portable library for working with UTF-8 strings.
* [Hyphenation](https://github.com/heiglandreas/Org_Heigl_Hyphenator) ⭐ 54 | 🐛 5 | 🌐 PHP | 📅 2024-02-12 - Text-Hyphenation based on the TeX-hyphenation Algorithm

### Numbers

*Libraries for working with numbers.*

* [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) ⭐ 4,995 | 🐛 3 | 🌐 PHP | 📅 2026-01-30 - A PHP implementation of Google's phone number handling library.
* [MathPHP](https://github.com/markrogoyski/math-php) ⭐ 2,399 | 🐛 55 | 🌐 PHP | 📅 2026-01-23 - A math library for PHP.
* [Brick Math](https://github.com/brick/math) ⭐ 2,109 | 🐛 3 | 🌐 PHP | 📅 2026-02-09 - A library providing large number support: `BigInteger`, `BigDecimal` and `BigRational`.
* [IP](https://github.com/darsyn/ip) ⭐ 258 | 🐛 2 | 🌐 PHP | 📅 2025-02-17 - An immutable value object for working with IPv4 and IPv6 addresses.
* [ByteUnits](https://github.com/gabrielelana/byte-units) ⭐ 167 | 🐛 6 | 🌐 PHP | 📅 2021-01-16 - A library to parse, format and convert byte units in binary and metric systems.
* [PHP Conversion](https://github.com/Crisu83/php-conversion) ⭐ 132 | 🐛 5 | 🌐 PHP | 📅 2022-06-15 - Another library for converting between units of measure.
* [DecimalObject](https://github.com/php-collective/decimal-object) ⭐ 25 | 🐛 1 | 🌐 PHP | 📅 2025-04-03 - A value object to handle decimals/floats easily and more precisely.
* [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) ⭐ 22 | 🐛 0 | 🌐 PHP | 📅 2025-05-01 - A library for converting between units of measure.

### Filtering, Sanitizing and Validation

*Libraries for filtering, sanitizing and validating data.*

* [Respect Validation](https://github.com/Respect/Validation) ⭐ 5,923 | 🐛 6 | 🌐 PHP | 📅 2026-02-10 - A simple validation library.
* [JSON Schema](https://github.com/jsonrainbow/json-schema) ⭐ 3,626 | 🐛 15 | 🌐 PHP | 📅 2026-02-09 - A [JSON Schema](https://json-schema.org/) validation library.
* [HTML Purifier](https://github.com/ezyang/htmlpurifier) ⭐ 3,382 | 🐛 126 | 🌐 PHP | 📅 2025-10-17 - A standards compliant HTML filter.
* [Assert](https://github.com/beberlei/assert) ⭐ 2,433 | 🐛 47 | 🌐 PHP | 📅 2025-10-13 - A validation library with a rich set of assertions. Supports assertion chaining and lazy assertions.
* [Upload](https://github.com/brandonsavage/Upload) ⚠️ Archived - A library for handling file uploads and validation.
* [Valitron](https://github.com/vlucas/valitron) ⭐ 1,602 | 🐛 56 | 🌐 PHP | 📅 2024-04-16 - Another validation library.
* [Valinor](https://github.com/CuyZ/Valinor) ⭐ 1,478 | 🐛 32 | 🌐 PHP | 📅 2026-02-07 - A library for mapping to strongly typed value objects.
* [ISO-codes](https://github.com/ronanguilloux/IsoCodes) ⭐ 802 | 🐛 4 | 🌐 PHP | 📅 2026-01-25 - A library for validating inputs according to standards from ISO, International Finance, Public Administrations, GS1, Book Industry, Phone numbers & Zipcodes for many countries.
* [Filterus](https://github.com/ircmaxell/filterus) ⭐ 449 | 🐛 8 | 🌐 PHP | 📅 2018-11-21 - A simple PHP filtering library.
* [Symfony HTML Sanitizer](https://github.com/symfony/html-sanitizer) ⭐ 276 | 🐛 0 | 🌐 PHP | 📅 2025-11-27 - An HTML sanitizer library.
* [Aura.Filter](https://github.com/auraphp/Aura.Filter) ⭐ 158 | 🐛 3 | 🌐 PHP | 📅 2025-11-25 - Provides tools to validate and sanitize objects and arrays.
* [MetaYaml](https://github.com/romaricdrigon/MetaYaml) ⭐ 102 | 🐛 8 | 🌐 PHP | 📅 2019-03-16 - A schema validation library that supports YAML, JSON and XML.
* [Volan](https://github.com/serkin/Volan) ⭐ 44 | 🐛 0 | 🌐 PHP | 📅 2018-06-19 - Another simplified validation library.
* [CakePHP Validation](https://github.com/cakephp/validation) ⭐ 42 | 🐛 0 | 🌐 PHP | 📅 2026-01-15 - Another validation library.

### API

*Libraries and web tools for developing APIs.*

* [Negotiation](https://github.com/willdurand/Negotiation) ⭐ 1,423 | 🐛 11 | 🌐 PHP | 📅 2023-08-03 - A content negotiation library.
* [Restler](https://github.com/Luracast/Restler) ⭐ 1,372 | 🐛 35 | 🌐 PHP | 📅 2025-12-02 - A lightweight framework to expose PHP methods as RESTful web API.
* [Hateoas](https://github.com/willdurand/Hateoas) ⭐ 1,045 | 🐛 33 | 🌐 PHP | 📅 2026-01-10 - A HATEOAS REST web service library.
* [Jane](https://github.com/janephp/janephp/) ⭐ 672 | 🐛 78 | 🌐 PHP | 📅 2026-01-26 - An OpenApi client generator with validation support.
* [PackageGenerator](https://github.com/WsdlToPhp/PackageGenerator) ⭐ 434 | 🐛 25 | 🌐 PHP | 📅 2026-02-09 - Package Generator generates a PHP SDK from any WSDL.
* [HAL](https://github.com/blongden/hal) ⭐ 201 | 🐛 2 | 🌐 PHP | 📅 2026-01-05 - A Hypertext Application Language (HAL) builder library.
* [Drest](https://github.com/leedavis81/drest) ⭐ 87 | 🐛 3 | 🌐 PHP | 📅 2017-05-11 - A library for exposing Doctrine entities as REST resource endpoints.
* [Laminas API Tool Skeleton](https://github.com/laminas-api-tools/api-tools-skeleton) ⭐ 53 | 🐛 28 | 🌐 PHP | 📅 2024-04-18 - An API builder built with the Laminas Framework.
* [API Platform](https://api-platform.com) - Expose in minutes a hypermedia REST API that embraces JSON-LD, Hydra format.

### Caching and Locking

*Libraries for caching data and acquiring locks.*

* [Doctrine Cache](https://github.com/doctrine/cache) ⭐ 7,894 | 🐛 2 | 🌐 PHP | 📅 2025-10-08 - A caching library.
* [CacheTool](https://github.com/gordalina/cachetool) ⭐ 1,791 | 🐛 18 | 🌐 PHP | 📅 2026-01-28 - A tool to clear APC/opcode caches from the command line.
* [Stash](https://github.com/tedious/Stash) ⭐ 962 | 🐛 34 | 🌐 PHP | 📅 2025-12-27 - Another library for caching.
* [Lock](https://github.com/php-lock/lock) ⭐ 947 | 🐛 5 | 🌐 PHP | 📅 2025-07-29 - A lock library to provide exclusive execution.
* [APIx Cache](https://github.com/apix/cache) ⭐ 115 | 🐛 4 | 🌐 PHP | 📅 2022-07-26 - A thin PSR-6 cache wrapper to various caching backends emphasizing cache tagging and indexing.
* [Laminas Cache](https://github.com/laminas/laminas-cache) ⭐ 106 | 🐛 14 | 🌐 PHP | 📅 2026-02-09 - Another caching library.
* [Metaphore](https://github.com/sobstel/metaphore) ⭐ 100 | 🐛 2 | 🌐 PHP | 📅 2024-02-24 - Cache slam defense using a semaphore to prevent dogpile effect.
* [CakePHP Cache](https://github.com/cakephp/cache) ⭐ 49 | 🐛 0 | 🌐 PHP | 📅 2026-01-15 - A caching library.

### Data Structure and Storage

*Libraries that implement data structure or storage techniques.*

* [Fractal](https://github.com/thephpleague/fractal) ⭐ 3,553 | 🐛 54 | 🌐 PHP | 📅 2025-12-16 - A library for converting complex data structures to JSON output.
* [Serializer](https://github.com/schmittjoh/serializer) ⭐ 2,351 | 🐛 171 | 🌐 PHP | 📅 2025-12-03 - A library for serializing and de-serializing data.
* [JsonMapper](https://github.com/cweiske/jsonmapper) ⭐ 1,570 | 🐛 10 | 🌐 PHP | 📅 2024-09-08 - A library that maps nested JSON structures onto PHP classes.
* [JSON Machine](https://github.com/halaxa/json-machine) ⭐ 1,289 | 🐛 5 | 🌐 PHP | 📅 2025-12-14 - Provides iteration over huge JSONs using simple `foreach`
* [Knapsack](https://github.com/DusanKasan/Knapsack) ⭐ 535 | 🐛 15 | 🌐 PHP | 📅 2024-05-09 - Collection library inspired by Clojure's sequences.
* [PINQ](https://github.com/TimeToogo/Pinq) ⚠️ Archived - A PHP library based on .NET's LINQ (Language Integrated Query).
* [YaLinqo](https://github.com/Athari/YaLinqo) ⭐ 451 | 🐛 13 | 🌐 PHP | 📅 2025-10-19 - Yet Another LINQ to Objects for PHP.
* [msgpack.php](https://github.com/rybakit/msgpack.php) ⭐ 406 | 🐛 1 | 🌐 PHP | 📅 2025-12-18 - A pure PHP implementation of the [MessagePack](https://msgpack.org/) serialization format.
* [Ginq](https://github.com/akanehara/ginq) ⭐ 192 | 🐛 6 | 🌐 PHP | 📅 2022-06-30 - Another PHP library based on .NET's LINQ.
* [CakePHP Collection](https://github.com/cakephp/collection) ⭐ 89 | 🐛 0 | 🌐 PHP | 📅 2026-01-15 - A simple collections library.
* [Laminas Serializer](https://github.com/laminas/laminas-serializer) ⭐ 34 | 🐛 7 | 🌐 PHP | 📅 2026-02-09 - Another library for serialising and de-serialising data.

### Notifications

*Libraries for working with notification software.*

* [JoliNotif](https://github.com/jolicode/JoliNotif) ⭐ 1,437 | 🐛 1 | 🌐 PHP | 📅 2026-01-28 - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc)
* [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) ⭐ 1,182 | 🐛 31 | 🌐 PHP | 📅 2023-09-05 - A standalone library for device push notifications.
* [Notificato](https://github.com/mac-cain13/notificato) ⚠️ Archived - A library for handling push notifications.
* [Notificator](https://github.com/namshi/notificator) ⭐ 192 | 🐛 0 | 🌐 PHP | 📅 2018-06-05 - A lightweight notification library.
* [Php-pushwoosh](https://github.com/gomoob/php-pushwoosh) ⭐ 67 | 🐛 18 | 🌐 PHP | 📅 2020-10-06 - A PHP Library to easily send push notifications with the Pushwoosh REST Web Services.

### Deployment

*Libraries for project deployment.*

* [Deployer](https://github.com/deployphp/deployer) ⭐ 10,999 | 🐛 7 | 🌐 PHP | 📅 2026-02-05 - A deployment tool.
* [Rocketeer](https://github.com/rocketeers/rocketeer) ⚠️ Archived - A fast and easy deployer for the PHP world.
* [Envoy](https://github.com/laravel/envoy) ⭐ 1,612 | 🐛 1 | 🌐 PHP | 📅 2025-07-30 - A tool to run SSH tasks with PHP.

### Internationalisation and Localisation

*Libraries for Internationalization (I18n) and Localization (L10n).*

* [Aura.Intl](https://github.com/auraphp/Aura.Intl) ⭐ 89 | 🐛 0 | 🌐 PHP | 📅 2022-12-12 - Provides internationalization (I18N) tools, specifically package-oriented per-locale message translation.
* [CakePHP I18n](https://github.com/cakephp/i18n) ⭐ 28 | 🐛 0 | 🌐 PHP | 📅 2026-01-15 - Message translation and localization for dates and numbers.

### Serverless

*Libraries and tools to help build serverless web applications.*

* [Bref](https://bref.sh/) - Serverless PHP on AWS Lambda.
* [OpenWhisk](https://openwhisk.apache.org/) - An open-source serverless cloud platform.
* [Serverless Framework](https://www.serverless.com/framework) - An open-source framework for building serverless applications.
* [Laravel Vapor](https://vapor.laravel.com/) - A serverless deployment platform for Laravel, powered by AWS.

## Configuration

*Libraries and tools for configuration.*

* [PHP Dotenv](https://github.com/vlucas/phpdotenv) ⭐ 13,514 | 🐛 17 | 🌐 PHP | 📅 2025-12-27 - Parse and load environment variables from `.env` files.
* [Symfony Dotenv](https://github.com/symfony/dotenv) ⭐ 3,801 | 🐛 0 | 🌐 PHP | 📅 2025-12-07- Parse and load environment variables from `.env` files.
* [Yo! Symfony TOML](https://github.com/yosymfony/toml) ⭐ 209 | 🐛 8 | 🌐 PHP | 📅 2020-08-08 - A PHP parser for [TOML](https://github.com/toml-lang/toml) ⭐ 20,345 | 🐛 14 | 📅 2025-12-24.

### LLMs

*Libraries for working with Large Language Models.*

* [OpenAI Client](https://github.com/openai-php/client) ⭐ 5,716 | 🐛 26 | 🌐 PHP | 📅 2026-02-09 - OpenAI PHP is a supercharged community-maintained PHP API client that allows you to interact with OpenAI API.
* [OpenAI Client for Laravel](https://github.com/openai-php/laravel) ⭐ 3,709 | 🐛 14 | 🌐 PHP | 📅 2025-12-15 - OpenAI PHP for Laravel is a supercharged PHP API client that allows you to interact with OpenAI API.
* [LLPhant](https://github.com/LLPhant/LLPhant) ⭐ 1,419 | 🐛 33 | 🌐 PHP | 📅 2026-02-09 - A comprehensive PHP Generative AI Framework using OpenAI GPT 4. Inspired by Langchain.
* [Instructor for PHP](https://github.com/cognesy/instructor-php) ⭐ 302 | 🐛 2 | 🌐 PHP | 📅 2026-02-09 - Structured data outputs with LLMs, in PHP.
* [PHP Mistral AI SDK](https://github.com/SoftCreatR/php-mistral-ai-sdk) ⭐ 15 | 🐛 0 | 🌐 PHP | 📅 2025-11-21 - A powerful and easy-to-use PHP SDK for the Mistral AI API, allowing seamless integration of advanced AI-powered features into your PHP projects.

### Third Party APIs

*Libraries for accessing third party APIs.*

* [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) ⭐ 6,178 | 🐛 33 | 🌐 PHP | 📅 2026-02-09 - The official PHP AWS SDK library.
* [Stripe](https://github.com/stripe/stripe-php) ⭐ 3,980 | 🐛 15 | 🌐 PHP | 📅 2026-02-04 - The official Stripe PHP library.
* [Github](https://github.com/KnpLabs/php-github-api) ⭐ 2,197 | 🐛 49 | 🌐 PHP | 📅 2025-11-24 - A library to interface with the Github API.
* [Twilio](https://github.com/twilio/twilio-php) ⭐ 1,634 | 🐛 40 | 🌐 PHP | 📅 2026-02-05 - The official Twilio PHP REST API.
* [Mailgun](https://github.com/mailgun/mailgun-php) ⭐ 1,133 | 🐛 8 | 🌐 PHP | 📅 2026-01-29 The official Mailgun PHP API.
* [Square](https://github.com/square/connect-php-sdk) ⚠️ Archived - The official Square PHP SDK for payments and other Square APIs.
* [AsyncAWS](https://async-aws.com/) - An unofficial asynchronous PHP AWS SDK.
* [Campaign Monitor](https://campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.

### Extensions

*Libraries to help build PHP extensions.*

* [PHP CPP](https://www.php-cpp.com/) - A C++ library for developing PHP extensions.
* [Zephir](https://github.com/zephir-lang/zephir) ⭐ 3,365 | 🐛 119 | 🌐 PHP | 📅 2026-02-04 - A compiled language between PHP and C++ for developing PHP extensions.

### Miscellaneous

*Useful libraries or utilities that don't fit into the categories above.*

* [Annotations](https://github.com/doctrine/annotations) ⭐ 6,751 | 🐛 26 | 🌐 PHP | 📅 2025-12-11 - An annotation library (part of Doctrine).
* [BotMan](https://github.com/botman/botman) ⭐ 6,170 | 🐛 10 | 🌐 PHP | 📅 2025-09-26 - A framework agnostic PHP library to build cross-platform chatbots.
* [Safe](https://github.com/thecodingmachine/safe) ⭐ 2,480 | 🐛 31 | 🌐 PHP | 📅 2026-02-04 - All PHP functions, rewritten to throw exceptions instead of returning false.
* [Hprose-PHP](https://github.com/hprose/hprose-php) ⭐ 2,068 | 🐛 42 | 🌐 PHP | 📅 2024-02-06 - A cross-language RPC.
* [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) ⭐ 1,582 | 🐛 35 | 🌐 PHP | 📅 2020-06-09 - A pagination library.
* [Ganesha](https://github.com/ackintosh/ganesha) ⭐ 658 | 🐛 14 | 🌐 PHP | 📅 2025-08-26 - A PHP implementation of Circuit Breaker pattern.
* [Laravel Serializable Closure](https://github.com/laravel/serializable-closure) ⭐ 597 | 🐛 5 | 🌐 PHP | 📅 2026-02-04 - A library that allows Closures to be serialized.
* [ClassPreloader](https://github.com/ClassPreloader/ClassPreloader) ⭐ 376 | 🐛 0 | 🌐 PHP | 📅 2025-01-13 - A library for optimizing autoloading.
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) ⭐ 366 | 🐛 5 | 🌐 PHP | 📅 2024-04-13 - Helper for Google's noCAPTCHA (reCAPTCHA).

# Software

*Software for creating a development environment.*

### PHP Installation

*Tools to help install and manage PHP on your computer.*

* [PHP Brew](https://github.com/phpbrew/phpbrew) ⭐ 5,522 | 🐛 99 | 🌐 Makefile | 📅 2026-01-28 - A PHP version manager and installer.
* [Static PHP CLI](https://github.com/crazywhalecc/static-php-cli) ⭐ 1,817 | 🐛 34 | 🌐 PHP | 📅 2026-02-06 - Build or [download](https://dl.static-php.dev/static-php-cli/) static versions of PHP CLI and FPM.
* [PHP Build](https://github.com/php-build/php-build) ⭐ 1,043 | 🐛 33 | 🌐 Shell | 📅 2026-02-09 - Another PHP version installer.
* [Brew PHP Switcher](https://github.com/philcook/brew-php-switcher) ⭐ 1,005 | 🐛 18 | 🌐 Shell | 📅 2025-11-25 - Brew PHP switcher.
* [HomeBrew](https://brew.sh/) - A package manager for OSX.

### Development Environment

*Software and tools for creating and sharing a development environment.*

* [Docker PHP Extension Installer](https://github.com/mlocati/docker-php-extension-installer) ⭐ 4,853 | 🐛 11 | 🌐 Shell | 📅 2026-02-09 - Easily install PHP extensions in Docker containers.
* [Expose](https://github.com/exposedev/expose) ⭐ 4,521 | 🐛 23 | 🌐 PHP | 📅 2026-01-26 - An open-source PHP tunneling service.
* [DDEV](https://github.com/ddev/ddev) ⭐ 3,485 | 🐛 147 | 🌐 Go | 📅 2026-02-10 - a local web development environment system for PHP.
* [Takeout](https://github.com/tighten/takeout) ⭐ 1,650 | 🐛 4 | 🌐 PHP | 📅 2026-01-29 - A Docker-based development-only dependency manager.
* [Docksal](https://github.com/docksal/docksal) ⭐ 713 | 🐛 176 | 🌐 Shell | 📅 2025-12-19 - Unified, Docker :whale: powered web development environments for macOS, Windows, and Linux.
* [Ansible](https://www.redhat.com/en/ansible-collaborative) - A radically simple orchestration framework.
* [Docker](https://www.docker.com/) - A containerization platform.
* [Lando](https://lando.dev/) - Push-button development environments.
* [Laravel Homestead](https://laravel.com/docs/master/homestead) - A local development environment for Laravel.
* [Laravel Herd](https://herd.laravel.com/windows) - A one click PHP development environment for macOS and Windows.
* [Laradock](http://laradock.io/) - A full PHP development environment based on Docker.
* [PHPMon](https://phpmon.app/) - A macOS menu bar app for managing PHP installations (works with [Laravel Valet](https://laravel.com/docs/master/valet)).
* [Puppet](https://www.puppet.com) - A server automation framework and application.
* [Vagrant](https://www.vagrantup.com/) - A portable development environment utility.

### Virtual Machines

*Alternative PHP virtual machines.*

* [HHVM](https://github.com/facebook/hhvm) ⭐ 18,605 | 🐛 517 | 🌐 C++ | 📅 2026-02-10 - A Virtual Machine, Runtime and JIT for PHP by Facebook.
* [PeachPie](https://github.com/peachpiecompiler/peachpie) ⭐ 2,469 | 🐛 89 | 🌐 C# | 📅 2026-01-22 - PHP compiler and runtime for .NET and .NET Core.
* [Hack](https://hacklang.org/) - A programming language for HHVM.

### Text Editors and IDEs

*Text Editors and Integrated Development Environments (IDE) with support for PHP.*

* [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
* [Apache NetBeans](https://netbeans.apache.org/front/main/index.html) - An IDE with support for PHP and HTML5.
* [PhpEd](https://www.nusphere.com/products/phped.htm) - An IDE with professional commercial debugger.
* [PhpStorm](https://www.jetbrains.com/phpstorm/) - A commercial PHP IDE.
* [VS Code](https://code.visualstudio.com/) - An open source code editor.

### Web Applications

*Web-based applications and tools.*

* [Cachet](https://github.com/cachethq/cachet) ⭐ 14,904 | 🐛 37 | 🌐 PHP | 📅 2026-01-08 - The open source status page system.
* [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) ⭐ 7,792 | 🐛 908 | 🌐 PHP | 📅 2026-02-08 - A web interface for MySQL/MariaDB.
* [MailCatcher](https://github.com/sj26/mailcatcher) ⭐ 6,728 | 🐛 46 | 🌐 Ruby | 📅 2024-05-25 - A web tool for capturing and viewing emails.
* [Lychee](https://github.com/electerious/Lychee) ⭐ 6,367 | 🐛 0 | 🌐 PHP | 📅 2022-01-08 - An easy to use and great looking photo-management-system.
* [phpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin) ⭐ 3,187 | 🐛 12 | 🌐 PHP | 📅 2025-12-22 - A simple web interface to manage [Redis](https://redis.io/) databases.
* [PHP Queue](https://github.com/CoderKungfu/php-queue) ⭐ 665 | 🐛 6 | 🌐 PHP | 📅 2025-12-04 - An application for managing queueing backends.
* [3V4L](https://3v4l.org/) - An online PHP & HHVM shell.
* [Adminer](https://www.adminer.org/en/) - Database management in a single PHP file.
* [DBV](https://github.com/victorstanciu/dbv) - A database version control application.
* [PHPSandbox](https://phpsandbox.io) - An online IDE for PHP in the browser.

### Infrastructure

*Infrastructure for providing PHP applications and services.*

* [RoadRunner](https://github.com/roadrunner-server/roadrunner) ⭐ 8,387 | 🐛 88 | 🌐 Go | 📅 2026-02-05 - High-performance PHP application server, load-balancer and process manager.
* [php-pm](https://github.com/php-pm/php-pm) ⭐ 6,569 | 🐛 33 | 🌐 PHP | 📅 2023-12-08 - A process manager, supercharger and load balancer for PHP applications.
* [appserver.io](https://github.com/appserver-io/appserver) ⭐ 963 | 🐛 90 | 🌐 JavaScript | 📅 2023-04-15 - A multithreaded application server for PHP, written in PHP.

# Resources

Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

### PHP Websites

*Useful PHP-related websites.*

* [Nomad PHP](https://nomadphp.com/) - A online PHP learning resource.
* [Laravel News](https://laravel-news.com/) - The official Laravel blog.
* [PHP Annotated Monthly](https://blog.jetbrains.com/phpstorm/tag/php-annotated-monthly/) - A monthly digest of PHP news.
* [PHP FIG](https://www.php-fig.org/) - The PHP Framework Interoperability Group.
* [PHP Package Development Standards](http://php-pds.com) - Package development standards for PHP.
* [PHP School](https://www.phpschool.io/) - Open Source Learning for PHP.
* [PHP The Right Way](https://phptherightway.com/) - A PHP best practice quick reference guide.
* [PHP UG](https://php.ug) - A website to help people locate their nearest PHP user group (UG).
* [PHP Watch](https://php.watch/) - PHP articles, news, upcoming changes, RFCs and more.
* [Unit Testing Tips](https://testing-tips.sarvendev.com/) - Unit Testing Tips by examples in PHP.

### PHP Books

*Fantastic PHP-related books.*

* [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles.
* [Functional Programming in PHP](https://www.functionalphp.com/) - This book will show you how to leverage these new PHP5.3+ features by understanding functional programming principles
* [Grumpy PHPUnit](https://leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
* [Mastering Object-Orientated PHP](https://masteringobjectorientedphp.com/) - A book about object-orientated PHP by Brandon Savage.
* [PHP Cookbook](https://www.oreilly.com/library/view/php-cookbook/9781098121310/) - This cookbook provides code recipes to help you resolve a variety of coding issues.
* [Modernizing Legacy Applications in PHP](https://leanpub.com/mlaphp) - A book about modernizing legacy PHP applications by Paul M. Jones.
* [Scaling PHP Applications](https://www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
* [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
* [Signaling PHP](https://leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
* [XML Parsing with PHP](https://www.phparch.com/books/xml-parsing-with-php/) - This book covers parsing and validating XML documents, leveraging XPath expressions, and working with namespaces as well as how to create and modify XML files programmatically.

### PHP Videos

*Fantastic PHP-related videos.*

* [Laracasts](https://laracasts.com) - Screencasts about Laravel, Vue JS and more.
* [Laravel YouTube Channel](https://www.youtube.com/channel/UCfO2GiQwb-cwJTb1CuRSkwg) - The official Laravel YouTube channel.
* [Program With Gio](https://www.youtube.com/playlist?list=PLr3d3QYzkw2xabQRUpcZ_IBk9W50M9pe-) - PHP 8 course by Gio.
* [Programming with Anthony](https://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
* [SymfonyCasts](https://symfonycasts.com/) - Screencasts and tutorials about PHP and Symfony.

### PHP Conferences

*PHP conferences.*

* [Laracon EU](https://www.youtube.com/@LaraconEU) - Laracon EU is a 2-day event for people who are interested in learning Laravel and related technologies, or who want to share their knowledge with others.
* [PHP\[TEK\]](https://phptek.io/) - The longest-running web developer conference in the United States that has a focus on the PHP programming language.
* [PHP UK Conference](https://www.youtube.com/user/phpukconference/videos) - A collection of videos from the PHP UK Conference.

### PHP Podcasts

*Podcasts with a focus on PHP topics.*

* [Laravel News Podcast](https://podcast.laravel-news.com/) - The Laravel News Podcast brings you all the latest news and events related to the Laravel PHP Framework.
* [Mostly Technical](https://mostlytechnical.com/) - Hosted by Ian Landsman and Aaron Francis, Mostly Technical is a lively discussion on Laravel, business, and an eclectic mix of related topics.
* [No Compromises](https://show.nocompromises.io/) - Two seasoned salty programming veterans talk best practices based on years of working with Laravel SaaS teams.
* [North Meets South Web Podcast](https://www.northmeetssouth.audio/) - Jacob Bennett and Michael Dyrynda conquer a 14.5 hour time difference to talk about life as web developers.
* [Over Engineered](https://overengineered.fm/) - A podcast in mini-series where we explore unimportant programming questions in extreme detail.
* [PHP Internals News](https://phpinternals.news) - A podcast about PHP internals.
* [PHP Town Hall](https://phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
* [php\[podcast\] episodes from php\[architect\]](https://www.phparch.com/podcast/) - The official podcast of php\[architect] the industry's leading tech magazine and publisher focused on PHP and web development.
* [PHPUgly](https://www.phpugly.com/) - The ramblings of a few overworked PHP Developers.
* [The Laracasts Snippet](https://laracasts.simplecast.com) - The Laracasts snippet, each episode, offers a single thought on some aspect of web development.
* [The Laravel Podcast](https://laravelpodcast.com/) - Laravel and PHP development news and discussion.
* [The PHP Roundtable](https://phproundtable.com/) - The PHP Roundtable is a casual gathering of developers discussing topics that PHP nerds care about.

### PHP Newsletters

*PHP-related news directly to your inbox.*

* [PHP Weekly](https://www.phpweekly.com/) - A weekly newsletter about PHP.

### PHP Reading

*PHP-related reading materials.*

* [php\[architect\]](https://www.phparch.com/magazine/) - A monthly magazine dedicated to PHP.

### PHP Internals Reading

*Reading materials related to the PHP internals or performance.*

* [PHP RFCs](https://wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
* [Externals](https://externals.io/) - PHP internal discussions.
* [PHP RFC Watch](https://github.com/beberlei/php-rfc-watch) ⭐ 127 | 🐛 19 | 🌐 HTML | 📅 2026-01-28 - Watch the latest PHP [RFCs](https://wiki.php.net/rfc).
* [PHP Internals Book](https://www.phpinternalsbook.com/) - An online book about PHP internals, written by three core developers.
