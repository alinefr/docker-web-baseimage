# Changelog

## 1.2.0 - Unreleased
## Added
  - Multiarch support

### Changed
  - Upgrade baseimage to light-baseimage:release-1.2.0-dev (debian buster)
  - Upgrade to php7.3-fpm

### Fixed 
  - Install psmisc package with apache for killall command used in finish.sh

## 1.1.2 - Unreleased
### Changed
  - Upgrade baseimage to light-baseimage:1.1.2
  - nginx logs to /proc/self/fd/1 and /proc/self/fd/2

## 1.1.1
  - Add default ssl, security, cache and gzip config

## 1.1.0
  - apache: enable http2
  - update ssl config (nginx, apache)
  - php7.0-fpm
  - Upgrade baseimage: light-baseimage:1.1.1 (debian stretch)
  - set php timeout to 90s

## 1.0.0
  - order apt sources
  - time for 1.0.0 whup whup !

## 0.1.12
  - Use light-baseimage:0.2.6

## 0.1.11
  - Use light-baseimage:0.2.5

## 0.1.10
  - Use light-baseimage:0.2.4

## 0.1.9
  - Use light-baseimage:0.2.2

## 0.1.8
  - Use light-baseimage:0.2.1

## 0.1.7
  - Use light-baseimage:0.2.0
  - Makefile with build no cache
  - Use ubuntu keyserver

## 0.1.6
  - Use light-baseimage:0.1.5

## 0.1.5
  - Use light-baseimage:0.1.4

## 0.1.4
  - Use light-baseimage:0.1.3

## 0.1.3
  - Use light-baseimage:0.1.2
  - Add nginx

## 0.1.2
  - Fix "Package 'libapache2-mod-fastcgi' has no installation candidate"

## 0.1.1
  - Upgrade baseimage: light-baseimage:0.1.1

## 0.1.0
  - Initial release
