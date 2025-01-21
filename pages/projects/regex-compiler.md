---
layout: post
---

See full project, technical report, and source code here: [Scanner Generator](https://github.com/ColeStrickler/CompilerInfra/tree/main/projects/t1) 

This project takes in a spec for a compiler front-end scanner, that includes regular expressions and tokens to be produced when that regular expression is matched. Each regular expression is then tokenized, parsed into a parse tree, and then SDT techniques are used to compile the parse trees into NFAs. The NFAs can then be reduced to DFAs and dumped to a header file suitable for a scanner used in a compiler frontend.



![thompson](/assets/img/thompson.png)