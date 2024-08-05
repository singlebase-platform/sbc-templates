# SBC-Templates




```
{

  *type:str (model|app) - the type of template 
  title:str -
  description:str - 
  "path": "",
  *schemas: {
    jsonschema: {...},
    tableviewschema: {...},
    singleviewschema: {},
    editviewschema: {...},
  },
  properties: {
    "allow_jsonschema_edit": true,
    "allow_tableview_edit": true,
    "allow_editview_edit": true,
  },

}

```