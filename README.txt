---CSS---
Для чего нужны свойства вида -moz-box-sizing, -moz-border-radius, -wap-accesskey?

Чему будет равно знаечение text-indent для h1 (в px)?
body {
  font-size: 12px;
  text-indent: 3em;  /* i.e., 36px */
}
h1 { font-size: 15px }

Что такое em? В чём отличия от px?

Что выведется на экран?
h1 + p {
  color: green;
}
<h1>Header</h1>
sample text
<p>First paragraph</p>
<p>Second paragraph</p>

Как задать стиль классу, не используя запись .classname {}?

Перечислите псевдо-селекторы? Почему они "псевдо"?

Расчёт приоритета назначения стилей

---JS---
var a = 55;
var myFunc = function() { 
  console.log(a); 
  var a = 10;  
}
myFunc(); // Что выведет на экран?

Типы данных JS?

Результат вычислений:
1) "example" + 10 * 2
2) 10 + "" + 30
3) 50 * "example"

Анонимные функции, замыкания, 

---PHP---
Что означает E_ALL & ~E_NOTICE? 
E_ALL ^ E_NOTICE?

$a = -20;
$b = -6;
$c = $a % $b // $c ?

echo ((true ? 'true' : false) ? 't' : 'f');
