
----

## Architectural components

---

### NET Standard
Common set of API Specification that are present in all implementations of .NET.

for example there is function called `foo` that accepts 2 parameters.

API specification only tells there is function called `foo` that do some work. But it doesn't tell how it is doing its work.

Every implementation can implementation their own logic.

### .NET implementations
Each implementation of .NET includes the following components - 
- One or more runtimes --> 