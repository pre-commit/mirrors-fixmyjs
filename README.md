fixmyjs mirror
================

Mirror of fixmyjs package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For fixmyjs: see https://github.com/jshint/fixmyjs

NOTE: fixmyjs requires pre-commit>=0.2.9


### Using fixmyjs with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/pre-commit/mirrors-fixmyjs
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: fixmyjs

It appears the most recent versions of fixmyjs are a work in progress.
It's best to use the legacy version for the time being by passing the -l
flag in `.pre-commit-config.yaml`:

    -   repo: https://github.com/pre-commit/mirrors-fixmyjs
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: fixmyjs
            args: ['-l', '-c', '.jshintrc']

