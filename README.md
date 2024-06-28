<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
   
</head>
<body>

<h1>Redis-Go</h1>

<h2>Description</h2>
<p>
    Trying to replicate redis, an in-memory db, concurrent and single threaded used mainly for caching operations, in Go, this is my first time using Go! Redis uses RESP for communication.
</p>


<h3>Prerequisites</h3>
<p>
    Make sure you have Go installed
</p>

<h3>Steps</h3>
<h4>Clone the repo and run the main server and then the client</h4>
<pre><code>
  go run main.go
  redis-cli
</code></pre>

<h2>Usage</h2>
<p>
   Have implemented just a few methods like SET,GET,HSET, HGET. It was fun learning.
</p>


<p>
    There is also a database.aof file that contains all executed command that runs incase of a crash, implemented for persistance of data. 
</p>



</body>
</html>
