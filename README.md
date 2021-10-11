# NGiNX + PHP-FPM Docker

This Docker image aims to produce a starting point for you who wants to serve your PHP project through something Docker environment, or simply doesn't want to use the nowdays usual Docker Compose setup, which is not optimal for a K8s like environment.

## PDO

The PHP PDO extension comes installed by default.

## Versioning

The build versions will be based on PHP version, and both FPM and NGiNX will be used accordingly so they are compatible with the target PHP version.

The version names are divided by a dash; on the left side the PHP version and on the right side the build version.
