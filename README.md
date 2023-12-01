# Own_language

## 編譯方法
- yacc -dv mycalc.y
- lex mycalc.l
- cc -o calc y.tab.c lex.yy.c [產生名為calc執行欓]
  
