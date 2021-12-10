- Java was developed by James Gosling in 1995
- Scala was developed by Martin Odersky in 2004
- Python was developed by Guido von Rossum in 1991
- Sample Scala class Employee: 
###### Case Class Employee(empId:Int, empName:String)
- REPL - Read Evaluate Print Loop
- sys.exit or :q to quit scala console
- val: immutable, var: mutable
- Types of variables: Instance variables, local variable, method parameter variable
- Instance/Field/object variable: properties of a class, when you have a class, you define some var inside the variable, we call these as instance variable, can be immutable/mutable.
- Local/Block variable: defined inside your object. cannot be accessible outside the object/block, can be mutable/immutable
- method-parameter variable: write when you define a method, always be immutable (val)

###### Assigning multiple variables in a single line: 3 ways
- val (name:String,age:Int,sal:Float)= Tuple3("Esho",23,1222f)
- val (name:String,age:Int,sal:Float)=("Haider",25,1333f)
- val (name,age,sal)=("Sanju",26,1222f)



