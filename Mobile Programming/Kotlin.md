- Is a cross platform, statically typed, general purpose programming language
- is designed to interoperate fully with java

##### Data Types
- **String**
- **Int**
- **Double**
- **Float**
- **Boolean**
##### Variables
**Immutable Variables**
- read-only variables, cannot change
```kotlin
val myName = "Jed"
myName = "Tim"
print(myName) //gives error
```
**Mutable Variables**
- variables that can change
```kotlin
var myAge = 19
myAge = 20
print(myAge) //works properly
```

**Naming Convention** - lowerCamelCase

**Type Inference**
- Kotlin allows type inference
```kotlin
var name:String = "Jed"
```

**Type Conversion**
- AKA Type casting, changing the entity of one data type into another
```kotlin
var number = 12
var numToStr = number.toInt()
```

**String Interpolation**
- allows you to embed variables within string literals
```kotlin
val name = "Jed"
val message = "Hello, $name" //you can also do ${name}
print(message) //prints "Hello, Jed"
```

**String Concatenation**
```kotlin
val name = "Jed"
val message = "Hello, " + $name
print(message) //prints "Hello, Jed"
```

##### Operators
- **Arithmetic** - perform common mathematical operations
- **Relational** - AKA comparison operators, used to compare two values and return boolean values
- **Assignment** - assign values to variables
- **Unary** - operators that work with only one operand (increment/decrement)
- **Logical** - determine logic between two variables 

##### Kotlin Input
```kotlin
val name = readLine()
val age = readLine()!! //!! won't allow null variables
```

Can also use java.util.Scanner class from Java standard library.
```kotlin
import java.util.Scanner

val name = Scanner(System.`in`)
```

#### Comments
```kotlin
// This is a comment
```

##### If...Else Statements
```kotlin
if (condition){
	statement
} else {
	statement
}
```
**Another way (1 line)**
```kotlin
val a = 10
val b = 5
val variable = if (a>b) a else b // variable = 10
```

##### When statement
- works like switch case
```kotlin
val word = readLine().toString()
when (word){
	"Hello" -> print("It said hello")
	"Goodbye" -> print("It said goodbye")
	"Greetings" -> print("It said greetings")
	else -> print("unknown") //can also work without an else statement
}
```

**Can also use ranges**
```kotlin
var number = readLine().toInt()
when(number) {
	in 1..5 -> print("1-5")
	in 6..10 -> print("6-10")
	!in 1..10 -> print("Unknown")
}
```

**As an expression**
```kotlin 
var number = readLine().toInt()
var day = when(number) {
	1 -> "Sunday"
	2 -> "Monday"
	3 -> "Tuesday"
	4 -> "Wednesday"
	//and so on
}
```

#### Loops
##### While Loop
```kotlin
while(condition){
	//do something
}
```

**with Arrays**
```kotlin
var colors = arrayOf ("red","yellow","blue")
var index = 0

while (index < colors.size){
	println(colors[index])
	index ++
}
```
##### Do While Loop
```kotlin
do {
	//do something
} while (condition)
```

##### For Loop
```kotlin
for (i in 1..6) {
	//do something
}
```
