1. What is one benefit of using generics in Java classes?

It gives us flexibility when using classes, and it helps to keep our code dry.

2. Name an example of a generic class that we have used in Java?

Arraylists

3. What is the syntax for declaring a generic class?

We can define a generic class using angle brackets, and within the angle brackets
we use E or T as placeholders.
class Account<T> {
  private T id;
}

4. At what point does the generic type get specified?

We specify the generic type when we instantiate the class.

5. Can generic types be of primitive type?

No, they can only be class type.

6. Can a generic class take more than one type parameters?

Yes, we have to use different placeholders separated by commas.
