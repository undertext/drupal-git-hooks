drupal-git-hooks
================
Pre-commit hook for Drupal projects.

Written in PHP because i love PHP.

Inspired by [drupal-pre-commit](https://github.com/geraldvillorente/drupal-pre-commit) project.

In order to commit your changes, your code must pass the three filters:

- Syntax checking using PHP Linter

   You can alter file extensions to check by changing <code>$phpLintExtensions</code> variable.

- Coding standards checking using PHP Code Sniffer

   You need to have 'phpcs' installed on your machine.
   You can alter file extensions to check by changing <code>$phpSnifferExtensions</code> variable.

- Blacklisted functions checking/validation

   You can alter blacklisted functions by changing <code>$checks</code> variable.

   
