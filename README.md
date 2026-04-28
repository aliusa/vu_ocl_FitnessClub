# OCL (Object Constraint Language)

### Task requirements:
* The original UML model must include at least 3 interrelated classes.
* Requirements for OCL constraints:
  * at least 10 meaningful **invariants**, 10 **pre-** and 10 **post-conditions** must be defined;
  * at least 5 post-conditions must include the values of features at the start of the operation (**@pre**);
  * at least 5 invariants and 5 post-conditions must include the **collection** operations; 
  * at least 5 different **collection operations** must be used, including **collect** and **select** operations;
  * at least 2 **collection of collections** must be used;
  * at least 3 invariants must include the **collection** types; 
  * at least 3 **local variables** must be defined and used;
  * at least 3 **queries** must be defined, at least 2 of which must use collection operations;
  * at least 2 **tuples** must be used;
  * no more than 2 OCL constraints may include the **allInstances** operation.
* All requirements must be presented with appropriate comments defining their meaning.
* **Use OCL tool** to:
  * represent the model **graphically**;
  * **check** (compile) the syntax of OCL constraints,
  * create and check at least 10 class **objects** that satisfy all invariants,
  * create and check at least 5 class **objects** that do not satisfy at least one invariant.
* **Recommended tool**: [USE](https://sourceforge.net/projects/useocl/) - a system for the specification and validation of information systems based on a subset of UML and OCL:
  * Download [USE](https://sourceforge.net/projects/useocl/) tool,
  * USE tool [Documentation](https://www.db.informatik.uni-bremen.de/projects/USE/use-documentation.pdf),
  * [USE Quick Tour](https://www.db.informatik.uni-bremen.de/projects/USE/qt.html),
  * also see  "The UML-based Specification Environment (USE) Tutorial" on YouTube.
* Any other OCL tool can be used. More about OCL tools:
  * [List of OCL tools](https://modeling-languages.com/list-ocl-tools/)
  * [OCLE](https://lci.cs.ubbcluj.ro/ocle/index.htm) - OCL Environment (supports both, syntax checking and Java code generation, requires Java 2 SE **JRE ver. 6**),
  * [Eclipse OCL](https://projects.eclipse.org/projects/modeling.ocl) - OCL **Eclipse** plug-in (supports all main features, evaluating OCL constraints, Java code generation, etc.)
* If the choosen tool does not support a certain construct, e.g. tuple, then the corresponding constraint shoud be modeled (defined) by another appropriate construct.

```use
open FitnessClub.use
read good_objects.soil
read bad_objects.soil
```
