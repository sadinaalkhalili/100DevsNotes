# 100DevsNotes

JQuery, ECMAscript tea

NODE JS 

Synchronus vs Asynchronus
JavaScript is single threaded - synchronus
How do we make API calls and keep scrolling?
because of the enviroment in which we run javascript (the browser), browsers have a bunch of APIs that are asynchronus
such as DOM API (Api that is used to manipulate using Javascript) + developer modzilla

but how do we handle with the response coming from browser?
promises, callbacks, async and await.

setTimeout(),SetInterval() are web APIs they're not part of the JS.
setTimeout() --> Event LOOP
fact: even if setTimeout is set to zero, the code was already handed to browser

Old Way vs New Way
CallBacks --> have a function that takes another function as an argument -- higher order function
fact: in a call back we don't pass the function, we pass the word
but they can be hard to read CALLBACK HELLLLL PYRAMID OF DOOM

make it more readable? how?
       *Promises*

An object that may have a value in the future
states = pending, fulfilled ,rejected
methods = then,catch, upon resolving then the then method is fired and vise versa

example: Fetch API, most web APIs return promises

asynch/await --> promises that read good cause there is till chaining
make synchronus code look synchronus 


















