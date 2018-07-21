## Simple tcp server in Golang-Go

install golang-go:
<pre>
sudo apt update && sudo apt install -y golang-go
</pre>

run tcp server:
<pre>
go run server.go
</pre>

checking if it works (in another shell console):
<pre>
echo -n "test tcp server" | nc localhost 3344
</pre>

needed output:
<pre>
Message received
</pre>
