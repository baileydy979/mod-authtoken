## 2.0.1 2018-09-11
 * Code clean-up

## 2.0.0 2018-09-10
 * Implement /refreshtoken and /refresh endpoints for obtaining and using refresh tokens
 * Change return format of /token endpoint to return token in body rather than header

## 1.5.2 2018-09-07
 * Reduce verbosity and level of several logs

## 1.5.1 2018-07-25
 * Merge fix for caching-flush bug

## 1.5.0 2018-07-10
 * Add 'iat' claim to all generated tokens

## 1.4.1 2018-02-27
 * Correct package name in pom

## 1.4.0 2018-02-27
 * Add header to zap cache on demand

## 1.3.0 2018-02-22
 * Implement option for time-based caching
 * Adjust token signing hand-off for new Okapi behavior

## 1.2.0 2017-12-18
 * Change behavior to act as a "headers only" filter in Okapi

## 1.1.0 2017-10-11
 * Allow wildcard permission names in desired permissions

## 1.0.0 2017-09-05
 * Use new id-referenced scheme for retrieving permissions
 * Add userid field to authtoken

## 0.6.1 2016-07-31
 * Fix bug with missing source file

## 0.6.0 2017-7-31
 * Add support for X-Okapi-User-Id header
 * Add support for X-Okapi-Request-Id header

## 0.5.0
 * Expand permission sets provided as modulePermissions to modules
 * Treat 404 for permission lookup as empty permission set
 * Remove keep-alive idle timeout
 * Fix internal dependency

## 0.4.0 2017-10-05

 * Initial release after splitting repository from mod-auth
