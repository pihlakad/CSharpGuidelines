# CSharp Guidelines

## 1. Naming Guidelines
### Don't repeat the name of a class or enumeration in its members

```csharp
class Food {
	// Wrong!
	static GetFood() {}
	DeleteFood() {}
	
	// Right
	static Get() {...}
	Delete() {...}
}
```

## 2. Documentation Guidelines

### Write comments and documentation in English

### Avoid inline comments

If you feel the need to explain a block of code using a comment, consider replacing that block with a method with a clear name.