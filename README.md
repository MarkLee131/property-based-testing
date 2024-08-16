# Property-Based-Testing (PBT)

A collection of Property-Based Testing research for self-study and reference. 


## Useful Links

- https://hypothesis.works/articles/what-is-property-based-testing/

- https://fsharpforfunandprofit.com/posts/property-based-testing-2/

- https://techblog.criteo.com/introduction-to-property-based-testing-f5236229d237

- https://techblog.criteo.com/detecting-the-unexpected-in-web-ui-fuzzing-1f3822c8a3a5

- https://johanneslink.net/model-based-testing/

- https://www.youtube.com/watch?v=IYzDFHx6QPY

## PBT Tools

### QuickCheck

QuickCheck is a library for random testing of program properties. The programmer provides a specification of the program, in the form of properties which functions should satisfy, and QuickCheck then tests that the properties hold in a large number of randomly generated cases. Specifications are expressed in Haskell, using combinators defined in the QuickCheck library. QuickCheck provides combinators to define properties, observe the distribution of test cases, and define test data generators.

https://docs.rs/quickcheck/latest/quickcheck/index.html


### JUnit-QuickCheck

JUnit-QuickCheck is a library that provides a test runner for JUnit that generates test cases using the QuickCheck library. It is designed to work with JUnit 4.7 or later.


### Hypothesis

Hyperthesis is a library for property-based testing. It lets you write tests which are parametrized by a source of examples, and then generates simple and comprehensible examples that make your tests fail. This lets you find more bugs in your code with less work.

https://hypothesis.works/

### ScalaCheck

ScalaCheck is a library written in Scala that allows you to write property-based tests. It is based on Haskell's QuickCheck, but it is not a direct port. ScalaCheck is a powerful tool for automatically testing your Scala programs. It is built on the same principles as QuickCheck, but is designed to work well with Scala's type system, and can shrink failing test cases to minimal counterexamples.

https://www.scalacheck.org/

### PropEr

PropEr is a property-based testing tool for Erlang. It is inspired by QuickCheck, but is designed to work well with Erlang's concurrency model, and has support for stateful testing and distributed testing.

https://proper-testing.github.io/

### FastCheck

Property based testing framework for JavaScript (like QuickCheck) written in TypeScript

https://fast-check.dev/

### Hedgehog

Hedgehog is a modern property-based testing system, in the spirit of QuickCheck. It uses integrated shrinking, so shrinks obey the invariants of generated values by construction.


### TestCheck

TestCheck is a property-based testing library for Clojure, inspired by QuickCheck. It generates test cases automatically, and shrinks failing test cases to minimal counterexamples.

http://reiddraper.com/testcheck/


### PBT

PBT is a property-based in & for Ruby.

https://github.com/ohbarye/pbt

## Acknowledgements

Thanks to Prof.Ting SU and Dr.Jingling SUN for their guidance and support.

## Contributing

Please feel free to contribute to this repository by either opening issues or creating pull requests.



