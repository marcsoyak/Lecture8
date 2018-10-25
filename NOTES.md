If you dont "Extend" your class, it will automatically by default extend "Object"
- inherits toString(), equals(), hashCode()
    - generally overwrite these methods in your object
    - equals() by default will return true if both objects are of the same class. 
        - so can change it to check parameters and varaibles within the classes
        - should change hashCode() value if you change how you view equality between objects 
    - hashCode() is an integer derived from an object
