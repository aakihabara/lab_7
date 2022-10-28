<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Коньков Никита Алексеевич</p>
<br><br><br>
<p align = "center">Лабораторная работа №7<br><b>«Разработка серверных скриптов»</b><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2022 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p> <b>HTML</b> (или же HyperText Markup Language) - стандартизированный язык разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора. </p>

<p><b>PHP</b> (произносится пи-эйч-пи́) — скриптовый язык программирования, созданный для генерации HTML-страниц на веб-сервере и работы с базами данных. На сегодняшний момент поддерживается подавляющим большинством представителей хостингов. Входит в «LAMP» — «стандартный» набор для создания веб-сайтов.</p>

<h1 align = "center">Цели и задачи</h1>

<p>1. Создайте переменную $var и присвойте ей значение 'hello'. Обращаясь к отдельным символам этой строки выведите на экран символ 'h', символ 'e', символ 'o'.</p>

<p>2. Напишите скрипт, который считает количество секунд в часе.</p>

<p>3. Переделайте приведенный код так, чтобы в нем использовались операции +=, -=, *=, /=, ++, --. Количество строк кода при этом не должно измениться. Код для переделки:</p>

```php
<?php
	$var = 1;
$var = $var + 12;
$var = $var - 14;
$var = $var * 5;
$var = $var / 7;
$var = $var + 1;
$var = $var - 1;
echo $var;
?>
```

<p>4. Создайте переменную $a и присвойте ей значение 3. Выведите значение этой переменной на экран.</p>

<p>5. Создайте переменные $a=10 и $b=2. Выведите на экран их сумму, разность, произведение и частное (результат деления).</p>

<p>6. Создайте переменные $c=15 и $d=2. Просуммируйте их, а результат присвойте переменной $result. Выведите на экран значение переменной $result.</p>

<p>7. Создайте переменные $a=10, $b=2 и $c=5. Выведите на экран их сумму.</p>

<p>8. Создайте переменные $a=17 и $b=10. Отнимите от $a переменную $b и результат присвойте переменной $c. Затем создайте переменную $d, присвойте ей значение 7. Сложите переменные $c и $d, а результат запишите в переменную $result. Выведите на экран значение переменной $result.</p>

<p>9. Создайте переменную $text и присвойте ей значение 'Привет, Мир!'. Выведите значение этой переменной на экран.</p>

<p>10. Создайте переменные $text1='Привет, ' и $text2='Мир!'. С помощью этих переменных и операции сложения строк выведите на экран фразу 'Привет, Мир!'.</p>

<p>11. Создайте переменную $name и присвойте ей ваше имя. Выведите на экран фразу 'Привет, %Имя%!'. Вместо %Имя% должно стоять ваше имя.</p>

<p>12. Создайте переменную $age и присвойте ей ваш возраст. Выведите на экран 'Мне %Возраст% лет!'.</p>

<p>13. Создайте переменную $text и присвойте ей значение 'abcde'. Обращаясь к отдельным символам этой строки выведите на экран символ 'a', символ 'c', символ 'e'.</p>

<p>14. Дана произвольная строка, например, 'abcde'. Поменяйте первую букву (то есть букву 'a') этой строки на '!'.</p>

<p>15. Создайте переменную $num и присвойте ей значение '12345'. Найдите сумму цифр этого числа.</p>

<p>16. Напишите скрипт, который считает количество секунд в часе, в сутках, в месяце.</p>

<p>17. Создайте три переменные - час, минута, секунда. С их помощью выведите текущее время в формате 'час:минута:секунда'.</p>

<p>18. Создайте переменную, присвойте ей число. Возведите это число в квадрат (это значит нужно умножить его само на себя). Выведите его на экран.</p>

<p>19. Переделайте этот код так, чтобы в нем использовались операции +=, -=, *=, /=. Количество строк кода при этом не должно измениться.</p>

```php
$var = 47;
$var = $var + 7;
$var = $var - 18;
$var = $var * 10;
$var = $var / 20;
echo $var;
```

<p>20. Переделайте этот код так, чтобы в нем использовалась операция .=. Количество строк кода при этом не должно измениться.</p>

```php
$text = 'Я';
$text = $text.' хочу';
$text = $text.' знать';
$text = $text.' PHP!';
echo $text;
```

<p>21. Переделайте этот код так, чтобы в нем использовались операции ++ и --. Количество строк кода при этом не должно измениться.</p>

```php
$var = 10;
$var = $var + 1;
$var = $var + 1;
$var = $var - 1;
echo $var;
```

<p>22. Переделайте этот код так, чтобы в нем использовались операции ++, -- , +=, -=, *=, /=. Количество строк кода при этом не должно измениться.</p>

```php
$var = 10;
$var = $var + 7;
$var = $var + 1;
$var = $var - 1;
$var = $var + 12;
$var = $var * 7;
$var = $var - 15;
echo $var;
```

