# 110502503_顏婕葳
## MiniLISP
此程式碼使用python以實現MiniLISP的簡易編譯器
## Overview
LISP is an ancient programming language based on S-expressions and lambda calculus.

All operations in Mini-LISP are written in parenthesized prefix notation. For example, a simple mathematical formula “(1 + 2) * 3” written in Mini-LISP is:

```
(* (+ 1 2) 3)
```

As a simplified language, Mini-LISP has only three types (Boolean, number and function) and a few operations.
## Type Definition
* Boolean: Boolean type includes two values, #t for true and #f for false.
* Number: Signed integer from −(2^31) to 2^31 – 1, behavior out of this range is not defined.
* Function: See Function.
![image](https://github.com/WeiYen1103/Me/assets/144879901/9a61b506-d8bb-48fa-8e5d-81d9f25b58f2)
![image](https://github.com/WeiYen1103/Me/assets/144879901/62b368e2-4127-49ad-bf74-1079fa545a97)

