Start off python code - oppotunities to fail

Microservices architecture: Lots of small components working together.
Sped up delivery cycle

Aim: Graceful failure behaviour. Easy to diagnose errors when these occur

Want: An easy way to write programs which encampulusates all the behaviours of a program

What can we guarantee? 

Break into smaller functions - data processing - any result in guarantees the same result out

What can't we guarantee?
Any external service call, I/O

Write small functions that keep a failure scenario

Thread these together with a for comp. Nothing like a forloop in c++

//this could be hard to explain
For comp digression - series of flatMaps

Handle the error case in one general way - eg logging

Guarantees of returning to client

Using the type system - we can use the compiler to enforce giving a result back to the client

If any of the steps fail there is an enforced behaviour


