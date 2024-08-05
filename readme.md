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
  *config: {
    jsonschema: {
      edit_mode: full|partial|none 
    }
  },

}

```