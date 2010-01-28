CHANGES
=======

tip (unreleased)
----------------

- update to jQuery 1.4 and MarkItUp! 1.1.6

- Add auto_preview option.

- Ajax preview view now uses RequestContext, and additionally passes
  ``MARKITUP_MEDIA_URL`` into the template context. (Previously,
  ``MARKITUP_MEDIA_URL`` was passed as ``MEDIA_URL`` and RequestContext was
  not used).

0.5.2 (2009.11.24)
------------------

- Fix setup.py so ``tests`` package is not installed.

0.5.1 (2009.11.18)
------------------

- Added empty ``models.py`` file so ``markitup`` is properly registered in
  ``INSTALLED_APPS``. Fixes issue with ``django-staticfiles`` tip not
  finding media.

0.5 (2009.11.12)
----------------

- Added ``MarkupField`` from http://github.com/carljm/django-markupfield
  (thanks Mike Korobov)

- Deprecated ``markitup_head`` template tag in favor of ``markitup_media``.

- Added ``MARKITUP_MEDIA_URL`` setting to override base of relative media
  URL paths.

0.3 (2009.11.04)
----------------

- added template-tag method for applying MarkItUp! editor (inspired by
  django-wysiwyg

0.2 (2009.03.18)
----------------

- initial release

