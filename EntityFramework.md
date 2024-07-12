

```markdown
# Entity Framework Commands

This document provides a complete list of commands used in Entity Framework Core and Entity Framework 6.

## Table of Contents

- [Entity Framework Core Commands](#entity-framework-core-commands)
- [Entity Framework 6 Commands](#entity-framework-6-commands)

## Entity Framework Core Commands

### Package Manager Console (PMC) Commands

| Command                                          | Description                                              |
|--------------------------------------------------|----------------------------------------------------------|
| `Add-Migration <MigrationName>`                 | Creates a new migration with the specified name.        |
| `Update-Database`                               | Applies pending migrations to the database.             |
| `Remove-Migration`                              | Removes the last migration that has not been applied.    |
| `Get-Migrations`                                | Lists all migrations that have been applied or are pending. |
| `Script-Migration`                              | Generates a SQL script from migrations.                 |
| `Update-Database -TargetMigration <MigrationName>` | Updates the database to a specific migration.          |
| `Get-DbContext`                                 | Displays information about the DbContext.               |

### .NET CLI Commands

| Command                                          | Description                                              |
|--------------------------------------------------|----------------------------------------------------------|
| `dotnet ef migrations add <MigrationName>`      | Creates a new migration.                                 |
| `dotnet ef migrations remove`                   | Removes the last migration that has not been applied.    |
| `dotnet ef database update`                     | Applies pending migrations to the database.             |
| `dotnet ef migrations list`                     | Lists all migrations.                                   |
| `dotnet ef migrations script`                   | Generates a SQL script for migrations.                  |
| `dotnet ef dbcontext info`                       | Displays information about the DbContext.               |
| `dotnet ef dbcontext scaffold <ConnectionString> <Provider>` | Scaffolds a DbContext and entity types from an existing database. |
| `dotnet ef dbcontext optimize`                  | Optimizes the DbContext configuration.                  |

## Entity Framework 6 Commands

### Package Manager Console (PMC) Commands

| Command                                          | Description                                              |
|--------------------------------------------------|----------------------------------------------------------|
| `Add-Migration <MigrationName>`                 | Creates a new migration with the specified name.        |
| `Update-Database`                               | Applies pending migrations to the database.             |
| `Remove-Migration`                              | Removes the last migration that has not been applied.    |
| `Get-Migrations`                                | Lists all migrations.                                   |
| `Script-Migration`                              | Generates a SQL script from migrations.                 |
| `Update-Database -TargetMigration <MigrationName>` | Updates the database to a specific migration.          |

## General Commands

### Context and Database Management

| Command                                          | Description                                              |
|--------------------------------------------------|----------------------------------------------------------|
| `context.Database.EnsureCreated()`              | Creates the database if it does not exist.              |
| `context.Database.EnsureDeleted()`              | Deletes the database.                                   |
| `context.Database.Migrate()`                    | Applies all pending migrations.                          |
| `context.Database.ExecuteSqlCommand(<SQL>)`     | Executes a raw SQL command against the database.        |

### Querying and Saving

| Command                                          | Description                                              |
|--------------------------------------------------|----------------------------------------------------------|
| `context.SaveChanges()`                         | Saves all changes made in the context to the database.  |
| `context.Set<TEntity>().ToList()`               | Retrieves all entities of a specified type.             |
| `context.Set<TEntity>().Find(<id>)`             | Finds an entity by its primary key.                      |
| `context.Set<TEntity>().Add(entity)`            | Adds a new entity to the context.                        |
| `context.Set<TEntity>().Remove(entity)`         | Removes an entity from the context.                     |
| `context.Set<TEntity>().Update(entity)`         | Updates an existing entity in the context.              |

## References

- [Entity Framework Core Documentation](https://docs.microsoft.com/en-us/ef/core/)
- [Entity Framework 6 Documentation](https://docs.microsoft.com/en-us/ef/ef6/)

## License

This project is licensed under the MIT License.
```

Feel free to modify this as needed!
