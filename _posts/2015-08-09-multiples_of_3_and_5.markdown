---
layout: post
problem: 1
title:  "Multiples of 3 and 5"
date:   2015-08-09 19:37:36
categories: javascript
permalink: /01
---

## **Problem**

  > If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.
  >
  > Find the sum of all the multiples of 3 or 5 below 1000.

## **Solution**

```javascript
var sum = 0;

for ( var i = 0; i < 1000; i++ ) {
  if ( i % 3 == 0 || i % 5 == 0 ) {
    sum+= i;
  }
}
```
