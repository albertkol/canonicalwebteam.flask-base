# 0.7.1 (2020-11-23)

### Added
Changed `SEND_FILE_MAX_AGE_DEFAULT` back to the default value
Set `Cache-Control: max-age 31536000` for requests with the v in the query string

# 0.7.0 (2020-11-18)

### Added
Set `SEND_FILE_MAX_AGE_DEFAULT` to a year (31536000)

# 0.6.4 (2020-09-22)

### Added
Pin gevent to version 20.6.2
Pin greenlet to version 0.4.16

# 0.6.3 (2020-05-27)

### Added
Pin gevent to version 20.6.1

# 0.6.2 (2020-06-11)

### Fix
`versioned_static` shouldn't break the app if files are missing


# 0.6.1 (2020-05-20)

### Features
Serve favicon from static if it exists, otherwise fallback to favicon url.

# 0.6.0 (2020-04-14)

### Added
Update to talisker 0.18.0


# 0.5.1 (2020-04-14)

### Added
Pin gevent to version 1.4.0


# 0.4.0 (2020-02-10)

### Added
Set cache headers for all responses, overridable in the view.


# 0.2.0 (2019-06-10)

### Features
Added a context processor to FlaskBase instances containing common helpers needed acrosss
diferent apps.


# 0.1.0 (2019-06-05)

### Features
Added FlaskBase class to wrap common functionality of canonical webteamm's flask applications
