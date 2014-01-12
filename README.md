##########################################################################
```
(scheme->ruby
 (lambda (repl)
  (print (eval (read)))))
```

```
(ruby->scheme
 (lambda (repl)
  (print
   (eval
    (read)))))
```
##########################################################################
 Title : repl.reverse ruby lisp like evaluator
 Author : Stuart Gerstein <stu@rubyprogrammer.net>
 Date : 2014-01-11
 Requires : Ruby >2
 Category : Utilities and other for the fuck of it work arounds
##########################################################################
 Description
 o "repl"
 o NOTES: Edification /ˌedəfiˈkāSHən/
 this is a fun way to grok interpreters with so called evil syntax!
 Examples:
 type (repl) and let the fun begin... there is no builtin buffering
 for more fun try (eval (repl)) and impliment your own call/cc
 and evil functions while doing lines in applicative ordered
 ruduction based syntax primative assignment all in lambda form =)
##########################################################################
