## If

------

```
fn main() {
	a := 10
	b := 20
	if a < b {
		println('$a < $b')
	} else if a > b {
		println('$a > $b')
	} else {
		println('$a == $b')
	}
}
```



`if`语句非常简单，和Go等众多语言类似。

但与类C语言不同的是，条件不需要`()`,但`{}`必须。

`if`也可以被用作表达式:

```
num := 777
s := if num % 2 == 0 {
	'even'
}
else {
	'odd'
}
println(s) // ==> "odd"
```