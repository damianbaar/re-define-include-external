re-define-include-external
==========================

`re-define` plugin for finding external files, outside the scope of the project.

Usage:

```
var findExternal = require('re-define-include-external')({
    external     : {"lodash":"./vendor/lodash.js"}
  , discoverable : ['node_modules', 'bower_component']
  , descriptors  : ['package.json', 'bower.json']
  , skip         : ['module_name']
  })
```
