First Name Gender
=================

A python dict containing first names from the US Census and from other data we scraped from somewhere. The dict contains name:gender pairs with `Male`, `Female`, and `Neutral` as the values.

It's easy to use:

    from names import names
    if key in names:
        return names[key]

Example
----

    from names import names
    if "daniel" in names:
        print names['daniel']
    if "jessie" in names:
        print names['jessie']

returns:

    Male
    Neutral