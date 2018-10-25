If you dont "Extend" your class, it will automatically by default extend "Object"
- inherits toString(), equals(), hashCode()
    - generally overwrite these methods in your object
    - equals() by default will return true if both objects are of the same class. 
        - so can change it to check parameters and varaibles within the classes
        - should change hashCode() value if you change how you view equality between objects 
    - hashCode() is an integer derived from an object

JAVA I/O

- I/O streams
- Flags in formatting???
    - has to do with System.out.* methods


BufferedReader is different in that it reads bytes, not characters.
- useful when you want to look for things other than char's. So like an integer. And if you used a normal fileReader that reads char's, you would have to one by one convert each char and see if it is an integer or not.

Generics let you abstract over a datastructure and other things
- supposed to help when working with multiple different types


Collection classes and interface 