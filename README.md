* MVC - Modeel- View- controller
It is software architecture pattern. MVC separate the application into main components and it helps to organize code and promiting 
the principles of separation of concerns, making the application more maintanable and scalable

* Model - represent the application Data and buisness logic.
In .Net Core MVC application, Models are typically classes that define the structre of data and include methods for interacting with data.

* View - Use for presenting data to the user and handling user input.
In a web application, a view is often an HTML page that is rendered to the user. Views in .NET Core MVC can include Razor syntax to embed C# code within the HTML for dynamic content rendering.

* Controller - act as intermediary between the Model and the View. It recive user input from the view and determines which view to display. In .Net Core controllers are the classes that handlne 
incoming HTTP requests, process the input, andreturn an appropriate response. often by selecting a view to render.

* Service - .Net Core is  versatile and modular framework that provides a variety of services for building different types of applications
Here are some key services and features offered by .Net Core.

* Cross-Platform Development:
.NET Core is designed to be cross-platform, supporting development on Windows, macOS, and Linux. This allows developers to build applications that can run on a variety of operating systems.

*ASP.NET Core:
ASP.NET Core is a web framework that is part of .NET Core, used for building modern web applications, including MVC (Model-View-Controller) architecture, Razor Pages, and Web API for building RESTful services.

*Entity Framework Core:
Entity Framework Core is an Object-Relational Mapping (ORM) framework that simplifies database access in .NET Core applications. It provides a set of APIs for interacting with databases using C# code.

*Dependency Injection:
.NET Core includes a built-in dependency injection (DI) system. Dependency injection helps manage component dependencies, making applications more modular, testable, and maintainable.

*Cross-Platform Command-Line Interface (CLI):
.NET Core comes with a cross-platform command-line interface (dotnet CLI) that allows developers to perform various development tasks, such as building, testing, and publishing applications, from the command line.

*NuGet Package Management:
NuGet is a package manager for .NET that simplifies the process of adding, updating, and managing third-party libraries and components in .NET Core projects.

*.NET Standard:
.NET Standard is a specification that defines a set of common APIs across different .NET implementations. This allows code written against the .NET Standard to be shared and reused across different .NET platforms.

*Performance Optimization:
.NET Core is designed for high-performance applications. It includes features like Just-In-Time (JIT) compilation, asynchronous programming support, and other optimizations to improve the speed and efficiency of applications.

*Support for Microservices:
.NET Core is well-suited for building microservices architectures. Its lightweight nature, support for containerization (e.g., Docker), and built-in features for building scalable and distributed applications make it a good choice for microservices development.

*Cloud Integration:
.NET Core integrates well with various cloud platforms, including Microsoft Azure and AWS. It provides tools and libraries for developing cloud-native applications and supports container orchestration with platforms like Kubernetes.

*Machine Learning and AI:
.NET Core supports machine learning and artificial intelligence scenarios through libraries like ML.NET, allowing developers to integrate machine learning models into their applications.

These services collectively make .NET Core a powerful and flexible framework suitable for a wide range of application development scenarios, from web development to cloud-native and microservices architectures.


What is Dependency Injection _
Dependency Injection is a way to provide the necessary dependencies (i.e., objects or services) to a class rather than having the class create or manage them on its own.
The main goals of Dependency Injection are to improve code maintainability, flexibility, and testability. 
Instead of hard-coding dependencies within a class or method, dependencies are injected from the outside, 
typically through constructor injection, method parameters, or property injection.

Here are the key concepts related to Dependency Injection:

Dependency:
A dependency is an object or service that another class relies on to perform its functionality.

Client Class:
The class that requires a dependency is often referred to as the "client class."

Injector:
The injector is responsible for providing the required dependencies to the client class.

Injection Types:
There are three main types of dependency injection:
Constructor Injection: Dependencies are injected through the class constructor.
Method Injection: Dependencies are passed as method parameters.
Property Injection: Dependencies are set through public properties of the client class.
