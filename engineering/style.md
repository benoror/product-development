## Styles
We follow the [ruby style guide](https://github.com/bbatsov/ruby-style-guide) as our base, with the following changes:

* Line length 80 -> 90, the preferred line length is still 80, but we wont raise a fuzz if its a bit longer.
* Methods shouldn't exceed 20 lines, consider splitting the logic if it does.
* Classes shouldn't exceed 150 lines.
* No need to enforce `%r{}` around regexes.
* Don't use space between access modifiers and methods.
* Use the shorthand method for defining classes, 
```ruby
# this
class Api::V1::Controller
# instead of this
class Api 
  module V1 
    module Controller
```

Refer to the ruby style guide for anything not mentioned here.

## Linting
We use [rubocop](https://github.com/bbatsov/rubocop) as our linter, which helps us enforce the guidelines and is also part of the required checks before submitting code.

To use rubocop, you can run rubocop at the root of the project and it will display all linter errors and warnings, which you can then proceed to fix.

You can also install an addon in your text editor:
* [Atom](https://atom.io/packages/linter-rubocop)
* Vim
* Emacs
