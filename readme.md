## Create Migration
```db-migrate create:SCOPE MIGRATION_NAME --sql-file```

```db-migrate create:ubis update_budget_header --sql-file```

## Update Database Name
Open the file `./migration/SCOPE/config.json` and edit `database`

## Update Database Configuration

Open the file `database.json` and update the configuration. For `username` and `password` open the file `.env` or create one if not existed and follow the configuration below:

```
DB_USER=root
DB_PASS=mysqladmin
```
## Execute/Run Migration
```db-migrate up:SCOPE```

```db-migrate up:ubis```
