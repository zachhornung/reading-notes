# Class 09 Reading Notes
* There is a balance between speed and comprehension when writing code, and good code lives in that balance. some strategies for doing this are to return early from functions, cache variables so functions can be read like sentences, and check web apis before implimenting your own functionality.
* in functional programming, immutability and pure functions are very helpful. they allow for side-effect free functions, along with some other benefits. functional programming avoids changing state and mutable data. pure functions are pure if they return the asme result if given the same arguments, (this means that they are deterministic), and that they do not cause any observable side effects. if the parameters are not hard coded in, a pure function will access parameters passed into the function. if a function reads external files, it is not a pure function because the file's contents can change. a function that relies on a random number generator cannot be pure. mutability is discouraged in functional programming. when data is immutable, its state cannot change after it is created. recursion is used in functional programming to keep variables immutable. if a function consistently yields the same result for the same input, it is referentially transparent. pure functions + immutable data = referentially transparent.
<-----[Back](../README.md)