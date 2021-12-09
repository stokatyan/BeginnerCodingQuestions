# Intro
These are Generic coding problems for absolute beginners. 
The problems can be attempted in any language (Swift is used in the examples on this page).

Look closely at the example for each problem to see the format for each solution.

Feel free to use the web to find solutions, but avoid copy-pasting entire questions into Google.

Good luck!

# Problems

### Strings

1. Write a function, call it `helloWorld`, that returns the string `"hello world"`.
    ```swift
    let isCorrectAnswer = helloWorld() == "hello world"
    ```
-----
2. Write a function, call it `hello`, that says hello to the given person.
    ```swift
    let isCorrectAnswer = hello("Steve Jobs") == "Hello Steve Jobs."
    let isCorrectAnswer = hello("Spongebob") == "Hello Spongebob."
    ```
-----
3. Write a function, call it `madLibs`, that adds the given words to a fixed sentence.
    ```swift
    let isCorrectAnswer = madLibs("Steve Jobs", "John Lennon") == "Steve Jobs looks like John Lennon"
    let isCorrectAnswer = madLibs("Spongebob", "a sponge") == "Spongebob looks like a sponge"
    ```
-----
4. Write a function, call it `spellCheck`, that captilizes the first word of a given string.
    ```swift
    let isCorrectAnswer = spellCheck("hello there") == "Hello there"
    let isCorrectAnswer = spellCheck("see you later") == "See you later"
    ```
-----
5. Write a function, call it `punctuationCheck`, that adds a period to the end of a given string.
    ```swift
    let isCorrectAnswer = punctuationCheck("Hello there") == "Hello there."
    let isCorrectAnswer = punctuationCheck("in the jungle") == "in the jungle."
    ```
-----
6. Write a function, call it `capitalizeWords`, that capitalizes the first letter for each word in a list of words.
    ```swift
    let isCorrectAnswer = capitalizeWords(["steve, john, Goku"]) == ["Steve", "John", "Goku"]
    ```
-----
7. Write a function, call it `bottlesOnTheWall`, that uses the correct grammar for the given number of bottles on the wall.
    ```swift
    let isCorrectAnswer = bottlesOnTheWall(1) == "1 bottle on the wall"
    let isCorrectAnswer = bottlesOnTheWall(2) == "2 bottles on the wall"
    ```
-----
8. Write a function, call it `numOfOccurrences`, that find the number of times a given word occurs in a given string.
    ```swift
    let isCorrectAnswer = numOfOccurrences("hi hi hi", "hi") == 3
    let isCorrectAnswer = numOfOccurrences("hi hi hi", " hi ") == 1
    let isCorrectAnswer = numOfOccurrences("I like apples and I like video games", "like") == 2
    ```
-----
9. Write a function, call it `reverseWord` that rewrites a given string in reverse.
    ```swift
    let isCorrectAnswer = reverseWord("abc") == "cba"
    let isCorrectAnswer = reverseWord("hello") == "olleh"
    ```
-----
10. Write a function, call it `mixWords` that mixes any two given strings.
    ```swift
    let isCorrectAnswer = numOfOccurrences("abc", "123") == "a1b2c3"
    let isCorrectAnswer = numOfOccurrences("hello", "citizens") == "hceiltliozens"
    ```
-----

### Math

1. Write a function, call it `sum`, that can add any two numbers.
    ```swift
    let isCorrectAnswer = sum(1, 2) == 3
    ```
-----
2. Write a function, call it `isLessThan`, that returns `true` if a given number is less than another given number.
    ```swift
    let isCorrectAnswer = isLessThan(1, 2) == true
    let isCorrectAnswer = isLessThan(2, 1) == false
    ```
-----
3. Write a function, call it `isEven`, that returns `true` if a given number is even.
    ```swift
    let isCorrectAnswer = isEven(1) == false
    let isCorrectAnswer = isEven(2) == true
    ```
-----
4. Write a function, call it `max`, that returns the maximum value in a given list of numbers.
    ```swift
    let isCorrectAnswer = max([1, 2, 3, 4]) == 4
    let isCorrectAnswer = max([10, 5, -20, 818]) == 818
    ```
-----
5. Write a function, call it `evens`, that returns the evens values from a given list of numbers.
    ```swift
    let isCorrectAnswer = evens([1, 2, 3, 4]) == [2, 4]
    let isCorrectAnswer = evens(10, 5, -20, 818) == [10, -20. 818]
    ```
-----
6. Write a function, call it `sumAll`, that returns the sum of a list of numbers.
    ```swift
    let isCorrectAnswer = sumAll([1, 2, 3]) == 6
    let isCorrectAnswer = sumAll(10, 4) == 14
    ```
-----
7. Write a function, call it `squishAndHalf`, that returns the sum of a list of numbers divided by 2.
    ```swift
    let isCorrectAnswer = squishAndHalf([1, 2, 3]) == 3
    let isCorrectAnswer = squishAndHalf(10, 4) == 7
    ```
-----
8. Write a function, call it `mean`, that returns the average of a list of numbers.  
The average of a list of numbers is the sum of all the numbers, divided by the length of the list.
    ```swift
    let isCorrectAnswer = mean([2, 4]) == 3
    let isCorrectAnswer = mean(5, 10, 6) == 7
    ```
-----
9. Write a function, call it `areaOfCircle`, that returns the area of a circe for a given radius.  
Check google for the equation that gives the area of a circle, use radius = 3.14.
    ```swift
    let isCorrectAnswer = areaOfCircle(2) == 12.56
    let isCorrectAnswer = areaOfCircle(10) == 314
    ```
-----
10. Write a function, call it `volume(radius, height)`, that returns the volume of a cylinder with a given radius and height.  
Check google for the equation that gives the volume of a cylinder, use radius = 3.14.
    ```swift
    let isCorrectAnswer = volume(2, 10) == 125.6
    let isCorrectAnswer = volume(10, 0.5) == 157
    ```
-----
