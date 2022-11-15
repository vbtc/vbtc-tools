Python 2 to 3 conversion, Notes:

Using modernize, it did some extra changes on imports, it tried to import six.[something] that did not exist.

Installed tools:
* caniusepython3
* mypy
* pylint
* pytype
* modernize
* types-requests (needed for mypy to do its thing)

As well as the mypy plugin.


Next steps:

Future improvements: Type everything
Using mypy --strict reports missing types.


