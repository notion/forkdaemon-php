# PHP Fork Daemon
A library to make setup and management of forking daemons in PHP easy.

## Features
-   Easy management of PHP forks
-   Splitting work units into buckets
-   Preforking callbacks to manage resources before forking
-   Dynamic setting of number of children / work per child

## Usage
Check out the examples in the examples directory
``php example/blocking.php``

## Caveats
-	You need to specify ``declare(ticks=1);`` before inclusion of the fork-daemon library, otherwise signals wont be handled. Ref: php.net/declare

## License
Copyright 2013 Barracuda Networks, Inc.
Licensed under the MIT License
