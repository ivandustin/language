_"Dedicated to my love, to make programming joyful again."_

# The Programming Language

## Design

* High-level
* Application programming
* Game programming
* Write bug-less code
* Mathematical
* Functional
* Declarative
* Concise
* General purpose
* Familiar
* Fluid and unambiguous readability
* Paper and pen friendly
* Mobile phone friendly
* ASCII
* Auto-scale
* Compiled
* As fast as C
* One line (no multi-lines)
* No if-else condition
* No loops
* Automatic static memory allocation
* No dynamic memory allocation
* Automatic type inference
* Standard data types
* Math data types
* All lowercase
* Fixed function and variable name length
* No special characters on function and variable names
* No globals
* Enable code sharing and re-use
* Static typing
* Function names are verbs
* Variable names are nouns
* Rock

## Data types

* int
* real
* char
* text

## Multiple data types

* vector
* matrix

## Hello world

```
msg = "Hello world"
main() = out(msg)
```

## Math

```
a = 100
b = 200
c = a + b
main() = out(c)
```

## Function

```
sum(a, b) = a + b
main() = out(sum(1, 2))
```

## Data type assignment

```
float
a = 1

float
b = 2

int(int, int)
sum(a, b) = a + b

main() = out(sum(a, b))
```

## Vector multiplication

```
a = [1 2 3 4 5]
b = 3
main() = out(a * b)
```

## Matrix multiplication

```
a = [1 2 3 4 5]
    [6 7 8 9 10]
    [11 12 13 14 15]
b = [1 2 3 4 5]
main() = out(a * b)
```

## Condition

```
f(a) =  { a+1 a<10
        { 100 a>=10
        { 0
main() = out(f(3))
```

## Function composition

```
a(n) = n + 2
b(n) = n + 4
c = a o b
main() = out(c(3))
```

```
a(n) = n + 2
b(n) = n + 4
main() = a(3) o b o out
```

## Sequential functions

```
main() = walk() then run() then jump()
```

## Passing a function

```
x(n, f) = f(n)
y(a)    = a + 1
main()  = out(x(3, y))
```
