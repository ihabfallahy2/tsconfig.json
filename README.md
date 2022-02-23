# tsconfig.json
tsconfig.json configuration for Angular

'''
Or you get Property '' has no initializer and is not definitely assigned in the constructor. error.

Add below to your tsconfig.json

{
  "compilerOptions": {
    ...
    "strictPropertyInitialization": false
  }
}
'''
