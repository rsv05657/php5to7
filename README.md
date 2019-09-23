# php5to7
php5.x to 7.x migration tools

## Overview
Our automatically converts php5.x programs to work with php7.

## Features
1. Conversion of obsolete specifications  
1.1 Replace the method with the same name as the class name (old constructor style) with the correct name.  
1.2 Replace =& with =  
1.3 Rewrite variables / methods using new templorary name (eg yield)  

## How to work.
1. clone project.
2. composer install
3. ./bin/php5to7 <<option>> <<folder>> 
4. Test!

## Options
--overwrite
--backup
--disable-convert
