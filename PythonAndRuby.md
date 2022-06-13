# Style Considerations for Python and Ruby

Method and variable names in these languages should be spelled in `snake_case`, in keeping with local conventions.

## Specific to Python

* The _Black_ code formatter is used on all Python projects without exception.

* The standard pylintrc kept within our WillPress project shall be used on all Python projects without exception.

* Code in Python must follow [PEP-8](https://peps.python.org/pep-0008/).

* __Code using multiple inheritance will not be accepted into the `trunk` branch of any Dreamacy project for any reason.__

* We prefer to refer to `__init__` and its ilk as _magic methods_.

* Our preferred Python frameworks are Django and Flask.

## Specific to Ruby

* The Rufo code formatter (similar to Black in its degree of opinionatedness) is used on all Ruby projects without exception.

* Code in Ruby must follow [the Airbnb Ruby style guide](https://airbnb.io/projects/ruby/).

* Our preferred Ruby frameworks are Ruby on Rails and Sinatra.
