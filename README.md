kwttd
=====

* port 21151

## Protocol:(base64)

app
* 001 NOTIFY: WHO'S MAC STARTS WITH xxx
* 101 REQUIRE: xxxyyy TURN ON
* 102 REQUIRE: xxxyyy TURN OFF
* 201 GET: xxxyyy PLEASE GIVE ME YOUR INFOMATION

switch
* 301 REPLY: MY MAC IS xxxyyy
* 302 REPLY: DONE TURN ON
* 303 REPLY: DONE TURN OFF
* 304 REPLY: MY INFORMATION IS ...
