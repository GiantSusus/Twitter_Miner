Twitter_Miner
=============
%% ---------------------
%% Main
%% ---------------------

Start erl with: erl -pa deps/*/ebin -pa ebin -config twitterminer

Then start program with main:start(), will run at 3 given times each day.

Will start scheduler, handler module and the loop.

Ip = "129.16.155.22".
Port = 8087.
Bucket = <<"Alpha">>.
ResultBucket = <<"Result">>.
