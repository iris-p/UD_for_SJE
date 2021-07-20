# Universal Dependencies for Pite Sámi
Constraint Grammar source code from my master's thesis

- _functions.cg3_ adds syntactic labels according to the GiellaLT annotation scheme.

- _dependency.cg3_ adds GiellaLT dependency arcs to the output of _functions.cg3_.

- _GT\_UD\_conv.cg3_ converts the output of _dependency.cg3_ to the Universal Dependency annotation scheme.

The version of the finite state morphological analyser used for testing is included because it contains some changes from the version at https://github.com/giellalt/lang-sje/tree/main/src/fst (some transitive verbs are tagged as such).
