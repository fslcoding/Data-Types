# Data Types

A data type ( commonly refered to as just '**_type_**' ), specifies the size of the variable, and what type of data it can store.

Here are some common types:

+ ```string```, stores many characters
+ ```char```, stores one character
+ ```int```, stores a whole number
+ ```double```, stores a decimal number
+ ```bool```, stores a true or false

Check out [Program.cs](https://github.com/fslcoding/Data_Types_CS/blob/main/Program.cs) to see examples of these types.

Some less common types include:

+ ```short```, half the size of ```int```
+ ```long```, double size of ```int```
+ ```float```, floating point number

### Converting between types

To convert between types, you use ```Convert``` class.
You use the **_Dot Syntax_** on the Convert class.

Here is a basic example:

```
string var1 = "5";

int var2 = Convert.ToInt32(var1);
```
var2 would be an integer of value 5.

_N.B. Converting is prone to errors, and you should always utilise a [**_Try Catch_**](https://github.com/fslcoding/Try_Catch_CS) when using them._

Another way to convert similar types is a [**_Cast_**](https://github.com/fslcoding/Casting_CS).



### **_Advanced_**

To create your own type, you can make a struct, class, or record



```
struct Car {
    public string CarName;
    public string Colour;
}
```

```
class Car {
    string CarName;
    string Colour;
}
```

```
public record Car(string CarName, string Colour);
```

## Useful Links

To learn more about these, check out their respective repos.

+ [Classes](https://github.com/fslcoding/Classes_CS)
+ [Structs](https://github.com/fslcoding/Structs_CS)
+ [Records](https://github.com/fslcoding/Records_CS)


# Tasks

[_Fork_](https://github.com/fslcoding/HowToFork) and clone this repo.

**_Level One_**
+ Read in the user's age
+ Convert it to an int
+ Print it back to them

**_Level Two_**
+ Do _level one_
+ Use a try catch, in a loop to keep asking the user for their age

**_Level Three_**
+ Use a TryParse to do _level one_

**_Level Four ( Super Hard! )_**
+ Create a user struct 
+ Read in user information
+ Populate struct with info
