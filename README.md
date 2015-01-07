prospector mirror
=============

Mirror of prospector package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For prospector: see https://github.com/landscapeio/prospector


### Using prospector with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/guykisel/prospector-mirror
        sha: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: prospector
            args:
            - -o=pylint   # Optional, but recommended for best results