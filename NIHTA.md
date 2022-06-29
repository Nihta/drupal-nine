# Document

## Lando

Start with environment.

```zsh
lando start
```

Import database.

```zsh
lando drush @site1.local sqlc < ./path_to_db.sql
```

Clear cache.

```zsh
lando drush @site1.local cr
```
