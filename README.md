Prospector (Boosted fork ed.) mirror
=============

Mirror of prospector package for pre-commit.

Boosted with mypy and vulture for personal projects.

For pre-commit: see https://github.com/pre-commit/pre-commit

For prospector: see https://github.com/landscapeio/prospector


### Using prospector with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/guykisel/prospector-mirror
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: prospector
