# mysq-to-postgres-within-docker

## Info
The script is just a simple argument parser, that will use an existing technology called Pgloader.
It you will have to call the script with your specific argument, based on your needs
For further information about pgloader, plase, visit www.pgloader.io

## Get started
You will have to change the directory into the one where the script is present.
Next step is calling the script with the wished arguments

## Template
sh ./migration mysql://<your_mysql_username>:<your_mysql_password>@<database_location> postgresql://<your_psql_username>:<your_psql_password>@<database_location>

## Example
sh ./migration mysql://username:password@database/shops postgresql://postgres:password@database/shops
