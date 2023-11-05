# effective_dart_notes

---

Reference: https://dart.dev/effective-dart

**Three Identifies Used in Dart:**
1. UpperCamelCase
2. lowerCamelCase
3. lower_case_with_underscore

### 1. UpperCamelCase:


- [Classes](https://dart.dev/guides/language/language-tour#classes)
- [Enums](https://dart.dev/guides/language/language-tour#enumerated-types)
- [Typedefs](https://dart.dev/guides/language/language-tour#typedefs)
- [Metadata Annotations](https://dart.dev/guides/language/language-tour#generics)
- [Type Parameters](https://dart.dev/guides/language/language-tour#generics)
- [Extensions](https://dart.dev/guides/language/extension-methods)


### 2. lowerCamelCase:


- [Class Members](https://dart.dev/guides/language/language-tour#using-class-members)
- [Variables](https://dart.dev/guides/language/language-tour#variables)
- [Constant Variables](https://dart.dev/guides/language/language-tour#final-and-const)
- [Enum Values](https://dart.dev/guides/language/language-tour#final-and-const)
- [Parameters](https://dart.dev/guides/language/language-tour#final-and-const)
- [Named Parameters](https://dart.dev/guides/language/language-tour#final-and-const)

#### Do NOT use SCREAMING_CAPS


### 3. lowercase_with_underscores


- Files
- Directories
- Packages
- Source Files
- Import Prefixes

## Ordering
- Place “dart:” imports before other imports.
- Place “package:” imports before relative imports.
- Specify exports in a separate section after all imports.
- Sort sections alphabetically.


## Formatting
- Use Dart Formatters 
- CONSIDER changing your code to make it more formatter-friendly.
- AVOID lines longer than 80 characters(Either in variable names or classes or single line comments).
- DO use curly braces for all flow control statements.

# Ending Notes
- DON’T use prefix letters(like kCustomBlackColor).
- DON’T use a leading underscore for identifiers that aren’t private.
- PREFER using _, __, etc. for unused callback parameters.

- Last but not least, these are best practices and not hard rules and everyone should consider adopting the system.