<p>23. <a href = "https://www.codewars.com/kata/534ea96ebb17181947000ada">Breaking chocolate problem</a></p>
<p>24. <a href = "https://www.codewars.com/kata/5552101f47fc5178b1000050">Playing with digits</a></p>
<p>25. <a href = "https://www.codewars.com/kata/52988f3f7edba9839c00037d">The reject() function</a></p>
<p>26. <a href = "https://www.codewars.com/kata/5506b230a11c0aeab3000c1f">Deodorant Evaporator</a></p>
<p>27. <a href = "https://www.codewars.com/kata/57bf599f102a39bb1e000ae5">Fibonacci's FizzBuzz</a></p>
<p>28. <a href = "https://www.codewars.com/kata/5901f361927288d961000013">Product of Array Items</a></p>
<p>29. <a href = "https://www.codewars.com/kata/546f922b54af40e1e90001da">Replace With Alphabet Position</a></p>
<p>30. <a href = "https://www.codewars.com/kata/5679aa472b8f57fb8c000047">Equal Sides Of An Array</a></p>
<p>31. <a href = "https://www.codewars.com/kata/57a2013acf1fa5bfc4000921">Calculate average</a></p>
<p>32. <a href = "https://www.codewars.com/kata/5a995c2aba1bb57f660001fd">Scrolling Text</a></p>
<p>33. <a href = "https://www.codewars.com/kata/57ed30dde7728215300005fa">Bumps in the Road</a></p>
<p>34. <a href = "https://www.codewars.com/kata/582746fa14b3892727000c4f">Coding Meetup #1 - Higher-Order Functions Series - Count the number of JavaScript developers coming from Europe</a></p>
<p>35. <a href = "https://www.codewars.com/kata/5b39e3772ae7545f650000fc">Remove duplicate words</a></p>

<h1 align = "center">Решение</h1>  

```php
<?php
	echo "Задание 1 <br>";
	$var = 'Hello';
	echo "$var world!";
?>
<br>
<?php
	echo "Задание 2 <br>";
	$res = 60*60;
	echo $res . " секунд в часе";
?>
<br>
<?php
	echo "Задание 3 <br>";
	$var = 1;
	$var += 12;
	$var -= 14;
	$var *= 5;
	$var /= 7;
	$var++;
	$var--;
	echo $var;
?>
<br>
<?php
	echo "Задание 4 <br>";
	$a = 3;
	echo $a;
?>
<br>
<?php
	echo "Задание 5 <br>";
	$a = 10;
	$b = 2;
	echo $a + $b;
	echo "<br>";
	echo $a - $b;
	echo "<br>";
	echo $a * $b;
	echo "<br>";
	echo $a / $b;
?>
<br>
<?php
	echo "Задание 6 <br>";
	$c = 15;
	$d = 2;
	$result = $c + $d;
	echo $result;
?>
<br>
<?php
	echo "Задание 7 <br>";
	$a = 10;
	$b = 2;
	$c = 5;
	echo $a + $b + $c;
?>
<br>
<?php
	echo "Задание 8 <br>";
	$a = 17;
	$b = 10;
	$c = $a - $b;
	$d = 7;
	$result = $c - $d;
	echo $result;
?>
<br>
<?php
	echo "Задание 9 <br>";
	$text = "Привет, Мир!";
	echo $text;
?>
<br>
<?php
	echo "Задание 10 <br>";
	$text1 = "Привет,";
	$text2 = "Мир!";
	echo $text1 . $text2;
?>
<br>
<?php
	echo "Задание 11 <br>";
	$name = "Никита";
	echo "Привет, " . $name . "!"
?>
<br>
<?php
	echo "Задание 12 <br>";
	$age = 19;
	echo "Мне " . $age . " лет!"
?>
<br>
<?php
	echo "Задание 13 <br>";
	$text = "abcde";
	echo $text[0] . $text[2] . $text[4];
?>
<br>
<?php
	echo "Задание 14 <br>";
	$text = "abcde";
	echo str_replace("a", "!", $text);
?>
<br>
<?php
	echo "Задание 15 <br>";
	$num = '12345';
	echo $num[0] + $num[1] + $num[2] + $num[3] + $num[4];
?>
<br>
<?php
	echo "Задание 16 <br>";
	$hr = 60*60;
	$dy = $hr * 24;
	$mnth = $dy * 30;
	echo $hr . " / " . $dy . " / " . $mnth;
?>
<br>
<?php
	echo "Задание 17 <br>";
	$hr = date('H');
	$min = date('i');
	$sec = date('s');
	echo $hr . ":" . $min . ":" . $sec
?>
<br>
<?php
	echo "Задание 18 <br>";
	$num = rand(1,10);
	echo($num*$num);
?>
<br>
<?php
	echo "Задание 19 <br>";
	$var = 47;
	$var += 7;
	$var -= 18;
	$var *= 10;
	$var /= 20;
	echo $var;
?>
<br>
<?php
	echo "Задание 20 <br>";
	$text = 'Я';
	$text .= ' хочу';
	$text .=' знать';
	$text .=' PHP!';
	echo $text;
?>
<br>
<?php
	echo "Задание 21 <br>";
	$var = 10;
	$var++;
	$var++;
	$var--;
	echo $var;
?>
<br>
<?php
	echo "Задание 22 <br>";
	$var = 10;
	$var += 7;
	$var++;
	$var--;
	$var += 12;
	$var *= 7;
	$var -= 15;
	echo $var;
?>
```

