readline
========

read line module for nodejs. Read a file line by line.



Example
=======

```
  var readline = require('readline');
  var rl = readline("./somefile.txt");
  rl.on("line", function (line){
    //do something with the line of text
  });
  rl.on('error', function (e){
    //something went wrong
  });
```
