Search identifier
=================

Add an identifier column to search and advanced search results pages in the staff ui. 
This is a slight remix of the functionality that's been built into ArchivesSpace 
as of v2.4.0.

The plugin displays values for:

- Agents (authority id if defined)
- Accessions
- Archival Objects (parent resource id)
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
