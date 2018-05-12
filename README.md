Symfony-Wordpress Skeleton
==========================

A Composer builded stack for combining Wordpress and Symfony.
This skeleton use the [MukadiWordpressBundle](https://github.com/mbo2olivier/mukadi-wordpress-bundle) to use Wordpress in symfony. So check the documentation to deal with it.

## Features

* Use Symfony to manipulate Wordpress database
* Dispatch Event from Wordpress into Symfony
* Use custom Symfony services into Wordpress (note: only public services),
* Versionning your custom wordpress code (themes and plugins)
* Install plugins via composer

## Installation

Run `composer create-project mukadi/wp-sf-skeleton app`