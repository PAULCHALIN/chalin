# chalin
<?php
require("connect.php");
?>
<?php
if(isset($_POST["submit"])){
    $name=$_POST["name"];
    $q=mysqli_query($connection,"INSERT INTO surn (firstname)VALUES('$name')");
    if($q){
        echo"success";
    }
    else{
        echo"failed";
    }
}
?>
CREATE TABLE studentdetails
(id(int(100) auto_increment primary_key,surname varchar(50) not null, firstname varchar(50) not null, class varchar(50) not null, amountpaying varchar(50)
 not null, term varchar(50) not null, dateofpayment varchar(50) not null, times varchar(50) not null  )
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=<, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="text.php" method="POST" enctype="multipart/form-data">
        <input type="text" name="name" placeholder="Name..."/>
</form>
</body>
</html>
# https://tea.xyz/what-is-this-file
---
version: 1.0.0
codeOwners:
  - '0x6e34D8f9ef30280C22c384a8f876E7Dc9592e33B'
quorum: 1
