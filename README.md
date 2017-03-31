# saif-joker
first day

hello my name is saif. And today is my first day at GitHub

<?php
$y;
$count=0;
function fun($x)   
{
      
    if($x=="a"||$x=="e"||$x=="i"||$x=="o"||$x=="u")
    {
     return true;
     $count++;
    }                
    
    else
    
    return false;               
}

function fun1($y)
{
    return ($y*$y);
}

$arr2=array("a","c","e","w","y","w","e","p");  

//$arr3=array(12,56,3,4,5,7,8,8,9);



$res_array1=array_filter($arr2,"fun");

var_dump($res_array1);

$arr3=array_map("fun",$arr2);

var_dump($arr3);
?>
