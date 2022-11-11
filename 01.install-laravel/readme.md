<pre>
Microsoft Windows [Version 10.0.22621.819]
(c) Microsoft Corporation. All rights reserved.

C:\>composer global require laravel/installer
Changed current directory to C:/Users/codew/AppData/Roaming/Composer
Info from https://repo.packagist.org: #StandWithUkraine
Using version ^4.2 for laravel/installer
./composer.json has been updated
Running composer update laravel/installer
Loading composer repositories with package information
Updating dependencies
Nothing to modify in lock file
Installing dependencies from lock file (including require-dev)
Nothing to install, update or remove
Generating autoload files
11 packages you are using are looking for funding.
Use the `composer fund` command to find out more!

C:\>laravel new laravel

   _                               _
  | |                             | |
  | |     __ _ _ __ __ ___   _____| |
  | |    / _` | '__/ _` \ \ / / _ \ |
  | |___| (_| | | | (_| |\ V /  __/ |
  |______\__,_|_|  \__,_| \_/ \___|_|

    Creating a "laravel/laravel" project at "./laravel"
    Installing laravel/laravel (v9.3.10)
  - Downloading laravel/laravel (v9.3.10)
      - Installing laravel/laravel (v9.3.10): Extracting archive
    Created project in C:\/laravel
> @php -r "file_exists('.env') || copy('.env.example', '.env');"
    Loading composer repositories with package information
    Updating dependencies
Lock file operations: 107 installs, 0 updates, 0 removals
  - Locking brick/math (0.10.2)
  - Locking dflydev/dot-access-data (v3.0.2)
  - Locking doctrine/inflector (2.0.6)
  - Locking doctrine/instantiator (1.4.1)
  - Locking doctrine/lexer (1.2.3)
  - Locking dragonmantank/cron-expression (v3.3.2)
  - Locking egulias/email-validator (3.2.1)
  - Locking fakerphp/faker (v1.20.0)
  - Locking filp/whoops (2.14.6)
  - Locking fruitcake/php-cors (v1.2.0)
  - Locking graham-campbell/result-type (v1.1.0)
  - Locking guzzlehttp/guzzle (7.5.0)
  - Locking guzzlehttp/promises (1.5.2)
  - Locking guzzlehttp/psr7 (2.4.3)
  - Locking hamcrest/hamcrest-php (v2.0.1)
  - Locking laravel/framework (v9.39.0)
  - Locking laravel/pint (v1.2.0)
  - Locking laravel/sail (v1.16.2)
  - Locking laravel/sanctum (v3.0.1)
  - Locking laravel/serializable-closure (v1.2.2)
  - Locking laravel/tinker (v2.7.2)
  - Locking league/commonmark (2.3.7)
  - Locking league/config (v1.1.1)
  - Locking league/flysystem (3.10.2)
  - Locking league/mime-type-detection (1.11.0)
  - Locking mockery/mockery (1.5.1)
  - Locking monolog/monolog (2.8.0)
  - Locking myclabs/deep-copy (1.11.0)
  - Locking nesbot/carbon (2.63.0)
  - Locking nette/schema (v1.2.2)
  - Locking nette/utils (v3.2.8)
  - Locking nikic/php-parser (v4.15.1)
  - Locking nunomaduro/collision (v6.3.1)
  - Locking nunomaduro/termwind (v1.14.2)
  - Locking phar-io/manifest (2.0.3)
  - Locking phar-io/version (3.2.1)
  - Locking phpoption/phpoption (1.9.0)
  - Locking phpunit/php-code-coverage (9.2.18)
  - Locking phpunit/php-file-iterator (3.0.6)
  - Locking phpunit/php-invoker (3.1.1)
  - Locking phpunit/php-text-template (2.0.4)
  - Locking phpunit/php-timer (5.0.3)
  - Locking phpunit/phpunit (9.5.26)
  - Locking psr/container (2.0.2)
  - Locking psr/event-dispatcher (1.0.0)
  - Locking psr/http-client (1.0.1)
  - Locking psr/http-factory (1.0.1)
  - Locking psr/http-message (1.0.1)
  - Locking psr/log (3.0.0)
  - Locking psr/simple-cache (3.0.0)
  - Locking psy/psysh (v0.11.9)
  - Locking ralouphie/getallheaders (3.0.3)
  - Locking ramsey/collection (1.2.2)
  - Locking ramsey/uuid (4.6.0)
  - Locking sebastian/cli-parser (1.0.1)
  - Locking sebastian/code-unit (1.0.8)
  - Locking sebastian/code-unit-reverse-lookup (2.0.3)
  - Locking sebastian/comparator (4.0.8)
  - Locking sebastian/complexity (2.0.2)
  - Locking sebastian/diff (4.0.4)
  - Locking sebastian/environment (5.1.4)
  - Locking sebastian/exporter (4.0.5)
  - Locking sebastian/global-state (5.0.5)
  - Locking sebastian/lines-of-code (1.0.3)
  - Locking sebastian/object-enumerator (4.0.4)
  - Locking sebastian/object-reflector (2.0.4)
  - Locking sebastian/recursion-context (4.0.4)
  - Locking sebastian/resource-operations (3.0.3)
  - Locking sebastian/type (3.2.0)
  - Locking sebastian/version (3.0.2)
  - Locking spatie/backtrace (1.2.1)
  - Locking spatie/flare-client-php (1.3.0)
  - Locking spatie/ignition (1.4.1)
  - Locking spatie/laravel-ignition (1.6.1)
  - Locking symfony/console (v6.1.7)
  - Locking symfony/css-selector (v6.1.3)
  - Locking symfony/deprecation-contracts (v3.1.1)
  - Locking symfony/error-handler (v6.1.7)
  - Locking symfony/event-dispatcher (v6.1.0)
  - Locking symfony/event-dispatcher-contracts (v3.1.1)
  - Locking symfony/finder (v6.1.3)
  - Locking symfony/http-foundation (v6.1.7)
  - Locking symfony/http-kernel (v6.1.7)
  - Locking symfony/mailer (v6.1.7)
  - Locking symfony/mime (v6.1.7)
  - Locking symfony/polyfill-ctype (v1.27.0)
  - Locking symfony/polyfill-intl-grapheme (v1.27.0)
  - Locking symfony/polyfill-intl-idn (v1.27.0)
  - Locking symfony/polyfill-intl-normalizer (v1.27.0)
  - Locking symfony/polyfill-mbstring (v1.27.0)
  - Locking symfony/polyfill-php72 (v1.27.0)
  - Locking symfony/polyfill-php80 (v1.27.0)
  - Locking symfony/polyfill-php81 (v1.27.0)
  - Locking symfony/polyfill-uuid (v1.27.0)
  - Locking symfony/process (v6.1.3)
  - Locking symfony/routing (v6.1.7)
  - Locking symfony/service-contracts (v3.1.1)
  - Locking symfony/string (v6.1.7)
  - Locking symfony/translation (v6.1.6)
  - Locking symfony/translation-contracts (v3.1.1)
  - Locking symfony/uid (v6.1.5)
  - Locking symfony/var-dumper (v6.1.6)
  - Locking theseer/tokenizer (1.2.1)
  - Locking tijsverkoyen/css-to-inline-styles (2.2.5)
  - Locking vlucas/phpdotenv (v5.5.0)
  - Locking voku/portable-ascii (2.0.1)
  - Locking webmozart/assert (1.11.0)
Writing lock file
Installing dependencies from lock file (including require-dev)
Package operations: 107 installs, 0 updates, 0 removals
  - Downloading symfony/polyfill-ctype (v1.27.0)
  - Downloading symfony/deprecation-contracts (v3.1.1)
  - Downloading psr/container (2.0.2)
  - Downloading symfony/polyfill-mbstring (v1.27.0)
  - Downloading symfony/http-foundation (v6.1.7)
  - Downloading fruitcake/php-cors (v1.2.0)
  - Downloading laravel/pint (v1.2.0)
  - Downloading voku/portable-ascii (2.0.1)
  - Downloading symfony/polyfill-php80 (v1.27.0)
      - Downloading symfony/css-selector (v6.1.3)
      - Downloading symfony/var-dumper (v6.1.6)
  - Downloading symfony/polyfill-uuid (v1.27.0)
  - Downloading symfony/uid (v6.1.5)
  - Downloading symfony/routing (v6.1.7)
  - Downloading symfony/process (v6.1.3)
  - Downloading symfony/polyfill-php72 (v1.27.0)
  - Downloading symfony/polyfill-intl-normalizer (v1.27.0)
  - Downloading symfony/polyfill-intl-idn (v1.27.0)
  - Downloading symfony/mime (v6.1.7)
  - Downloading symfony/service-contracts (v3.1.1)
  - Downloading symfony/event-dispatcher-contracts (v3.1.1)
  - Downloading symfony/event-dispatcher (v6.1.0)
  - Downloading psr/log (3.0.0)
  - Downloading egulias/email-validator (3.2.1)
  - Downloading symfony/mailer (v6.1.7)
  - Downloading symfony/error-handler (v6.1.7)
  - Downloading symfony/http-kernel (v6.1.7)
  - Downloading symfony/finder (v6.1.3)
  - Downloading symfony/polyfill-intl-grapheme (v1.27.0)
  - Downloading symfony/string (v6.1.7)
  - Downloading symfony/console (v6.1.7)
  - Downloading symfony/polyfill-php81 (v1.27.0)
  - Downloading brick/math (0.10.2)
  - Downloading ramsey/uuid (4.6.0)
  - Downloading psr/simple-cache (3.0.0)
  - Downloading nunomaduro/termwind (v1.14.2)
  - Downloading symfony/translation-contracts (v3.1.1)
  - Downloading symfony/translation (v6.1.6)
  - Downloading nesbot/carbon (2.63.0)
  - Downloading league/flysystem (3.10.2)
  - Downloading league/commonmark (2.3.7)
  - Downloading laravel/framework (v9.39.0)
  - Downloading laravel/sanctum (v3.0.1)
  - Downloading psy/psysh (v0.11.9)
  - Downloading nunomaduro/collision (v6.3.1)
      - Downloading spatie/backtrace (1.2.1)
  - Downloading spatie/flare-client-php (1.3.0)
  - Downloading spatie/ignition (1.4.1)
  - Downloading spatie/laravel-ignition (1.6.1)
  0/49 [>---------------------------]   0%
  5/49 [==>-------------------------]  10%
 10/49 [=====>----------------------]  20%
 17/49 [=========>------------------]  34%
 21/49 [============>---------------]  42%
 25/49 [==============>-------------]  51%
 31/49 [=================>----------]  63%
 35/49 [====================>-------]  71%
 40/49 [======================>-----]  81%
 45/49 [=========================>--]  91%
 48/49 [===========================>]  97%
 49/49 [============================] 100%
  - Installing doctrine/inflector (2.0.6): Extracting archive
      - Installing doctrine/lexer (1.2.3): Extracting archive
  - Installing symfony/polyfill-ctype (v1.27.0): Extracting archive
  - Installing webmozart/assert (1.11.0): Extracting archive
  - Installing dragonmantank/cron-expression (v3.3.2): Extracting archive
  - Installing symfony/deprecation-contracts (v3.1.1): Extracting archive
  - Installing psr/container (2.0.2): Extracting archive
  - Installing fakerphp/faker (v1.20.0): Extracting archive
      - Installing symfony/polyfill-mbstring (v1.27.0): Extracting archive
  - Installing symfony/http-foundation (v6.1.7): Extracting archive
      - Installing fruitcake/php-cors (v1.2.0): Extracting archive
  - Installing psr/http-message (1.0.1): Extracting archive
  - Installing psr/http-client (1.0.1): Extracting archive
  - Installing ralouphie/getallheaders (3.0.3): Extracting archive
  - Installing psr/http-factory (1.0.1): Extracting archive
  - Installing guzzlehttp/psr7 (2.4.3): Extracting archive
  - Installing guzzlehttp/promises (1.5.2): Extracting archive
  - Installing guzzlehttp/guzzle (7.5.0): Extracting archive
      - Installing laravel/pint (v1.2.0): Extracting archive
      - Installing voku/portable-ascii (2.0.1): Extracting archive
      - Installing symfony/polyfill-php80 (v1.27.0): Extracting archive
  - Installing phpoption/phpoption (1.9.0): Extracting archive
  - Installing graham-campbell/result-type (v1.1.0): Extracting archive
  - Installing vlucas/phpdotenv (v5.5.0): Extracting archive
  - Installing symfony/css-selector (v6.1.3): Extracting archive
      - Installing tijsverkoyen/css-to-inline-styles (2.2.5): Extracting archive
  - Installing symfony/var-dumper (v6.1.6): Extracting archive
      - Installing symfony/polyfill-uuid (v1.27.0): Extracting archive
  - Installing symfony/uid (v6.1.5): Extracting archive
  - Installing symfony/routing (v6.1.7): Extracting archive
  - Installing symfony/process (v6.1.3): Extracting archive
      - Installing symfony/polyfill-php72 (v1.27.0): Extracting archive
  - Installing symfony/polyfill-intl-normalizer (v1.27.0): Extracting archive
  - Installing symfony/polyfill-intl-idn (v1.27.0): Extracting archive
  - Installing symfony/mime (v6.1.7): Extracting archive
  - Installing symfony/service-contracts (v3.1.1): Extracting archive
      - Installing psr/event-dispatcher (1.0.0): Extracting archive
  - Installing symfony/event-dispatcher-contracts (v3.1.1): Extracting archive
  - Installing symfony/event-dispatcher (v6.1.0): Extracting archive
  - Installing psr/log (3.0.0): Extracting archive
  - Installing egulias/email-validator (3.2.1): Extracting archive
      - Installing symfony/mailer (v6.1.7): Extracting archive
  - Installing symfony/error-handler (v6.1.7): Extracting archive
  - Installing symfony/http-kernel (v6.1.7): Extracting archive
      - Installing symfony/finder (v6.1.3): Extracting archive
  - Installing symfony/polyfill-intl-grapheme (v1.27.0): Extracting archive
  - Installing symfony/string (v6.1.7): Extracting archive
  - Installing symfony/console (v6.1.7): Extracting archive
      - Installing symfony/polyfill-php81 (v1.27.0): Extracting archive
  - Installing ramsey/collection (1.2.2): Extracting archive
  - Installing brick/math (0.10.2): Extracting archive
      - Installing ramsey/uuid (4.6.0): Extracting archive
      - Installing psr/simple-cache (3.0.0): Extracting archive
  - Installing nunomaduro/termwind (v1.14.2): Extracting archive
  - Installing symfony/translation-contracts (v3.1.1): Extracting archive
  - Installing symfony/translation (v6.1.6): Extracting archive
      - Installing nesbot/carbon (2.63.0): Extracting archive
      - Installing monolog/monolog (2.8.0): Extracting archive
  - Installing league/mime-type-detection (1.11.0): Extracting archive
  - Installing league/flysystem (3.10.2): Extracting archive
      - Installing nette/utils (v3.2.8): Extracting archive
  - Installing nette/schema (v1.2.2): Extracting archive
  - Installing dflydev/dot-access-data (v3.0.2): Extracting archive
  - Installing league/config (v1.1.1): Extracting archive
  - Installing league/commonmark (2.3.7): Extracting archive
      - Installing laravel/serializable-closure (v1.2.2): Extracting archive
  - Installing laravel/framework (v9.39.0): Extracting archive
      - Installing laravel/sail (v1.16.2): Extracting archive
  - Installing laravel/sanctum (v3.0.1): Extracting archive
  - Installing nikic/php-parser (v4.15.1): Extracting archive
      - Installing psy/psysh (v0.11.9): Extracting archive
      - Installing laravel/tinker (v2.7.2): Extracting archive
  - Installing hamcrest/hamcrest-php (v2.0.1): Extracting archive
      - Installing mockery/mockery (1.5.1): Extracting archive
      - Installing filp/whoops (2.14.6): Extracting archive
      - Installing nunomaduro/collision (v6.3.1): Extracting archive
  - Installing sebastian/version (3.0.2): Extracting archive
  - Installing sebastian/type (3.2.0): Extracting archive
  - Installing sebastian/resource-operations (3.0.3): Extracting archive
      - Installing sebastian/recursion-context (4.0.4): Extracting archive
      - Installing sebastian/object-reflector (2.0.4): Extracting archive
  - Installing sebastian/object-enumerator (4.0.4): Extracting archive
  - Installing sebastian/global-state (5.0.5): Extracting archive
  - Installing sebastian/exporter (4.0.5): Extracting archive
  - Installing sebastian/environment (5.1.4): Extracting archive
  - Installing sebastian/diff (4.0.4): Extracting archive
  - Installing sebastian/comparator (4.0.8): Extracting archive
  - Installing sebastian/code-unit (1.0.8): Extracting archive
  - Installing sebastian/cli-parser (1.0.1): Extracting archive
  - Installing phpunit/php-timer (5.0.3): Extracting archive
      - Installing phpunit/php-text-template (2.0.4): Extracting archive
      - Installing phpunit/php-invoker (3.1.1): Extracting archive
  - Installing phpunit/php-file-iterator (3.0.6): Extracting archive
  - Installing theseer/tokenizer (1.2.1): Extracting archive
  - Installing sebastian/lines-of-code (1.0.3): Extracting archive
  - Installing sebastian/complexity (2.0.2): Extracting archive
  - Installing sebastian/code-unit-reverse-lookup (2.0.3): Extracting archive
  - Installing phpunit/php-code-coverage (9.2.18): Extracting archive
      - Installing phar-io/version (3.2.1): Extracting archive
  - Installing phar-io/manifest (2.0.3): Extracting archive
      - Installing myclabs/deep-copy (1.11.0): Extracting archive
  - Installing doctrine/instantiator (1.4.1): Extracting archive
  - Installing phpunit/phpunit (9.5.26): Extracting archive
      - Installing spatie/backtrace (1.2.1): Extracting archive
  - Installing spatie/flare-client-php (1.3.0): Extracting archive
  - Installing spatie/ignition (1.4.1): Extracting archive
      - Installing spatie/laravel-ignition (1.6.1): Extracting archive
      0/97 [>---------------------------]   0%
 10/97 [==>-------------------------]  10%
 20/97 [=====>----------------------]  20%
 30/97 [========>-------------------]  30%
 40/97 [===========>----------------]  41%
 50/97 [==============>-------------]  51%
 60/97 [=================>----------]  61%
 70/97 [====================>-------]  72%
 80/97 [=======================>----]  82%
 90/97 [=========================>--]  92%
 97/97 [============================] 100%
    72 package suggestions were added by new dependencies, use `composer suggest` to see details.
Generating optimized autoload files
    > Illuminate\Foundation\ComposerScripts::postAutoloadDump
> @php artisan package:discover --ansi

   INFO  Discovering packages.

  laravel/sail ................................................................................................................................ DONE
  laravel/sanctum ............................................................................................................................. DONE
  laravel/tinker .............................................................................................................................. DONE
  nesbot/carbon ............................................................................................................................... DONE
  nunomaduro/collision ........................................................................................................................ DONE
  nunomaduro/termwind ......................................................................................................................... DONE
  spatie/laravel-ignition ..................................................................................................................... DONE

    81 packages you are using are looking for funding.
Use the `composer fund` command to find out more!
    > @php artisan vendor:publish --tag=laravel-assets --ansi --force

   INFO  No publishable resources for tag [laravel-assets].

    > @php artisan key:generate --ansi

   INFO  Application key set successfully.

   INFO  Application ready! Build something amazing.


C:\>

</pre>
