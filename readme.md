# Goal:
Develop a basic IoC container.

# Task:
Create a class library and corresponding unit tests for IoC container. IoC - inversion of control which is related to a concept called "Dependency injection". Dependency injection is a technique whereby one object (or static method) supplies the dependencies of another object.

# Minimal functionality:

1. resolve concrete classes (without registration)
2. register interfaces implementation
3. dependecnies can have one constructor with no, one and many parameters
4. all scenarios should be covered with unit tests (xUnit)

# Advanced tasks (desirable but not obligatory):

1. singleton registration
2. properties injection (with [Inject] attribute)
3. deferred Resolution with Lazy<T> (and corresponding Func<T>)
4. circular dependencies check on registration
5. dependencies registration from file (can be XML or JSON or any cusom format)
6. injection of simple types, such as integers, strings etc.

# Resources:
* SOLID lecture
* Reflection lecture
* https://stackoverflow.com/questions/1638919/how-to-explain-dependency-injection-to-a-5-year-old
* https://github.com/ninject/Ninject
* https://www.pluralsight.com/courses/dependency-injection-on-ramp

# Books:
* Dependency Injection with Unity (has much more material, you can skip parts about ASP.NET MVC) - https://download.microsoft.com/download/4/d/b/4dbc771d-9e24-4211-adc5-65812115e52d/dependencyinjectionwithunity.pdf
* Dependency Injection in .NET, Mark Seeman - https://www.manning.com/books/dependency-injection-in-dot-net