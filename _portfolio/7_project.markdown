---
layout: post
title: Polymorphic Typed Language
description: 
img:
---

Created an explicit parametric polymorphic typed language that can be used via a shell interface. Previously in this class we created several different interpreters and parsers. My partner and I built off of this work to create a language which checks types before evaluating. The language is built on top of Python.

It can compute inputs such as:

	---
	(+ 3 4)  -> 7
	---

But will reject:

	---
	(+ 3 false) -> error
	---

And return an error code.

The language can also handle first class functions.

	---
	(defun add1 (a) ( int) (+ a 1) )
	(defun istrue (a) ( bool) true )
	(defun map (a b) (<T> (-> (<T>) <S>)) (b a))
	(map (map 3 add1) add1)   -> 5
	(map (map true istrue) add1)  -> error
	---

And generic types.

	---
	(defun map2 (a b) ((-> (<T>) <S>) <T>) (a b))
	(map2 add1 (map2 add1 3))   -> 5
	(map2 add1 (map2 istrue true))  -> error
	(defun curry (f) ((-> (<S> <T>) <U>)) (function (a) (<S>) (function (b) (<T>) (f a b))))
	(curry +)
	(defun pair (x y) (<T> <S>) (function (f) ((-> (<T> <S>) <U>)) (f x y)))
	(defun sum (a b) (int int) (+ a b)) 
	(defun test1 () () ((pair 3 4) sum))    -> This should pass
	(defun test2 () () ((pair 3 false) sum))    -> This should fail
	---


<b>What I learned:</b>
- Parsing can be very difficult
- aoeeu

<b>Website: </b> <a href="https://github.com/LucyWilcox/PL-2016/blob/master/final.py">On GitHub</a>

<b>For: </b>Programing Languages course

<b>During: </b>Fall 2016

<b>Collaborators: </b>Xiaofan Wu

<b>Skills: </b>Python, programing language design
