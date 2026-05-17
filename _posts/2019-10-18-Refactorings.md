---
layout: post
title: Refactorings
tags: [refactoring, tools]
---

# Refactorings

1. Extract method.
2. Replace mutable fields with lenses.
3. Replace global state with parameter.
4. Introduce ReaderT (Kleisli). 
5. Replace loop with fold.
6. Replace recursion with fold.
7. Replace inheritance with natural transformation.
8. Replace exception with extended response type.
9. Replace null with optional.
10. Replace optional fields with sum types. 
11. Replace sum types with optional fields. 
12. Replace parameter with reduced type.
13. Replace mutable variable with recursion.
14. Replace similar methods with generic cousin.
15. Extract constant.
16. Merge into module.
17. Extract generic algebra.
18. Wrap side effect.
19. Pull out effect.

## With higher kinded types:

1. Generalize over input constraint. 
2. Isolate business key via data parametrization. 
3. Remove Recursion from GADT. 
4. Replace visitor with type class. 
5. Replace concrete classes with final tagless interpretation. 
6. Replace final tagless with free monad. 
7. Replace free monad with final tagless encoding. 
8. Replace strategy with tagless final. 
9. Replace subtypes with type class instances. 
10. Replace pattern matching with type class dispatch. 

## With dependent types :

1. Introduce parameter value dependent constraint.
2. Introduce (path) Dependent type.
3. Replace (path) Dependent type with type class constraint. 
