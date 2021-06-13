---
title: Test
path: "/test"
date: 2019-05-04
---

Shell

```shell
echo -n "Hello World"
Hello World
```

Another shell

```shell
echo -n "Hello World"
123
```

Shell with output line

```shell{outputLines: 2}
echo -n "Hello World"
Hello World
```

Another shell with output line

```shell{outputLines: 2}
echo -n "Hello World"
123
```

Javascript with highlighted lines

```javascript{1-2}
function add(x, y) {
  return x + y
}
```

Shell with highlighted lines and output lines

```shell{2-3,5}{outputLines: 2}
echo -n "Hello World"
123
Hello
123
echo -n Hello
Hello
```

Shell with only output lines

```shell{outputLines: 2-3, 4-7}
echo -n hello
123
this is 1235
hello
ABC=XYZ
heloo
hello
hello
```

Diff for javascript

```diff-javascript
+function(x,y) {
-function(x) {
  return x + y;
}
```

diff for python with highlighting

```diff-python{2-3}
+ def f(x,y):
- def f(x):
  return x + y
```

Diff no language

```diff
+function(x,y) {
-function(x) {
  return x + y;
}
```
