ThraceMediaBundle
=================

The `ThraceMediaBundle` handles file, video, audio and image upload plus some image manipulations like 
cropping, rotating, resetting ... etc. in your Symfony 2 application. It is 100% integrated with Doctrine ORM.
It is based on [Plupload](http://www.plupload.com/) library!
Also it has hard dependency of [KnpGaufretteBundle](https://github.com/KnpLabs/KnpGaufretteBundle) - used for filesystem abstraction
and [LiipImagineBundle](https://github.com/liip/LiipImagineBundle) for image manipulation with [Imagine](https://github.com/avalanche123/Imagine) library.

Documentation
-------------

The bulk of the documentation is stored in the `Resources/doc/index.md` file in this bundle:

Read the [documentation](Resources/doc/index.md)

Issues and feature requests are tracked in the [Github issue tracker](https://github.com/thrace-project/media-bundle/issues).

**Notice:** All PHP code is tested with PHPUnit. To run test 
```bash
	$ composer.phar install --dev --prefer-source 
	$ phpunit
```

[![Build Status](https://travis-ci.org/thrace-project/media-bundle.png?branch=master)](https://travis-ci.org/thrace-project/media-bundle)

When reporting a bug, it may be a good idea to reproduce it in a basic project
built using the [Symfony Standard Edition](https://github.com/symfony/symfony-standard)
to allow developers of the bundle to reproduce the issue by simply cloning it
and following some steps.


