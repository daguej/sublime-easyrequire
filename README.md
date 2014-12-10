About
=====

Inserts a `require()` statement snippet.  Type the module name or path and the variable name will have:

- Leading path information stripped
- Dashes removed with the following letter capitalized

Press <kbd>Alt</kbd>+<kbd>R</kbd> for a normal require statement, or <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>R</kbd> for a constructor require statement, where the first letter of the variable is also capitalized.

Example
=======

Press <kbd>Alt</kbd>+<kbd>R</kbd> and type `foo-bar`:

    fooBar = require('foo-bar')


Press <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>R</kbd> and type `foo-bar`:

    FooBar = require('foo-bar')

