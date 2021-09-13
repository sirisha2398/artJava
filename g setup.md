:beginner: _**SET UP**_  

:link: [git](https://git-scm.com/downloads)

:link: [jdk1.8](https://www.oracle.com/in/java/technologies/javase/javase-jdk8-downloads.html)

JAVA_HOME = C:\Program Files\Java\jdk1.8.0_191  
BINARIES : C:\Program Files\Java\jdk1.8.0_191\bin  
LIBRARIES : C:\Program Files\Java\jdk1.8.0_191\lib (java archives)


:boom: Bugs
  
:lock: **Unable to find main method while running**  

```sh
$ java -cp . <classfile>
```

:lock: **FAILED TO CREATE VIRTUAL MACHINE (ON MAC)**  
:key: **add this line in sts.ini file**  


-vm
/Library/Java/JavaVirtualMachines/jdk1.8.0_301.jdk/Contents/Home/bin/java

https://stackoverflow.com/questions/32845708/where-to-find-sts-ini-file/68775329#68775329