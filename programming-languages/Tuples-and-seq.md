## Tuples are Examples of Sequence Data Types which Include Lists, range etc.

Tuples are ordered sequence of  **Immutable** and Heterogenous elements that are accessed via unpacking and Indexing.

```
te = ()

t = (2,"One",3)

```
# Singelton Tuples Examples

Tuples having single element is called Singelton Tuples

```
>>>t = (2,"one",3,4)
>>>print(t[1:2])
>>>("One",)
```

## Helps Return multiple elements

```
def quotient_and_remainder(m,n):
    q = m//n
    r = m%n

    return (q,r)
```
