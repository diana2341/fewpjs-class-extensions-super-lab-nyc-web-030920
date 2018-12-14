# JavaScript Class Extension Lab: `super`

## Learning Goals

1.  Practice using `super` to extend child class functionality

## Introduction

In this lab we're going to practice the two most common usages of the `super`
keyword.

## Instructions

1.  Define a `Tree` class that will act as our parent.

    - A `Tree` instance should take in one parameter when created, `species`,
      and assign this to a private property, `_species`
    - A `Tree` should have a static method `baseDefinition` that states a short
      definition of all trees.

    > A tree is a perennial plant with an elongated stem, or trunk, supporting
    > branches and leaves.

2.  Define a `Deciduous` class that extends `Tree`

    - A `Deciduous` instance takes two parameters, `species` and `name`. Use
      `super` in the constructor to use the parent class constructor to assign
      `_species`, then assign `name` to a private property in the `Deciduous`
      constructor
    - Create a static method `definition` that uses `super` to access
      `baseDefinition` from `Tree` and add the following to the provide a specific
      definition for `Deciduous`:

    > Deciduous trees shed their leaves annually.

3.  Define a `Evergreen` class that extends `Tree`

    - A `Deciduous` instance takes two parameters, `species` and `name`. Use
      `super` in the constructor to use the parent class constructor to assign
      `_species`, then assign `name` to a private property in the `Evergreen`
      constructor
    - Create a static method `definition` that uses `super` to access
      `baseDefinition` from `Tree` and add the following to the provide a specific
      definition for `Evergreen`:

    > Evergreens keep their leaves all year round.

## Resources

- [Different Types of Quadrilaterals](https://www.math-only-math.com/different-types-of-quadrilaterals.html)
- [Trapezium](http://mathworld.wolfram.com/Trapezium.html)
- [“Super” and “Extends” In JavaScript ES6 - Understanding The Tough Parts](https://medium.com/beginners-guide-to-mobile-web-development/super-and-extends-in-javascript-es6-understanding-the-tough-parts-6120372d3420)
