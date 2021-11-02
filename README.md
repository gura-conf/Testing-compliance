Gura Compliance

This repository contains several tests useful for any developer working on a Gura format parser/emitter.


## Usage

The tests are a series of `.ura` files categorized in different folders.

- The tests found in the `correct` folder should not throw any errors or exceptions in a Gura format parser or writer implementation.
- Then, there are different tests in folders with the name of the exception that a parser should throw. You can check theYou can check the complete [exceptions list in official docs][exceptions].

Automation of these tests is not possible because exception handling is dependent on each tool used. To make it agnostic to the programming language used by the interested developer, it was decided to provide a series of files that can be easily integrated into any project.

If you are interested in practical usage examples, you can check any parser project maintained by the organization (Python, JS/TS, Rust, V). All of them includes all the test listed in this repository.


## Licence

This repository is distributed under the terms of the MIT license.

[exceptions]: https://gura.netlify.app/docs/2.0.0/Developers/parsing#standard-errors