# Constructors-and-Destrustors
## Theory:
#### Constructors:
A constructor in C++ is a special member function of a class that is automatically called when an object of the class is created. Its purpose is to initialize the object's data members and allocate any resources it may need.Constructors have the same name as the class and do not have a return type, not even void. They can be overloaded, which means a class can have multiple constructors with different parameter lists.
The basic syntax of the constructor is given below:<br>
class class_name{<br>
  private: <br>
  // private members <br>
  
  public: <br>
  
  // declaring constructor<br>
  class_name({parameters})<br>
  {<br>
    // constructor body <br>
  }<br>
  
};<br>
#### Destructors:
Destructor is just the opposite function of the constructor. A destructor is called by the compiler when the object is destroyed and its main function is to deallocate the memory of the object. The object may be destroyed when the program ends, or local objects of the function get out of scope when the function ends or in any other case.
Destructor has the same as of the class with prefix tilde(~) operator and it cannot be overloaded as the constructor.
Destructors take no argument and have no return type and return value.<br>
The basic syntax of the Destructor is given below:<br>
class class_name{<br>
  private: <br>
  // private members <br>
  
  public: <br>
  
  // declaring destructor<br>
  ~class_name()<br>
  {<br>
    // destructor body <br>
  }<br>
  
};


