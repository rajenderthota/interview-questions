Sure! Here's a curated list of **Java 8 interview questions** tailored for an experienced developer (5+ years). These cover **core features, real-world use cases**, and **performance trade-offs**, often asked in senior or lead developer interviews.

---

### 🔹 **Core Java 8 Concepts**

#### ✅ Lambda Expressions
1. **What is a lambda expression in Java 8? How is it different from anonymous classes?**
2. **How does the compiler infer types in lambda expressions?**
3. **Can lambda expressions access local variables? Explain "effectively final".**

#### ✅ Functional Interfaces
4. **What is a functional interface? How is it identified?**
5. **What are some commonly used functional interfaces in Java 8?**
6. **Can a functional interface have default or static methods?**

#### ✅ Method & Constructor References
7. **What are method references? Explain different types with examples.**
8. **When would you use a constructor reference instead of a lambda?**

---

### 🔹 **Streams API**

#### ✅ Basic Stream Concepts
9. **What is a stream in Java 8? How is it different from a collection?**
10. **Explain the difference between `map`, `flatMap`, and `filter`.**
11. **What’s the difference between intermediate and terminal operations?**
12. **Is a stream reusable? If not, how can you reuse its source?**
13. **How does lazy evaluation work in Java Streams?**

#### ✅ Advanced Stream Use Cases
14. **What’s the difference between `reduce` and `collect` in streams?**
15. **How would you group data in a stream (e.g., using `Collectors.groupingBy`)?**
16. **How to calculate averages, sum, or statistics using streams?**
17. **What’s the performance impact of using streams vs traditional loops?**

#### ✅ Parallel Streams
18. **What are parallel streams? When should or shouldn’t you use them?**
19. **How do parallel streams internally work? What thread pool do they use?**
20. **How would you make a custom collector to work with parallel streams?**

---

### 🔹 **Date and Time API (java.time)**

21. **What are the main classes in Java 8's Date and Time API?**
22. **How is `LocalDate` different from `ZonedDateTime` and `Instant`?**
23. **How would you calculate the difference between two dates?**
24. **How do you convert between `java.util.Date` and `java.time.LocalDate`?**

---

### 🔹 **Optional Class**

25. **What is `Optional` in Java 8? Why is it introduced?**
26. **What’s the difference between `orElse()`, `orElseGet()`, and `orElseThrow()`?**
27. **What are best practices for using Optional in method parameters and return types?**

---

### 🔹 **Default and Static Methods in Interfaces**

28. **Why were default methods introduced in Java 8?**
29. **Can you override a default method in a class?**
30. **What happens in case of multiple inheritance conflict (e.g., two interfaces with the same default method)?**

---

### 🔹 **Practical/Scenario-Based**

31. **Write a stream pipeline to find the first non-repeated character in a string.**
32. **Use Java 8 features to group employees by department and calculate average salary.**
33. **Given a list of transactions, find the highest transaction per customer.**
34. **How would you use `Optional` to avoid `NullPointerException` in nested property access?**
35. **Implement a retry logic using lambdas or functional interfaces.**

---

### 🔹 **Bonus: Design/Architecture Qs involving Java 8**

36. **Where have you used Java 8 features in system design or microservices?**
37. **How would Java 8 help improve readability and testability of code?**
38. **How do you decide between using imperative style vs functional style in production code?**

---

Would you like me to format this as a **PDF or one-pager** for interview prep? Or want sample **answers** or **code examples** for key questions?
