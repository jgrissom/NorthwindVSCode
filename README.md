# Data Migrations .Net Core CLI

## To create a new migration using the terminal

```
dotnet ef migrations add XXX
```

Replace XXX with the name of the new migration

## To apply pending migrations

```
dotnet ef database update
```

[documentation](https://docs.microsoft.com/en-us/ef/core/managing-schemas/migrations/?tabs=dotnet-core-cli)
