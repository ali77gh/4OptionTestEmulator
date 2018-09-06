# 4OptionTestEmulator
the main question is : <br>
<b>when you can use random to answer 4-option tests:</b> <br>
code output:
~~~xml
first test ( normal mode )
--posetives : 4687
--negetive : 5313

second test (when you can remove 1 choice)
--posetives : 9993
--negetive : 7

third test (when you can remove 2 choice)
--posetives : 10000
--negetive : 0
~~~
<b>so:</b><br>
use random in normal mode -> not recommnded <br>
use random when you are sure 1 option is wrong -> yes <br>
use random when you are sure 2 option is wrong -> sure <br>
use random when you are sure 3 option is wrong -> :| <br>
<b>trust me its computer science ;)<b>

# test it yourself:
1. clone this repository 
2. simply run student_emulator.js
~~~bash
node student_emulator.js
~~~
