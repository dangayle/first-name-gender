First Name Gender
=================

A python dict containing first names from the US Census and from other data we scraped from somewhere.

It's easy to use:

    from names import names

    if key in names:
        return names[key]

Example
----

    from names import names
    if "daniel" in names.names
        print names['daniel']

returns:

    Male