# sqlEq
A repo for SQL equivalent

# z3 update
needs to build on z3 4.6 version:
github link: https://github.com/Z3Prover/z3/releases

# update from calcite relnode to z3 relnode
1. In algeNodeParser folder, it parser from RelNode to my self defined data strcutre AlgeNode.
   you need to update from calcite relNode to odps relNode in all source file in AlgeNodeParser folder.
   For example, in FilterParser, you need to update from LogicalFilter to OdpsLogcialFilter
2. Update get the table name in TableParser

# test case
1. check SimpleTest in test/java/SimpleQuery/Tests.
