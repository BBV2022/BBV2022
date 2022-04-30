Hi, my name is Bogdan. 
I am a beginer in php.
I'm tring to import in my application the Euro Currency from the webpage   https://bnr.ro/curs-de-schimb-524.aspx

I have use the following code:
<?php
$content = file_get_contents('https://bnr.ro/curs-de-schimb-524.aspx');
echo $content;
?>

But, I would like to bring only the follwing values for EURO
21apr.2022 4,9441
26apr.2022 4,9457
27apr.2022 4,9474
28apr.2022 4,9475
29apr.2022 4,9480

Do you know how to do it?