<h1 align = "center">CODEWARS</h1>

<p>23. Breaking chocolate problem</p>

```php
function breakChocolate ($n, $m) {
  
  if($n * $m ==1){ 
  return 0;
  }else{
  return $n * $m -1;}
  
};
```

<p>24. Playing with digits</p>

```php
function digPow($n, $p) {
  $res = 0;
  $num = str_split($n);
  foreach($num as $x){
    $res += $x ** $p;
    $p++;
  }
  
  if($res % $n == 0)
    return $res / $n;
  else
    return -1;
}
```

<p>25. The reject() function</p>

```php
function reject($array, $predicate) {
  $arr = array();
  for($i = 0; $i < count($array); $i++){
    if(!$predicate($array[$i])){
      array_push($arr, $array[$i]);
    }
  }
  return $arr;
}
```

<p>26. Deodorant Evaporator</p>

```php
function evaporator($content, $evap_per_day, $threshold) {
  $good = $content * $threshold * 0.01;
  $count = 0;
    while($content >= $good){
      $count++;
      $content *= 1 - ($evap_per_day * 0.01);
    }
  return $count;
}
```

<p>27. Fibonacci's FizzBuzz</p>

```php
function fibs_fizz_buzz($n) {
  $res = [1, 1];
  if($n == 1){
    return [1];
  }
  else if($n == 2){
    return $res;
  }
  else{
    $temppr = 1;
    for($i = 1; $i < $n - 1; $i++){
      $temp = $res[$i] + $res[$i - 1];
      array_push($res, $temp);
    }
    
    for($i = 0; $i < count($res); $i++){
      if(($res[$i] % 3 == 0) && ($res[$i] % 5 == 0)){
        $res[$i] = "FizzBuzz";
      }
      else if($res[$i] % 5 == 0){
        $res[$i] = "Buzz";
      }
      else if($res[$i] % 3 == 0){
        $res[$i] = "Fizz";
      }
    }
    return $res;
  }
}
```

<p>28. Product of Array Items</p>

```php
function product($a) {
  $count = 1;
  if(($a == null) || (count($a) == 0)){
    return null;
  }
  else{
    for($i = 0; $i < count($a); $i++){
      $count *= $a[$i];
    }
  }
  return $count;
}
```

<p>29. Replace With Alphabet Position</p>

```php
function alphabet_position(string $s): string {
  $res = [];
  for($i = 0; $i < strlen($s); $i++){
     if (preg_match("/[a-zA-Z]/", $s[$i])){
       array_push($res, ord(strtolower($s[$i])) - 96);
     }
  }
    
  return implode(" ", $res);
}
```

<p>30. Equal Sides Of An Array</p>

```php
function find_even_index($arr){
  
  for($i = 0; $i < count($arr); $i++){
    $first = array_slice($arr, 0, $i);
    $last = array_slice($arr, $i + 1);
    
    if(array_sum($first) == array_sum($last)){
      return $i;
    }
  }
  
  return -1;
}
```

<p>31. Calculate average</p>

```php
function find_average($array): float {
  $count = 0;
  for($i = 0; $i < count($array); $i++){
    $count += $array[$i];
  }
  if(count($array) == 0){
    return 0;
  }
  else
    return $count / count($array);
}
```

<p>32. Scrolling Text</p>

```php
function scrollingText($text) {
  $res = array();
  array_push($res, strtoupper($text));

  for($i=0; $i < strlen($text) - 1; $i++) {
    $a = strtoupper(substr($text, 0, 1));
    $b = strtoupper(substr($text, 1));
    $text = $b.$a;
    array_push($res, $text);
  }

  return $res;
}
```

<p>33. Bumps in the Road</p>

```php
function bump($x) {
  $countBumps = 0;
  for($i = 0; $i < strlen($x); $i++){
    if($x[$i] == "n")
      $countBumps++;
  }
  
  ($countBumps > 15) ? $str = "Car Dead" : $str = "Woohoo!";
  return $str;
}
```

<p>34. Coding Meetup #1 - Higher-Order Functions Series - Count the number of JavaScript developers coming from Europe</p>

```php
function count_developers($a) {
  $count = 0;
  foreach($a as $x){
    if(($x['continent'] == 'Europe') && ($x['language'] == 'JavaScript'))
      $count++;
  }
  
  return $count;
}
```

<p>35. Remove duplicate words</p>

```php
function removeDuplicateWords($s) {
  $res = implode(" ", array_unique(explode(" ", $s)));
  return $res;
}
```

<h1 align = "center">Вывод</h1>
<p>Опираясь на материал с сайта w3school, а также свои остаточные знания, Я вспомнил базовые функции php и решил лабораторную работу и задачи на codewars.</p>