# SBC App Templates


---
## SCHEMA VERSIONS

### 1.0.0

`$schema_version: 1.0.0`

#### Model 

```
{
    id: null, 
    name: 'name',
    description: '',
    version: '1.0.0',
    type: 'model',
    meta: {
      creator: null,
      category: null,
      usecases: [],
      industries: [],
      previewImage: null,
      previewImages:[],
    },
    schemas: {
      json_schema: {},
      view_schema: {},
      singleview_schema: {},
      singleedit_schema: {},
    },
    schemas_settings: {
      json_schema: {},
      view_schema: {},
      singleview_schema: {},
      singleedit_schema: {},
    },
    rules: [],
    $_version: "1.0.0",
    $_date: Date
    
}
```

#### Definitions:
```

id:str - unique id
name:str name of the app
description:str - the description
version:str - semver 
type:str - the schema type: model|app
meta:object - extra data
schemas:object - contains all the schemas
  - json_schema:object - JSON Schema
  - view_schema:object - Schema for the Data View
  - singleview_schema:object - Schema to show a single element view
  - singleedit_schema:object - Schema to edit single element view

schemas_settings:object - settings for all schemas
  - json_schema:object - JSON Schema
  - view_schema:object - Schema for the Data View
  - singleview_schema:object - Schema to show a single element view
  - singleedit_schema:object - Schema to edit single element view

rules:[]
validations:TBD

$_version:str - the schema version of the system
$_date:Date - the date the schema was created 
```

---

