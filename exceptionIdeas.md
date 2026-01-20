# ExceptionIdeas

## 1. Single ideas explained
- try: to excute certain lines and code(Literally means try a certain code disregarding its correctness) 
- catch: if a error happens in a try statement we go to this line of code and execute it 

    Real life example

    try{
        int x = 10 / 0; 
    }
    catch(Exception e){
        System.out.println("Code will not run");
    }

- Exception e: 
Java does not explode when hit with a type of exception. 
Because it is an object oriented programming java creates an object when met with this circumstance. 
Thus, we catch the exception that has occurred and run the code inside of catch.

- System.exit(0)
Forces the code to stop entirely. 
Similar to a return statement in a sense that it ends the code but a more powerful one.

**Can even kill "Finally"


- Finally 
Finally runs disregarding of an error happening or not.
Despite the correctness of the code finally always runs.

