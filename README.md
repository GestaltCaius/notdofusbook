# Links

* https://loopback.io/doc/en/lb4/apidocs.repository.filterbuilder.html
* https://loopback.io/doc/en/lb4/Querying-data.html#build-filters-with-filterbuilder
* https://loopback.io/doc/en/lb2/Where-filter

# Examples

```
 https://fr.touch.dofapi.fr/equipments/?filter={"where":{"and":[{"statistics":[{"PA":{"min":1,"max":null}}]},{"level":{"gt":59}},{"type":"Anneau"}]}}
```
