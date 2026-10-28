# release-elements

Data source for a dynamic multi-select picker. `files-elements.json` holds 1000 elements in the shape the picker expects:

```json
{ "items": [ { "id": "element1", "name": "Element 1" } ] }
```

- `arraySelector`: `items`
- `valueSelector`: `id`
- `labelSelector`: `name`

## Files

One `<type>-elements.json` per element type: files (1000), plus directories, modules, container_image, db_objects, tokens, calendars, bms_sources, app_servers, ftp_pollers, nite_jobs, transfers, application, application_package and application_identity_group (100 each). Same shape in every file.
