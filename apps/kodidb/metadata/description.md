# KodiDB

KodiDB is simple a MariaDB instance, available on port 8606, with a user given all rights.

Once the app is started, you can follow this [step](https://kodi.wiki/view/MySQL/Setting_up_Kodi) to configure your Kodi to synchronize its databases.

Maybe in the future... there will be :

* some kind of restriction of only allow Kodi instances to use the deployed MariaDB instance
* some mechanism to support various version of Kodi to use the service (at this time, all your instances must be on the same major version)
* some mechanism to initialize the database with an export from an existing Kodi instance
