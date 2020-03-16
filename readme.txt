import threading

def printit():
  threading.Timer(5.0, printit).start()
  print "Hello, World!"

printit()


GET => http://172.16.16.38/ThreadingTasks/requists.php?myname=YOURNAME

POST => http://172.16.16.38/ThreadingTasks/requists.php

{

"isPrime" : 1,

"No" : ##,

"myname":"YOURNAME"

}
