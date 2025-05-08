# TypeScript: Interfaces vs Types

Interfaces can be extended and merged, allowing for more flexible and reusable structures. They are mainly used for object shape definitions.

Types are more versatile and allow the use of union, intersection, and mapped types. You cannot merge a type definition like an interface.

When to use:

Use interface when you need to extend or merge multiple structures.

Use type when you need more flexibility, like working with unions or intersections.

# TypeScript: The Use of keyof Keyword

The keyof keyword is used to get the keys of an object as a union of string literals. It makes sure you are only working with valid keys of an object, ensuring type safety.

Example usage:

keyof helps in restricting the values to only the keys present in the object type, preventing mistakes like accessing non-existing properties.