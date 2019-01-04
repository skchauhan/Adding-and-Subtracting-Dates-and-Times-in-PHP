This adds 2 days to the current date:

$date = date('Y-m-j');
$newdate = strtotime ( '+2 day' , strtotime ( $date ) ) ;
$newdate = date ( 'Y-m-j' , $newdate );

echo $newdate;


===========================
This adds 2 months to the current date:

$date = date('Y-m-j');
$newdate = strtotime ( '+2 month' , strtotime ( $date ) ) ;
$newdate = date ( 'Y-m-j' , $newdate );

echo $newdate;


=============================
This adds 2 years to the current date:

$date = date('Y-m-j');
$newdate = strtotime ( '+2 year' , strtotime ( $date ) ) ;
$newdate = date ( 'Y-m-j' , $newdate );

echo $newdate;
============================
This subtracts 6 hours from the current date:

$date = date('Y-m-j');
$newdate = strtotime ( '-6 hour' , strtotime ( $date ) ) ;
$newdate = date ( 'Y-m-j' , $newdate );

echo $newdate;

==============

This subtracts 10 minutes from the current date:

$date = date('Y-m-j');
$newdate = strtotime ( '-10 minute' , strtotime ( $date ) ) ;
$newdate = date ( 'Y-m-j' , $newdate );

echo $newdate;
===============

This adds 1 year to the date 2012-11-25:

$date = date('2011-11-25');
$newdate = strtotime ( '+1 year' , strtotime ( $date ) ) ;
$newdate = date ( 'Y-m-j' , $newdate );

echo $newdate;
