# OCL (Object Constraint Language)

Task requirements:
* The original UML model must include at least 3 interrelated classes.
Requirements for OCL constraints:
* at least 10 meaningful invariants, 10 pre- and 10 post-conditions must be defined;
* at least 5 post-conditions must include the values of features at the start of the operation (@pre);
* at least 5 invariants and 5 post-conditions must include the collection operations; 
* at least 5 different collection operations must be used, including collect and select operations;
* at least 2 collection of collections must be used;
vat least 3 invariants must include the collection types; 
* at least 3 local variables must be defined and used;
* at least 3 queries must be defined, at least 2 of which must use collection operations;
* at least 2 tuples must be used;
* no more than 2 OCL constraints may include the allInstances operation.

All requirements must be presented with appropriate comments defining their meaning.
Use OCL tool to:
* represent the model graphically;
* check (compile) the syntax of OCL constraints,
* create and check at least 10 class objects that satisfy all invariants,
* create and check at least 5 class objects that do not satisfy at least one invariant.

To run use [USE](https://sourceforge.net/projects/useocl/) program.
```use
open FitnessClub.use
read good_objects.soil
read bad_objects.soil
```
