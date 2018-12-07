## ooping

* [testing objects](https://github.com/colevanderswands/testing-objects)
* [designing objects](https://github.com/colevanderswands/designing-objects)
* [data modeling](https://github.com/colevanderswands/data-modeling)
* [prototypical inheritance](https://github.com/colevanderswands/prototypical-inheritance)
* [inheritance design patterns](https://github.com/colevanderswands/inheritance-design-patterns)

apps = data + user interaction

objects enable this in a nice bundle

```
"
  you will often be told at the beginning of your learning to think of oop as things in real life: a car with doors & fuel levels, a person with a name and an age.  
  This is not quite accurate and engraining this understanding will make it difficult for you to make the transition from solving simple challenges to designing your own oop programs.
  Oop is:
    structured data with supported user interactions
  just what does this mean, and how can i use this to reframe the traditional 'object is a person'? 
    - this object represents a person, they can greet you
    + i will represent this person with a property called 'name' that stores their real name as a string.  i will enable users to access that property using a method called 'greet' which returns the stored name with a greeting concatinated
"

"
  with our new, correct, understanding of oop, let's think about inheritance.  The common analogy of inheritance using things like 'autos -> sedans, autos -> trucks' or 'animals -> mamals -> lions, animals -> mamals -> skunks, animals -> reptiles' is a false cognate.  
  a more correct analogy that will serve you better when designing oop programs and understanding data structures is this:
    i have two structured data sets, representing different things in the world
    but their structures are similar
    so i want to allow the same interactions with both data collections
    -> they will inherit methods from a shared prototype
"

variables/data structures are modified in the scope/context where they are created
  oop lives data in the context of an object
  fp lives data in the global context

```
