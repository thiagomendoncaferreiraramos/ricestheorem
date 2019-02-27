# ricestheorem
Formalization of the Rice's Theorem in PVS for the multiple-function PVS0 language model.
In addition to Rice's Theorem, this library contains formalizations of the theorem of
undecidability of the Halting Problem and Fixed Point Theorem for this model. PVS0 is
essentially a functional language model which includes its operational semantics as part
of the specification. 

Instructions:  to follow this formalization, it is necessary to install PVS version
6.0 (avaliable in http://pvs.csl.sri.com/download.shtml) including the NASA PVS libraries
(avaliable in https://github.com/nasa/pvslib).

The description of the files in the library is given below. 

The main file top.pvs imports the principal files of the theory that are  
pvs0_halting.pvs and fixedpoint.pvs.

pvs0_halting.pvs contains the formalization of the Rice's Theorem (called 
pvs0_Rice_theorem), the formalization of the Undecidability of the Halting Problem 
(called pvs0_halting_problem_undecidability) and of an specific case where the 
Decidability of the Halting Problem holds (called pvs0_halting_problem_decidability).

fixedpoint.pvs contains the formalization of the Fixed Point Theorem (fixed_point).

pvs0_computable.pvs includes specification and properties of the types Computable 
and PartialRecursive. It also includes properties related to the countability 
the elements of the type PartialRecursive.

pvs0_to_nat.pvs includes properties related to countability of PVS0 expressions 
specified with the working type of naturals.

pvs0_lang.pvs contains the shifiting code lemmas (called add_rec_list and add_rec_list2) and the offset definition.

In pvs0_expr.pvs includes the semantic evaluation predically and functionally of the PVS0 programs.

In PVS0Expr.pvs contains the grammar of the PVS0 expressions.

subtype_length.pvs, subtype_map.pvs, map_append.pvs include properties related with types and lists.


Authors: Thiago Mendonca Ferreira Ramos, Ariane Alves Almeida and Mauricio Ayala-Rincon; Universidade de Brasilia, Brazil
Last modification: 27th February, 2019

References:

T.M. Ferreira Ramos, C.A. Munoz, M. Ayala-Rincon, M. M. Moscato, A. Dutle, A. Narkawicz, 
Formalization of the Undecidability of the Halting Problem for a Functional Language.
Workshop on Logic, Language, Information and Computation, WoLLIC 2018.
Contains the formalization of this theorem for the single-function PVS0 model, which is
available as part of the NASA PVS library, subdirectory PVS0  at link

T.M. Ferreira Ramos, A. A. Almeida, M. Ayala-Rincon, 
Formalization of Rice's Theorem over a Functional Language Model.
Submitted, 2019.
