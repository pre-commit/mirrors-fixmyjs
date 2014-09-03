fixmyjs mirror
================

Mirror of fixmyjs package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For jshint: see https://github.com/jshint/fixmyjs


### Using fixmyjs with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/pre-commit/mirrors-fixmyjs
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: fixmyjs
