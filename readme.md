Redux middlewere => are simply the function which have access to every action dispatched to the store they cam modify that action

What is ECMA6?
ECMA6 is a major a update in js language. Major changes were introduced in this version
like let, const , promises and template literals block scoping etc


What is event loop
ans=>So before event loop the js engine uses call stack a stack data to manage excution contexts
and function contexts. when we excute js script it cretaes global excution contexts and push 
it to the top of call stack and when ever a function is called the engne pushes the functional context 
on top of the stack . and after completion it pop of that context.but browser in addtion to the call stack
also have browser APIs so when we excutes async task like set timeout the call stack sends this tasks
to web APIs to complete and upon completion their callbacks are added to the callback queue. the 
event loop is a constantly running process that monitors both the call queue and stack and if the 
stack is not empty the loop waits untill it is empty then it pushes the callback to the stack

		


What is excution context?
It is simply env in the given file . for eg there is global env or scope and global env can container other functions which creats 
functional context.
