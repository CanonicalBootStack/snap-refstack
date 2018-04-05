Refstack API Snap
=================

This is a snap for the [Refstack](https://refstack.openstack.org/) API and UI, used
for running Refstack testing offline or if you would like a private server for 
collecting and viewing test results.

The API service by default is configured for using an SQLite DB, and will start the
API in dev mode, meaning the UI will be run also. The configuration files for
the API are redirected to /var/snap/refstack/common, so if you need to change this
behavious, you can.
