# PHP

As a general rule, code in PHP should only be written to extend or modify WordPress.

As another general rule, __greenfield projects may not be started in PHP for any reason__.

Interpolating HTML into PHP files should be kept to a minimum and only used where strictly
necessary (e.g., in WordPress themes).

Method and variable names should be spelled in snake_case, in keeping with local conventions.

Where possible, PHP code written for Dreamacy should be enclosed within the dreamacy namespace.
If needed, names can be munged with the dcy_ prefix instead (if the code cannot be namespaced,
as is the case with WordPress themes and extensions).

Code in PHP must follow [PSR-12](https://www.php-fig.org/psr/psr-12/).
