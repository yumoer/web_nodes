## 匿名函数

JavaScript 可以将函数作为数据使用。作为函数本体，它像普通的数据一样，不一定要有名字。默认名字的函数被称之为匿名函数。 如下示例:

```javascript
function (a){return a;}
```

匿名函数的两种用法:


## 自调函数

所谓自调函数就是在定义函数后自行调用。如下示例:

```javascript
(function(){
```

上述代码的含义如下:


```javascript
(function(name){
```

上述代码的含义如下:


## 回调函数
function add(a, b){
```

上述代码中，函数 one() 和 two() 都作为函数 add() 的参数传递。所以函数 one() 和 two() 都是回调函数。



function fn( f, args ){
```

上述代码还可以编写成如下方式:

```javascript
function fn( args ){
```

上述两段代码的区别在于:

```javascript
var f = fn( 10 );// function add(){ return 10 + 10; }
```