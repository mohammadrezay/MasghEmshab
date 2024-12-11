# MasghEmshab
https://quera.org/problemset/10230
<?php
list($a, $b, $c)
		= explode(" ", readline("Enter 3 numbers: "));
	
$a = (int)$a;
$b = (int)$b;
$c = (int)$c;
if($a + $b + $c == 180 and $a > 0 and $b > 0 and $c > 0){
	echo "Yes";
}else{
	echo "No";
}
