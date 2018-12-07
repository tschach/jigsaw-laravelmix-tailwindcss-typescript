# Jigsaw + Laravel Mix + Tailwind CSS + TypeScript
A skeleton project for Jigsaw (PHP static site generator), Laravel Mix (Webpack
asset manager), Tailwind CSS (functional CSS framework) and TypeScript
(strongly-typed JavaScript superset)

You can use this repository to kickstart your own static site with this JAM stack
or use it to troubleshoot your own take on setting it up. If you run into any 
problems, please [get in touch with me](https://about.me/tschach) or open an issue.
Also feel free to just say Hi! :smiley:

I am preparing an article on the details of creating this stack from scratch.
Stay tuned and come back here or subscribe to the [issue](https://github.com/tschach/jigsaw-laravelmix-tailwindcss-typescript/issues/1)
to get notified.

## Prerequisites

* [PHP 7](https://php.net/)
* [Composer](https://getcomposer.org/)
* [Node.js & npm](https://nodejs.org) (or yarn instead of npm, but I have no
experience with it)

I have used the following versions of these tools on an Ubuntu 16.04 32-bit
machine:

* `7.2.12`  (PHP)
* `1.8.0`  (Composer)
* `8.14.0`  (Node.js; at the time of writing I am stuck with the deprecated version 8 of
Node.js since pre-compiled 32-bit binaries for Linux are not offered anymore)
* `6.4.1`  (npm)

*Last updated: 7 December 2018*

## Clone the repository...

```shell-script
$ git clone git@github.com:tschach/jigsaw-laravelmix-tailwindcss-typescript.git
```

## ...or donwnload the ZIP file

```shell-script
$ wget https://github.com/tschach/jigsaw-laravelmix-tailwindcss-typescript/archive/master.zip && unzip master.zip && mv jigsaw-laravelmix-tailwindcss-typescript-master jigsaw-laravelmix-tailwindcss-typescript && rm master.zip
```

## Change to project directory 
```shell-script
$ cd ./jigsaw-laravelmix-tailwindcss-typescript
```

## Install dependencies (Composer and npm):
```shell-script
$ composer install && npm install
```

## Build & preview

```shell-script
$ npm run watch
```

Read more on [Building and Previewing Jigsaw projects](http://jigsaw.tighten.co/docs/building-and-previewing/)

## Enjoy and have fun!

**Jigsaw** is a MIT licensed PHP static site generator based on Laravel and using
Blade for templating.  
:house: http://jigsaw.tighten.co/  
:octocat: https://github.com/tightenco/jigsaw

**Laravel Mix** is a MIT licensed asset manager, compiler and bundler wrapped around
Webpack.  
:house: https://laravel-mix.com/  
:octocat: https://github.com/JeffreyWay/laravel-mix

**Tailwind CSS** is a MIT licensed utility-first CSS framework.  
:house: https://tailwindcss.com/  
:octocat: https://github.com/tailwindcss/tailwindcss

**TypeScript** is an Apache licensed superset of JavaScript with static types and 
other ECMAScript 2015 features.  
:house: https://www.typescriptlang.org/  
:octocat: https://github.com/Microsoft/TypeScript
