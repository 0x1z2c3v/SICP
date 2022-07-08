# Lecture 1: A brief introduction of Lisp

## Techs

* black-box abstraction
* conventional interfaces
* metalinguistic abstraction

## Language

* primitive elements
* means of combination
* means of abstriction

## Lisp 

### primitives

* operator
* operand

### combination

### abstraction

```lisp
(DEFINE A (* 5 5))
(DEFINE (SQUARE X) (* X X))  // syntactic sugar
(SQUARE 10) -> 100
(DEFINE SQUARE (LAMBDA (A) (* A A)) : make a procedure
(DEFINE (ABS X) (COND ((< X 0) (-X)))
        	    (COND ((= X 0) (0)))
                (COND (( > X 0) (X))))
```





