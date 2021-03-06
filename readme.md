LibNotifyWatch
==============
Log system-posted notifications
-------------------------------

by Elias Limneos
----------------
web: limneos.net

email: iphone (at) limneos (dot) net

twitter: @limneos

Intro
-----

LibNotifyWatch is useful mostly to developers and in particular, those 
who are bored to hook and log system notifications.
It hooks several notification-posting functions and writes them to 
/var/log/syslog using NSLog. (syslogd must be running).
It provides options to select which notification-posting functions to 
watch/log , as well as filtering for notification names.


Settings
--------

LibNotifyWatch offers a preferenceBundle in which you can define which 
functions to watch and write to /var/log/syslog.
You can turn global logging on/off, define which functions to watch in 
particular, or define a string filter so you can only
log notifications matching your filter.

Open Source
-----------

LibNotifyWatch is open-source, any help / modification / addition is 
appreaciated.


Compile
-------

LibNotifyWatch is compiled using Theos. For more information about 
Theos/Logos, visit http://bit.ly/af0Evu and http://hwtt.net/ths


Thanks
------

Thanks to:

 Optimo for being my mentor

 DHowett for Theos/Logos and all the background work he's done for the community

 Saurik for cycript and everything else

 Many other developers from IRC from which I've learned a lot, including
 rpetrich, BigBoss, DB42, kennytm, chpwn, mringwal, TheZimm, Yllier


