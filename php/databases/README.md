# Databases

## [Query collection hierarchies](query-collection-hierarchies.md)

+ Queries should be organised into a Query Collection Hierarchy.
+ Tables within the same collection can use an underscore to indicate their hierarchy.
+ Related tables should use an underscore to indicate their hierarchy.

## [Casing](casing.md)

+ Tables should use `SnakeCase`.
+ Columns should use `camelCase`.
+ Primary keys should be called `id`.

## [Naming](naming.md)

+ Columns can have optional descriptions to uniquely identify their purpose.
+ Foreign key column names should match their referenced column.
+ Foreign key constraint names should reference both tables and columns uniquely.
