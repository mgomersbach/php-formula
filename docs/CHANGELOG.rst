
Changelog
=========

`1.2.2 <https://github.com/saltstack-formulas/php-formula/compare/v1.2.1...v1.2.2>`_ (2019-10-10)
-----------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **composer.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/php-formula/commit/4e48a7a>`_\ )
* **map.jinja:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/php-formula/commit/01f5ede>`_\ )
* **repo.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/php-formula/commit/b4d994c>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/php-formula/commit/a5a8a95>`_\ )

`1.2.1 <https://github.com/saltstack-formulas/php-formula/compare/v1.2.0...v1.2.1>`_ (2019-10-07)
-----------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **pillar.example:** fix ``yamllint`` error (\ `1b1747a <https://github.com/saltstack-formulas/php-formula/commit/1b1747a>`_\ ), closes `/travis-ci.org/myii/php-formula/builds/594703019#L208-L210 <https://github.com//travis-ci.org/myii/php-formula/builds/594703019/issues/L208-L210>`_

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** change ``log_level`` to ``debug`` instead of ``info`` (\ `b86237e <https://github.com/saltstack-formulas/php-formula/commit/b86237e>`_\ )
* **kitchen:** install required packages to bootstrapped ``opensuse`` [skip ci] (\ `20be85a <https://github.com/saltstack-formulas/php-formula/commit/20be85a>`_\ )
* **kitchen:** use bootstrapped ``opensuse`` images until ``2019.2.2`` [skip ci] (\ `f70ebd2 <https://github.com/saltstack-formulas/php-formula/commit/f70ebd2>`_\ )
* **platform:** add ``arch-base-latest`` (commented out for now) [skip ci] (\ `55d5df1 <https://github.com/saltstack-formulas/php-formula/commit/55d5df1>`_\ )

`1.2.0 <https://github.com/saltstack-formulas/php-formula/compare/v1.1.1...v1.2.0>`_ (2019-09-13)
-----------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* use ``dist: bionic`` & apply ``opensuse-leap-15`` SCP error workaround (\ `76a2f76 <https://github.com/saltstack-formulas/php-formula/commit/76a2f76>`_\ )
* **yamllint:** add rule ``empty-values`` & use new ``yaml-files`` setting (\ `6f6d4bc <https://github.com/saltstack-formulas/php-formula/commit/6f6d4bc>`_\ )

Features
^^^^^^^^


* **tofs:** implementation for all file.managed (\ `8e79a35 <https://github.com/saltstack-formulas/php-formula/commit/8e79a35>`_\ )

`1.1.1 <https://github.com/saltstack-formulas/php-formula/compare/v1.1.0...v1.1.1>`_ (2019-09-05)
-----------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** replace EOL pre-salted images (\ `c9eea17 <https://github.com/saltstack-formulas/php-formula/commit/c9eea17>`_\ )

Tests
^^^^^


* **suse:** update version to ``7.0`` for ``opensuse-leap-15`` (\ `fd67570 <https://github.com/saltstack-formulas/php-formula/commit/fd67570>`_\ )

`1.1.0 <https://github.com/saltstack-formulas/php-formula/compare/v1.0.1...v1.1.0>`_ (2019-09-05)
-----------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **fpm:** be sure to restart all Php instances in case of multi-versions (\ `d4772f9 <https://github.com/saltstack-formulas/php-formula/commit/d4772f9>`_\ )
* **tests:** don't test services on Suse and RedHat (\ `23214bf <https://github.com/saltstack-formulas/php-formula/commit/23214bf>`_\ )
* **xdebug:** fix xdebug package name (\ `496ec28 <https://github.com/saltstack-formulas/php-formula/commit/496ec28>`_\ )
* **yamllint:** use separate suite for ``ubuntu`` (\ `6cba4af <https://github.com/saltstack-formulas/php-formula/commit/6cba4af>`_\ ), closes `#174 <https://github.com/saltstack-formulas/php-formula/issues/174>`_

Code Refactoring
^^^^^^^^^^^^^^^^


