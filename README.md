# Welcome to PHP Less
### This is a library created by [xNotKing](https://xnotking.github.io) that allows you to code faster by making some complex php functions in one.
PD: This library alows you to code faster, but your website content wont be faster, native code is always faster.
### ip()
Gets the user ip address
### ip_details($ip)
Gets ip information, like city, etc example: 
$details = ip_details( ip() ) 
txt($details->city);
### env($en)
Gets environment variables information  example: env("db_name")
### add($file)
This is an abbreviation of include "file" example: add("db.php")
### txt($echo)
Txt prints provided text in your screen. (abrreviation of echo) example: txt("Hello World")