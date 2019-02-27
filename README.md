# ricestheorem
Formalization of the Rice's Theorem in PVS for the functional language PVS0.

The main files described in the file top.pvs are pvs0_halting.pvs and fixedpoint.pvs.

In pvs0_halting.pvs, there are the Rice's Theorem (called pvs0_Rice_theorem), the Undecidability of the Halting Problem 
(called pvs0_halting_problem_undecidability) and a specif case where the Decidability of the Halting Problem holds
(called pvs0_halting_problem_decidability).

In fixedpoint.pvs, there is the fixed point theorem (called fixed_point).

In pvs0_computable.pvs, there are definitions of the types Computable and PartialRecursive. There are also properties related to
the countability the elements from the type PartialRecursive.

In pvs0_to_nat.pvs, there are more properties related to countability of PVS0 expressions that work with natural numbers.

In pvs0_lang.pvs, there are the shifiting code lemmas (called add_rec_list and add_rec_list2) and the offset definition.

In pvs0_expr.pvs, there are the semantic evaluation predically and functionally of the PVS0 programs.

In PVS0Expr.pvs, there is the grammar of the PVS0 expressions.

In more_lists.pvs, more_list2.pvs, more_list3.pvs there are properties related with types and lists.