* **macro:** extract file_requisites macro (\ `d26c4f8 <https://github.com/saltstack-formulas/php-formula/commit/d26c4f8>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** add test pillars for Debian and call some states (\ `d4fc842 <https://github.com/saltstack-formulas/php-formula/commit/d4fc842>`_\ )

Features
^^^^^^^^


* **repo:** add repo pattern so we can set distro repo during tests (\ `3c9efc7 <https://github.com/saltstack-formulas/php-formula/commit/3c9efc7>`_\ )

Styles
^^^^^^


* **spec:** remove empty lines (\ `dc12a0b <https://github.com/saltstack-formulas/php-formula/commit/dc12a0b>`_\ )

Tests
^^^^^


* **config:** add tests on Php config (\ `6555cf0 <https://github.com/saltstack-formulas/php-formula/commit/6555cf0>`_\ )
* **package:** fix package spec in case of multi Php versions (\ `59f648c <https://github.com/saltstack-formulas/php-formula/commit/59f648c>`_\ )
* **service:** add tests on Php services (\ `baeac04 <https://github.com/saltstack-formulas/php-formula/commit/baeac04>`_\ )
* **ubuntu:** fix tests on Ubuntu distro (\ `b13bed2 <https://github.com/saltstack-formulas/php-formula/commit/b13bed2>`_\ )

`1.0.1 <https://github.com/saltstack-formulas/php-formula/compare/v1.0.0...v1.0.1>`_ (2019-08-26)
-----------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **pillar:** fix pillar.get still looking under 'ng' namespace (\ `378b5b1 <https://github.com/saltstack-formulas/php-formula/commit/378b5b1>`_\ )

`1.0.0 <https://github.com/saltstack-formulas/php-formula/compare/v0.41.1...v1.0.0>`_ (2019-08-26)
------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **ng:** promote NG formula (\ `57b37dd <https://github.com/saltstack-formulas/php-formula/commit/57b37dd>`_\ ), closes `#183 <https://github.com/saltstack-formulas/php-formula/issues/183>`_

BREAKING CHANGES
^^^^^^^^^^^^^^^^


* **ng:** all previous ``php`` based configurations must be reviewed;
  ``php.ng`` usage must be promoted to ``php`` and any uses of the original
  ``php`` will have to be converted.

`0.41.1 <https://github.com/saltstack-formulas/php-formula/compare/v0.41.0...v0.41.1>`_ (2019-08-26)
--------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* **readme:** remove duplicate contents (local) (\ `f16796a <https://github.com/saltstack-formulas/php-formula/commit/f16796a>`_\ )

`0.41.0 <https://github.com/saltstack-formulas/php-formula/compare/v0.40.1...v0.41.0>`_ (2019-08-26)
--------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **ng:** promote NG formula (\ `f1b71d0 <https://github.com/saltstack-formulas/php-formula/commit/f1b71d0>`_\ )

`0.40.1 <https://github.com/saltstack-formulas/php-formula/compare/v0.40.0...v0.40.1>`_ (2019-08-17)
--------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **map:** fix missing value for php.lookup.fpm.user in multi-php mode (\ `f91d942 <https://github.com/saltstack-formulas/php-formula/commit/f91d942>`_\ )

`0.40.0 <https://github.com/saltstack-formulas/php-formula/compare/v0.39.2...v0.40.0>`_ (2019-08-17)
--------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **yamllint:** include for this repo and apply rules throughout (\ `571cc4b <https://github.com/saltstack-formulas/php-formula/commit/571cc4b>`_\ )

`0.39.2 <https://github.com/saltstack-formulas/php-formula/compare/v0.39.1...v0.39.2>`_ (2019-08-13)
--------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **tests:** fix package name for debian (\ `4f75eac <https://github.com/saltstack-formulas/php-formula/commit/4f75eac>`_\ )

`0.39.1 <https://github.com/saltstack-formulas/php-formula/compare/v0.39.0...v0.39.1>`_ (2019-08-12)
--------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **installed.jinja:** remove ``include`` to prevent conflicting IDs (\ `cb11784 <https://github.com/saltstack-formulas/php-formula/commit/cb11784>`_\ ), closes `#188 <https://github.com/saltstack-formulas/php-formula/issues/188>`_

`0.39.0 <https://github.com/saltstack-formulas/php-formula/compare/v0.38.1...v0.39.0>`_ (2019-08-07)
--------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **php/ng:** don't iterate on string, make sure list is not string (\ `dbb542c <https://github.com/saltstack-formulas/php-formula/commit/dbb542c>`_\ )

Documentation
^^^^^^^^^^^^^


* **pillar.example:** add example for alternatives with multiversion (\ `23a6ec1 <https://github.com/saltstack-formulas/php-formula/commit/23a6ec1>`_\ )
* **pillar.example:** example of versions (\ `a98aa7e <https://github.com/saltstack-formulas/php-formula/commit/a98aa7e>`_\ )

Features
^^^^^^^^


* **php/ng:** support for php cli multiversion (\ `bb4a077 <https://github.com/saltstack-formulas/php-formula/commit/bb4a077>`_\ )
* **php/ng:** support the use of a list of php versions (\ `b303239 <https://github.com/saltstack-formulas/php-formula/commit/b303239>`_\ ), closes `#138 <https://github.com/saltstack-formulas/php-formula/issues/138>`_

Styles
^^^^^^


* **pillar.example:** add line break (\ `38fe58f <https://github.com/saltstack-formulas/php-formula/commit/38fe58f>`_\ )

`0.38.1 <https://github.com/saltstack-formulas/php-formula/compare/v0.38.0...v0.38.1>`_ (2019-08-03)
--------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* update deprecation version number in ``semantic-release`` run (\ `a87fb91 <https://github.com/saltstack-formulas/php-formula/commit/a87fb91>`_\ ), closes `/github.com/saltstack-formulas/php-formula/pull/175#issuecomment-517492613 <https://github.com//github.com/saltstack-formulas/php-formula/pull/175/issues/issuecomment-517492613>`_ `/github.com/saltstack-formulas/php-formula/pull/185#issuecomment-517603898 <https://github.com//github.com/saltstack-formulas/php-formula/pull/185/issues/issuecomment-517603898>`_

`0.38.0 <https://github.com/saltstack-formulas/php-formula/compare/v0.37.1...v0.38.0>`_ (2019-08-01)
--------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **map:** add xmlrpc package for xml module, as it was done for SUSE (\ `a09ef92 <https://github.com/saltstack-formulas/php-formula/commit/a09ef92>`_\ )

`0.37.1 <https://github.com/saltstack-formulas/php-formula/compare/v0.37.0...v0.37.1>`_ (2019-08-01)
--------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* add warning message for ng states (\ `d45bae8 <https://github.com/saltstack-formulas/php-formula/commit/d45bae8>`_\ )
* allow muting deprecation warning via. pillar/config entry (\ `8e7471e <https://github.com/saltstack-formulas/php-formula/commit/8e7471e>`_\ )
* change message to warn about upcoming deprecation (\ `e97eeae <https://github.com/saltstack-formulas/php-formula/commit/e97eeae>`_\ )
* warn formula users ng states will be promoted in ``v1.0.0`` (\ `d033381 <https://github.com/saltstack-formulas/php-formula/commit/d033381>`_\ )
* **pillar_from_files:** use ``{}`` pillar files to ensure tests pass (\ `1a5d734 <https://github.com/saltstack-formulas/php-formula/commit/1a5d734>`_\ )
* **readme:** add warning in  docs/README.rst (\ `3ac59e4 <https://github.com/saltstack-formulas/php-formula/commit/3ac59e4>`_\ )

`0.37.0 <https://github.com/saltstack-formulas/php-formula/compare/v0.36.0...v0.37.0>`_ (2019-07-09)
--------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **mods:** fixup for `#181 <https://github.com/saltstack-formulas/php-formula/issues/181>`_ (\ `e2d7b4b <https://github.com/saltstack-formulas/php-formula/commit/e2d7b4b>`_\ )

Features
^^^^^^^^


* **mods:** added some mods support for FreeBSD (\ `3f6c0bc <https://github.com/saltstack-formulas/php-formula/commit/3f6c0bc>`_\ )

`0.36.0 <https://github.com/saltstack-formulas/php-formula/compare/v0.35.1...v0.36.0>`_ (2019-06-29)
--------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* **readme:** update with modules, bz2 & dba (\ `5e04187 <https://github.com/saltstack-formulas/php-formula/commit/5e04187>`_\ )

Features
^^^^^^^^


* add 'bz2' and 'dba' module support (\ `758ae88 <https://github.com/saltstack-formulas/php-formula/commit/758ae88>`_\ )

`0.35.1 <https://github.com/saltstack-formulas/php-formula/compare/v0.35.0...v0.35.1>`_ (2019-06-28)
--------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* merge latest changes from ``template-formula`` (\ `4af569a <https://github.com/saltstack-formulas/php-formula/commit/4af569a>`_\ ), closes `#179 <https://github.com/saltstack-formulas/php-formula/issues/179>`_

`0.35.0 <https://github.com/saltstack-formulas/php-formula/compare/v0.34.0...v0.35.0>`_ (2019-06-27)
--------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **semantic-release:** add support of semantic-release (\ `cdd206a <https://github.com/saltstack-formulas/php-formula/commit/cdd206a>`_\ )
