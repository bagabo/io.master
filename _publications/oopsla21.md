---
title: "Dynaplex: Analyzing Program Complexity using Dynamically Inferred Recurrence Relations"
collection: publications
permalink: /publication/oopsla21
excerpt: 'In this paper we infer asymptotic worst case complexity using recurrence relations'
date: 2021-10-20
venue: 'Proceedings of the ACM on Programming Languages'
paperurl: 
citation: 'Didier Ishimwe, KimHao Nguyen, and ThanhVu Nguyen. 2021. Dynaplex: analyzing program complexity using dynamically inferred recurrence relations. <i>Proc. ACM Program. Lang. 5, OOPSLA, Article 138 (October 2021), 23 pages</i>.'
---
In this work, we introduce a new dynamic approach for
inferring the asymptotic complexity bounds of recursive programs. From program execution traces, we learn
recurrence relations and solve them using pattern matching to obtain closed-form solutions representing the
complexity bounds of the program. This approach allows us to efficiently infer simple linear recurrence relations
that represent nontrivial, potentially nonlinear polynomial and non-polynomial, complexity bounds such as O(n^{1.58}) for Karatsuba multiplication algorithm.
[Download paper here](https://nguyenthanhvuh.github.io/pubs/ishimwe2021dynaplex.pdf)
