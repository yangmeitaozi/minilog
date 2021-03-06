# 1.2.3 (2019-01-08)

- Sped up logging by eliminating module lookup.

# 1.2.2 (2019-01-08)

- Sped up logging by eliminating source file loading.

# 1.2.1 (2018-12-10)

- Fixed missing `%(relpath)s` format for `pytest`.

# 1.2 (2018-12-09)

- Fixed bug where logger name is unset when logging during imports.

# 1.1 (2018-10-26)

- Added `%(relpath)s` logging format.
- Added `verbosity` as `init()` option to work with Django admin commands.

# 1.0 (2018-09-27)

- Initial stable release.

# 0.5 (2018-09-07)

- Disabled automatic logging configuration when invoked by `pytest`.

# 0.4 (2018-4-28)

- Added `reset=True` as `init()` option to replace all existing logging handlers.
- Added `exception` logging API.
- Added convenience alias: `log.c`, `log.exc`.

# 0.3.1 (2018-03-30)

- Fixed bug where records were written for disabled levels.

# 0.3 (2018-03-15)

- Exposed `logging` level constants on the `log` package.
- Added `log.WARN` as an alias of `log.WARNING`.

# 0.2.1 (2018-03-04)

- Removed the Python version check on installation.

# 0.2 (2018-03-03)

- Added method to force logging format: `log.init(format="...")`
- Added method to silenced named loggers: `log.silence('requests', allow_error=True)`
- Added convenience aliases: `log.d`, `log.i`, `log.w`, `log.e`

# 0.1 (2018-03-03)

 - Initial release.
