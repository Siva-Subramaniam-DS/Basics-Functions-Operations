## ✅ **C Language: Basics, Functions, Operations**

### 1. **Swapping Two Numbers**

```c
void swap(int *a, int *b) {
    int temp = *a;
    *a = *b;
    *b = temp;
}
```

### 2. **Factorial Using Recursion**

```c
int factorial(int n) {
    if (n <= 1) return 1;
    return n * factorial(n - 1);
}
```

### 3. **Check Prime Number**

```c
int isPrime(int n) {
    for (int i = 2; i <= n / 2; i++)
        if (n % i == 0) return 0;
    return n > 1;
}
```

### 4. **Array Sum**

```c
int sumArray(int arr[], int n) {
    int sum = 0;
    for (int i = 0; i < n; i++) sum += arr[i];
    return sum;
}
```

### 5. **String Reverse**

```c
void reverse(char str[]) {
    int len = strlen(str);
    for (int i = 0; i < len/2; i++) {
        char temp = str[i];
        str[i] = str[len-1-i];
        str[len-1-i] = temp;
    }
}
```

### 6. **Linear Search**

```c
int linearSearch(int arr[], int n, int key) {
    for (int i = 0; i < n; i++)
        if (arr[i] == key) return i;
    return -1;
}
```

### 7. **Pointer Example**

```c
void showPointer() {
    int x = 10;
    int *p = &x;
    printf("%d", *p);
}
```

### 8. **Structure Example**

```c
struct Student {
    char name[50];
    int age;
};
```

### 9. **Fibonacci Series**

```c
void fibonacci(int n) {
    int a = 0, b = 1, c;
    for (int i = 0; i < n; i++) {
        printf("%d ", a);
        c = a + b;
        a = b;
        b = c;
    }
}
```

### 10. **File Handling**

```c
void writeFile() {
    FILE *f = fopen("test.txt", "w");
    fprintf(f, "Hello C File!");
    fclose(f);
}
```

---

## ✅ **Python: Functions, List Ops, OOP**

### 1. **Swapping Variables**

```python
a, b = 5, 10
a, b = b, a
```

### 2. **Factorial Using Recursion**

```python
def factorial(n):
    return 1 if n <= 1 else n * factorial(n - 1)
```

### 3. **Prime Check**

```python
def is_prime(n):
    return all(n % i != 0 for i in range(2, int(n**0.5)+1)) and n > 1
```

### 4. **Sum of List**

```python
def sum_list(lst):
    return sum(lst)
```

### 5. **List Comprehension (Even Numbers)**

```python
evens = [x for x in range(10) if x % 2 == 0]
```

### 6. **String Reverse**

```python
def reverse_string(s):
    return s[::-1]
```

### 7. **Linear Search**

```python
def linear_search(arr, key):
    for i, v in enumerate(arr):
        if v == key:
            return i
    return -1
```

### 8. **OOP: Class Example**

```python
class Person:
    def __init__(self, name): self.name = name
    def greet(self): return f"Hello {self.name}"
```

### 9. **File Handling**

```python
with open("file.txt", "w") as f:
    f.write("Hello Python File!")
```

### 10. **Lambda and Map**

```python
squares = list(map(lambda x: x**2, range(5)))
```

---

## ✅ **Java: Functions, OOP, Arrays**

### 1. **Swap Two Numbers**

```java
void swap(int a, int b) {
    int temp = a;
    a = b;
    b = temp;
}
```

### 2. **Factorial with Recursion**

```java
int factorial(int n) {
    if (n <= 1) return 1;
    return n * factorial(n - 1);
}
```

### 3. **Check Prime**

```java
boolean isPrime(int n) {
    for (int i = 2; i <= n / 2; i++)
        if (n % i == 0) return false;
    return n > 1;
}
```

### 4. **Sum of Array Elements**

```java
int sumArray(int[] arr) {
    int sum = 0;
    for (int i : arr) sum += i;
    return sum;
}
```

### 5. **String Reverse**

```java
String reverse(String s) {
    return new StringBuilder(s).reverse().toString();
}
```

### 6. **Linear Search**

```java
int search(int[] arr, int key) {
    for (int i = 0; i < arr.length; i++)
        if (arr[i] == key) return i;
    return -1;
}
```

### 7. **Class & Object**

```java
class Car {
    String model;
    Car(String model) { this.model = model; }
    void show() { System.out.println(model); }
}
```

### 8. **Inheritance**

```java
class Animal {
    void sound() { System.out.println("Sound"); }
}
class Dog extends Animal {
    void sound() { System.out.println("Bark"); }
}
```

### 9. **File Handling**

```java
FileWriter fw = new FileWriter("test.txt");
fw.write("Hello Java File");
fw.close();
```

### 10. **Fibonacci Series**

```java
void fib(int n) {
    int a = 0, b = 1, c;
    for (int i = 0; i < n; i++) {
        System.out.print(a + " ");
        c = a + b;
        a = b;
        b = c;
    }
}
```
