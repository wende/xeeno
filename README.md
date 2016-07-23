# xeeno

| Construct  | Concern  | Solution   | Caveats
|---|---|---|---|
| Anonymous function  | Arity strictness  | Passing all parameters in a list  | - |
| Return  |  No return construct in Ex  | raising Error and wrapping in try catch  | Ugly and probably slow  |
| Break  | Same as return  | -\|- | -\|-  |
| Continue  | Same as return  | Same as break but with starting next run  |   |
| Break with label  | No construct  | raising Error with pattern matching on label  | Even uglier  |
| While  | No such construct in Ex  | Macro with recursion  | Might cause scoping problems  |
| For  |  Same as while |  -\|-  |   -\|- |
| Variables mutability  | No construct  | **NONE SO FAR**  | This might be hard  |
| module.exports  | Exporting functions  |  Wrap everything in def, return a map  |   |
| module.exports  | Exporting objects  |  **NONE SO FAR**  | This might be hard  |
|   |   |   |   |
