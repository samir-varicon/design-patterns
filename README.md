
# Design Patterns

*Design patterns are reusable solutions to common problems in software design. They provide a common vocabulary for developers to use when communicating software design ideas and help to ensure that the solutions are consistent and efficient.*

*There are three types of design patterns: creational, structural, and behavioral. Creational patterns deal with object creation mechanisms, structural patterns deal with object composition, and behavioral patterns deal with communication between objects.*

*Examples of design patterns include the Singleton pattern, which ensures only one instance of a class is created, the Factory pattern, which creates objects without exposing instantiation logic to the client, and the Observer pattern, which establishes a one-to-many dependency between objects.*

*Design patterns can simplify code, make it easier to maintain and modify, and provide a common vocabulary for developers. However, they should be used judiciously and only when appropriate.*

## **What does the pattern consist of?**

Most patterns are described very formally so people can reproduce them in many contexts. Here are the sections that are usually present in a pattern description:

- **Intent** of the pattern briefly describes both the problem and the solution.
- **Motivation** further explains the problem and the solution the pattern makes possible.
- **Structure** of classes shows each part of the pattern and how they are related.
- **Code example** in one of the popular programming languages makes it easier to grasp the idea behind the pattern.

Some people criticize design patterns, arguing that they are only necessary in weak programming languages or technologies lacking necessary abstractions, and that patterns can lead to inefficient solutions if applied dogmatically. Additionally, some argue that patterns are often unjustifiably used by novices who try to apply them everywhere, even in situations where simpler code would suffice. However, patterns can still be useful when used appropriately and with context in mind.

# **Classification of patterns**

Design patterns differ by their complexity, level of detail and scale of applicability to the entire system being designed. I like the analogy to road construction: you can make an intersection safer by either installing some traffic lights or building an entire multi-level interchange with underground passages for pedestrians.

The most basic and low-level patterns are often called *idioms*. They usually apply only to a single programming language.

The most universal and high-level patterns are *architectural patterns*. Developers can implement these patterns in virtually any language. Unlike other patterns, they can be used to design the architecture of an entire application.

In addition, all patterns can be categorized by their *intent*, or purpose. This book covers three main groups of patterns:

- **Creational patterns** provide object creation mechanisms that increase flexibility and reuse of existing code.
- **Structural patterns** explain how to assemble objects and classes into larger structures, while keeping these structures flexible and efficient.
- **Behavioral patterns** take care of effective communication and the assignment of responsibilities between objects
