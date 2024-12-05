# General


## When statement


### When as a statement

Is simpe, see this code and you will understand

```kotlin
package tests

fun main() {
    val feedback = 4;
    when (feedback) {    
        1 -> println("Sorry. How can we improve?")
        2 -> println("ok. How can we improve?")
        3 -> println("Thanks!")
        else -> println("I do not know this rate")
    }
}
```

### When as an expression

Easy to understand because the syntax is similar as "when" as expression. But an attribuition is done in this case, see:

```kotlin
package tests

fun main() {
    val feedback = 1;
    var result: Any = when (feedback) {    
        1 -> "Sorry. How can we improve?"
        2 -> "ok. How can we improve?"
        3 -> "Thanks!"
        else -> "I do not know this rate"
    }

    print(result)
}
```


## Verifying types - is

```kotlin
package tests

fun main() {
    if ("hi" is String) {
        print ("hi is a string")
    } else {
        print ("hi is not a string")
    }
}
```

## Any - any type

[Please see here](https://pl.kotl.in/gM0GHOkMQ"). Easy to understand. any = any type


## for loop

Very simple. Please see [this code](https://pl.kotl.in/qylf7Yhi6).

In this section you all saw **string interpolation**, that is mixing a string with a variable.

You also saw another example of use of **"vararg**" in the internal function **listOf()**.

And you saw a example of "**any**", as you have more tham 1 type inside the list generated with **listof()**.