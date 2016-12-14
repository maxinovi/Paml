Paml stands for **Pa**llada **M**odeling **L**anguage, an object-modeling language as a part of [Pallada project](https://www.pallada-project.com). The Pallada project is an attempt to research and develop a modeling language and corresponding tools to improve object-oriented approach based on concepts of OOP, MDD, AOP and other practical approaches.

Paml concepts are originally described [here](https://www.pallada-project.com/2015/11/08/paml-concepts), but the concepts have been updated since the project started and develop.

The key concepts of Paml are:

* **Strict and simple object modeling and decomposition.** Objects collaborate each other via messages. There are no properties, fields, or something else from implementation world.

* **Simplicity via high-level abstractions.** Simple means abstractions only from domain. Aspects (that's projections) and alternative naming are the language feature. 

* **Practical idioms, patterns and approaches are language features.** Data model is an abstraction via associations. CRQS via messages for writing, data for reading. Unit tests are attributes of appropriate Paml code elements. 

* **Separation of Paml domain models and technological environment.**

* **Source code is produced by metaprogramming.** Source code is not manually written, but is produced and generated from Paml models. Paml provides the capability for productions and generations for output code (which is a source code in GPL like C#). Anyway, traditional programming takes in play here to implement resources like memory and algorithms. 

* **IDE support is mandatory.** Paml code is not a plain text, but a styled text. Style makes sense for element semantic. Paml elements are composed and applied to other ones (meta features). 
