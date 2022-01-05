### OOP concepts

#### Encapsulation
##### Setters and Getters
Knowing a little of Java is sufficient to know the convention of making methods to set and get attribute's values. But why's that? It seems to me that the result is pratically the same between using setters/getters and directly attributing the values.
After searching I found that there are really important reasons to use this pattern:
- You may want to an attribute be possible to be modified but not get got, and vice versa.
- There can be a validation before setting a value, like just setting a value between one number and another
And more, that I dont understand that well... yet

But actually using getters and setters are more controversial than it's presented for beginner programmers, that learn that they always need to be used. 
Getters and setters are contrary to OOP.
You dont need to ALWAYS use them, there are situations that it just doesn't make sense.
And there are situation that actually it's a bad practice.

So I discovered that in each basic concept in OOP and maybe in programming in general there are a lot of points to consider, and in my actual stage of career it's not so useful get so deep, even me being so curious to do so.

https://stackoverflow.com/questions/1568091/why-use-getters-and-setters-accessors

##### Cohesion and acoplation
Cohesion is an OOP principle that means attributing a single functionality to a class, with a well-focused purpose. So high cohesion is preferable for the maintance, readability of code.
Coupling is making classes independents to each other, or low connected explicitlly.
So basically it's important to create classes that have really specific  functionalities, as fewer as possible . And also knowing little or nothing from each other.

https://www.decodejava.com/coupling-cohesion-java.htm