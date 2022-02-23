# tsconfig.json
/tsconfig.json configuration for Angular

``` your tree 
app|...
   |-tsconfig.app.json
   |-tsconfig.json
   |-tsconfig.spec.json
```

This is when you get Property '' has no initializer and is not definitely assigned in the constructor --> error.
Add below to your tsconfig.json

```json
{
  "compilerOptions": {
    ...
    "strictPropertyInitialization": false
  }
}
```
