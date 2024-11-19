# Modular manufacturing
*How module systems in the tradition of the ml programming language make software more flexible, maintainable, and correct*

- light switch. its not all the circuitry
- coffee machine. its not all the brewing steps
- map analogy. its not all the elements of the terrain
- restruraunt menu. its not all the recipes

## Problem statement

- what is the pain point
- why is that so painful
- what is the cause

## Solution statement

- what is the solution
- what are stories, context, and examples
- what are the benefits

## Notes

- Modules are essentially an environment or namespace that is first class, and that can optionally have types as members.
- Module types are a declaration of what member types, values, and functions a module must have, *at mininimum*, to satisfy the type.
- Module functions operate on modules, allowing you to define functionality for a module after it has been define. This allows you to define functions as and when needed. A good example of when this is useful is when you dont yet know the dependencies for a given module. You can specify the module type ahead of time and create functions to initialize different modules when the data or functions they require have been met.
