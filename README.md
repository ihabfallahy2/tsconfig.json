# tsconfig.json
tsconfig.json configuration for Angular

this is when you get Property '' has no initializer and is not definitely assigned in the constructor --> error.
Add below to your tsconfig.json

```json
{
  "compilerOptions": {
    ...
    "strictPropertyInitialization": false
  }
}
```
