# Patches with some custom opcodes and statements for Python.
### CPython version is 3.9 (3.9.14) 
#### LOAD_AVOEVODIN OPCODE that is used instead of LOAD_FAST (with 0 arg) and LOAD_CONST
#### Until statement
#### Increment and Decrement with ++ and --.
 
### Notes for Until Patch:
1) ast_opt.c is not required defenitly. Everything works without it's changes.
2) String with PyAST_Validate was commented because until statement hasn't passed through that validation. But correctly worked without that one. 
