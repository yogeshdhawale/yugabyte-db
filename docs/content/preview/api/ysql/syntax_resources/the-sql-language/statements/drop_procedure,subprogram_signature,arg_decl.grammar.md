```output.ebnf
drop_procedure ::= DROP PROCEDURE [ IF EXISTS ]  
                   { subprogram_name ( [ subprogram_signature ] ) } 
                   [ , ... ] [ CASCADE | RESTRICT ]

subprogram_signature ::= arg_decl [ , ... ]

arg_decl ::= [ formal_arg ] [ arg_mode ] arg_type
```
