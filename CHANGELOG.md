# Changelog

## Unreleased
 - fixes an issue where proxrox tried to read the pid file before nginx
   finished starting up

## 1.2.0
 - automatically create a self-signed certificate and enable transport layer
   security via `--tls`
 - support SPDY via `--spdy`

## 1.1.0
 - enable GZIP compression by default
 - disable GZIP compression with `--no-compression`
 - enable SSI via `--ssi`

## 1.0.2
 - typo in `colors` dependency

## 1.0.1
 - add missing `colors` dependency

## 1.0.0
 - install nginx automatically via the CLI
 - Start and stop nginx via the CLI
 - Support proxying a single service