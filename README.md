Search identifier
=================

Add an identifier column to search and advanced search results pages in the staff ui. Displays value for:

- Agents (authority id if defined)
- Accessions
- Archival Objects (resource id if defined in linked physical instance)
- Digital Objects
- Resources
- Subjects (authority id if defined)

Usage
-----

Download the plugin to the plugins folder. Add the plugin in `config.rb`:

```
AppConfig[:plugins] << "aspace-search-identifier"
```

Restart ArchivesSpace.

---
