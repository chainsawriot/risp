# risp
Lisp flavored R

Proposed syntax:

```{lisp}
## heavily inspired by the simplicity of Scheme.
## using python style [] to create vector
(define my-vector [3.5 2.7 3.8 4.5 5.8])
## using python style {} to create data.frame
(define my-dataframe {col1: [3 6 7], 
                      col2: [TRUE FALSE TRUE], 
					  col3: ['Peter', 'Paul', 'Mary']})
(mean my-vector)
(define (z-score x y)
   (/ (- x (mean y))
      (sd y)))
(z-score 5 my-vector)
```
