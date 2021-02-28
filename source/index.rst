.. jsonschema poc documentation master file, created by
   sphinx-quickstart on Sun Feb 28 20:09:02 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to jsonschema poc's documentation!
==========================================

..  contents::
    :local:

Example
----------

- Source: https://github.com/eclecticiq/git4intel/blob/master/git4intel/schemas/mitre.json
- Converted to JSON schema using github.com/wolverdude/genSON
- Displayed using `jsonschema` directive from https://github.com/lnoor/sphinx-jsonschema

.. jsonschema:: _data/mitre_schema.json

Expected format
---------------

..  jsonschema::

    {
        "$schema": "This field is ignored for now. Perhaps use it to indicate schema version in display?",
        "title": "Test data set 1: **Simple type**",
        "id": "http://this.better.be.a.regular.domain",
        "description": "These data sets exercise `JSON Schema <http://json-schema.org>`_ constructions and show how they are rendered.\n\nNote that it is possible to embed reStructuredText elements in strings.",
        "type": "string",
        "minLength": 10,
        "maxLength": 100,
        "pattern": "^[A-Z]+$"
    }
