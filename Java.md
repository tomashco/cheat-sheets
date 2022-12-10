[Return Back](https://github.com/tomashco/cheat-sheets)

# Java

### initiate variables
- initiate multiple variables:
```java
int sum, partialSum, totalSum;
```

###Loop through an array

- for
```java
for (int i = 0; i < myArray.length; i++) {
  System.out.println(myArray[i]);
}
```

- for-each
```java
for (String element : myArray) {
  System.out.println(element);
}
```

- while
```java
int i = 0;
while (i < myArray.length) {
  System.out.println(myArray[i]);
  
  i++;
}
```

- do-while
```java
if (myArray.length > 0) {
  int i = 0;
  do {
    System.out.println(myArray[i]);
    i++;
  } while (i < myArray.length);
}
```

- forEach Functional
```java
Arrays.asList(myArray).stream().forEach(System.out::println);
```

- map
```java
Arrays.asList(myArray).stream().map(element -> {
  System.out.println(element);
  return element;
});
```
