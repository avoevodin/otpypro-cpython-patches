# Patches with some custom opcodes and statements for Python.

## Notes for Until Patch:
1) ast_opt.c is not required defenitly. Everything works without it's changes.
2) String with PyAST_Validate was commented because until statement hasn't passed through that validation. But correctly worked without that one. 
