# Laravel Sublime Snippets

> Sublime Snippets for Laravel Migrations

This plugin for Sublime Text 3 allows you to have quick access to most common migration commands.

## Final Example

```php
$table->string('field_name', 255)->unique()->nullable()->default('Default')->comment('Comment');
```

## Screen

![Screen](https://raw.githubusercontent.com/marceloxp/laravel_migration_snippets/master/migration-v01.gif "Screen")

## Field Types

- Boolean
- Index
- Integer
- String
- Text

## Other Snippets
- Soft_deletes
- Unique

## Extra
- Fix_enum (Adds a code to execute migration on tables with any enum field type)