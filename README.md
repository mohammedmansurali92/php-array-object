# php-array-object
<?php
 // array operator
 /*$numbers= array(10,15,20,25);
 echo $numbers[3];*/
 $numbers = array(10,15,20,25);
 $sum= $numbers[0]+ $numbers[1]+$numbers[2]+ $numbers[3];
 echo $sum;
 echo "<br>";
 $x1= array(10,"mansur",10.5);
 echo $x1[0]."<br>";
 echo $x1[1]."<br>";
 echo $x1[2]."<br>";
 echo "<br>";
 $x2= array(10, array("mansur","tahmina"),20.12);
 echo $x2[0]."<br>";
 echo $x2[1][0]."<br>";
 echo $x2[1][1]."<br>";
 echo $x2[2]."<br>";
 echo "<br>";
 $x3= array(10,12,"mansur",10.35);
 echo "<pre>";
 print_r($x3);
 echo "</pre>";
?>
