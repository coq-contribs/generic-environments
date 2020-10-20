# Generic Environments

Generic Environments is a library which provides an abstract data type of environments, as a functor parameterized by a module defining variables, and a function which builds environments for such variables with any Type of type. Usual operations over environments are defined, along with an extensive set of basic and more advanced properties. Moreover, an implementation using lists satisfying and all the required properties is provided.

This library is based on the following article:
- Emmanuel Polonowski, "[Generic Environments in Coq](https://arxiv.org/pdf/1112.1316.pdf)", 2011.

## Installation using OPAM
```bash
opam install coq-generic-environments
```