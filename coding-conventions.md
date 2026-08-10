# SpellShop C# & .NET Coding Conventions

This document outlines the coding standards and conventions for the SpellShop project to maintain readability, consistency, and quality across the codebase.

---

## Naming Conventions

### PascalCase
Use **PascalCase** for:
* Class names (`ProductController`, `SpellDbContext`)
* Method names (`Create`, `GetProductById`)
* Public properties (`ProductID`, `Title`, `Price`)
* Namespaces (`SpellShop.Controllers`)

### camelCase
Use **camelCase** for:
* Method parameters (`product`, `id`)
* Local variables (`allProducts`, `isFound`)

### Private Fields
* Use **camelCase** prefixed with an underscore (`_`) for private read-only fields:
  ```csharp
  private readonly SpellDbContext _context;