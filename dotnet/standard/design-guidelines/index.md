
# Framework Design Guidelines
This section provides guidelines for designing libraries that extend and interact with the .NET Framework. The goal is to help library designers ensure API consistency and ease of use by providing a unified programming model that is independent of the programming language used for development. We recommend that you follow these design guidelines when developing classes and components that extend the .NET Framework. Inconsistent library design adversely affects developer productivity and discourages adoption.  
  
 The guidelines are organized as simple recommendations prefixed with the terms `Do`, `Consider`, `Avoid`, and `Do not`. These guidelines are intended to help class library designers understand the trade-offs between different solutions. There might be situations where good library design requires that you violate these design guidelines. Such cases should be rare, and it is important that you have a clear and compelling reason for your decision.  
  
 These guidelines are excerpted from the book *Framework Design Guidelines: Conventions, Idioms, and Patterns for Reusable .NET Libraries, 2nd Edition*, by Krzysztof Cwalina and Brad Abrams.  
  
## In This Section  
 [Naming Guidelines](naming-guidelines.md)  
 Provides guidelines for naming assemblies, namespaces, types, and members in class libraries.  
  
 [Type Design Guidelines](type.md)  
 Provides guidelines for using static and abstract classes, interfaces, enumerations, structures, and other types.  
  
 [Member Design Guidelines](member.md)  
 Provides guidelines for designing and using properties, methods, constructors, fields, events, operators, and parameters.  
  
 [Designing for Extensibility](designing-for-extensibility.md)  
 Discusses extensibility mechanisms such as subclassing, using events, virtual members, and callbacks, and explains how to choose the mechanisms that best meet your framework's requirements.  
  
 [Design Guidelines for Exceptions](exceptions.md)  
 Describes design guidelines for designing, throwing, and catching exceptions.  
  
 [Usage Guidelines](usage-guidelines.md)  
 Describes guidelines for using common types such as arrays, attributes, and collections, supporting serialization, and overloading equality operators.  
  
 [Common Design Patterns](common-design-patterns.md)  
 Provides guidelines for choosing and implementing dependency properties and the dispose pattern.  
  
 *Portions © 2005, 2009 Microsoft Corporation. All rights reserved.*  
  
 *Reprinted by permission of Pearson Education, Inc. from [Framework Design Guidelines: Conventions, Idioms, and Patterns for Reusable .NET Libraries, 2nd Edition](http://www.informit.com/store/framework-design-guidelines-conventions-idioms-and-9780321545619) by Krzysztof Cwalina and Brad Abrams, published Oct 22, 2008 by Addison-Wesley Professional as part of the Microsoft Windows Development Series.*  
  
## See Also  
 [Overview](../../../docs/framework/get-started/overview.md)  
 [Roadmap for the .NET Framework](http://msdn.microsoft.com/library/0b46b7c6-9163-4f99-8e58-0d1ee7da8c67)  
 [Development Guide](../../../docs/framework/development-guide.md)