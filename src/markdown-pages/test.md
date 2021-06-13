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
