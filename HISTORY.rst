History
-------

0.8.0 (2018-10-25)
++++++++++++++++++

- Add release utilities to ``setup.py`` + ``.gitignore`` update
- Tox/Travis: Expand Python versions tested
  https://github.com/wronglink/pytest-pudb/pull/27
- ``PuDBWrapper#pytest_exception_interact``: Remove call to ``self.disable_io_capture()``
  https://github.com/wronglink/pytest-pudb/pull/26
- `pytest.hookspec.pytest_enter_pdb` expects a `pdb` (keyword) argument
  https://github.com/wronglink/pytest-pudb/pull/25
- Disable unittest tearDowns and cleanups for post mortem debugging
  - https://github.com/wronglink/pytest-pudb/issues/9
  - https://github.com/wronglink/pytest-pudb/pull/21

0.7.0 (2018-10-25)
++++++++++++++++++

- Added pu.db support
- Fixed pytest 3.7.3+ compatibility
- Switched to semantic versioning
- Build package wheels

0.6 (2018-02-13)
++++++++++++++++

- Fixed pytest 3.3.1+ compatibility (by `@noirbizarre <https://github.com/noirbizarre>`_)

0.5 (2017-02-25)
++++++++++++++++

- Fixed pypi package by adding MANIFEST.in

0.4 (2017-02-24)
++++++++++++++++

- Use post mortem on exception (by `@Wilfred <https://github.com/Wilfred>`_)

0.2 (2016-09-24)
++++++++++++++++

- Added ``import pytest.b`` support

0.1 (2016-07-31)
++++++++++++++++

- Public release
