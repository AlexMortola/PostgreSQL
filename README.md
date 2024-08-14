# PostgreSQL
Download every file. One done, right click on adventureworks.zip and select "Extract all…".
You'll get the aw.dump file (869,218 KB) that is a plain text dump of the AdventureWorks database, PostgreSQL version.
It includes the sales.salesorderheaderenlarged and sales.salesorderdetailenlarged, based on the script written by Jonathan Kehayias.
This file must be restored using psql. E.g.:
psql -h localhost -p 5432 -d adventureworks -U postgres -f C:\...\aw.dump
