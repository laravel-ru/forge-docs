# Databases

[[toc]]

## Creating a Server With a Database

When creating a new server, you can select to install one of these database servers too:

- MySQL (5.7)
- MySQL (8.0)
- MariaDB (10.3)
- Postgres (12)

As part of the provisioning process, Forge will automatically install the chosen database server and create a default `forge` database, `forge` user and password. The database password will be shown upon creating the server alongside the root password, but will also be emailed to you.

If you decide not to install a database as part of the provisioning process but later decide you need one, you have two options:

1. Re-create the server, but this time selecting your required database server too.
2. Maintaining a custom database server. If you do this then Forge will not be able to manage users or databases for you.

## Creating a Database

You can create a new database through the Forge dashboard by clicking on to the server detail page and clicking **Database** in the sidebar. By default you'll only need to enter the name of your new database

## Create a Database User

## Changing the Root / Forge Database Password

## Connecting to a Database GUI Client

All Forge servers require SSH key authentication and are not able to be accessed using passwords. Therefore, when using a GUI database client to connect to your Forge database, you will need to use SSH authentication.

When selecting the SSH key to use during authentication, **ensure that you select your private SSH key**. For example, when using the Sequel Pro database client: