[![Latest Version](https://pypip.in/version/iso639/badge.svg)](https://pypi.python.org/pypi/iso639/)
[![License](https://pypip.in/license/iso639/badge.svg)](https://pypi.python.org/pypi/iso639/)

iso639
======
A simple (really simple) library for working with ISO639-2 language codes.
Tested for Python 2.7 & 3.4.

Includes data from Congress library: http://www.loc.gov/standards/iso639-2/php/code_list.php

Installation
------------
The easiest way is using `pip`:

    pip install iso639

Alternatives
------------
* **pycountry**: https://bitbucket.org/flyingcircus/pycountry - a more-featured package
* **iso639**: https://github.com/noumar/iso639 - another package with the same name

Example usage
-------------

```python
import iso639

>>> iso639.to_name('sv')
u'Swedish'
```

For more examples, see doctests in the source code.
