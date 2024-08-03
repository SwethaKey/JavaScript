# JavaScript


Variable ;
1. variable names are case sensitive; "a" and "A" is different.
2. only letters,digit,underscore(_) and special charater like $@ is not allowed¨.
3. only a letter, underscore(_) or $ should be 1st charater.(like _name, $name,name).
4. Reserved words connot be variable names.(inner word cannot be write as a variable name).
5. CamelCase we will use(like isfollow,fillName).


# Let, Const & Var

var = Variable can be re-declared & updated. A global scope variable. (we use 2015 year).(can change the variable value)(var will never use in Javascript now)
     var age = 35;
     var age = 40;
     var age = 50;
     console.log(age);

let = Variable cannot be re-declared but can be updated. A block scope variable.(cannot change the variable value and we can update)
  1. let age = 25;
     age = 30;
     age = 35;
     console.log(age);

  2. let a;
     console.log(a) # you will get output undefined

# 3. A block scope variable
    {
       let a = 5;
       let a = 10;(you will get error you cannot redefine inside block)
       console.log(a);
     }

    {
       let a = 10;
       console.log(a); (you can define different block and same variable name no problem)
    }

canst = Variable cannot be re-declared or updated. A block scope variable.(cannot change the variable value and update)
    const age = 30;
    age = 40;(you will get error while updating)
    age = 50;
    console.log(age);

    const a;
    console.log(a) # you will get error


# Datatypes in JS
# Primitive datatypes
   1. Number
     age = 25;
     typeof age;

   2. String
   3. Boolean
   4. Undefined
        let x;
           x (Undefined iutput)
           typeof x; (Undefined output)
      
   5. Null
        let x = null;
           x (Null Output)
           typeof x;(object output)
      
   6. BigInt
       let x = BigInt("123")
           x (123n output)
           typeof(x);
   7. symbol
        let y = Symbol("Hello!")
       
# NonPrimitive datatype

   Object = collection of values(Arrays,Functions)

   

