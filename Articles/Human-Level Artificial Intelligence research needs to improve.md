# Human-Level Artificial Intelligence research needs to improve

## Current state of doing HLAI research

* Most companies which are currently doing research or implementation targeted at HLAI are using relatively unsafe dynamically typed programming languages: Python, R, etc.
* There is little collaboration between all the people working on HLAI research and implementation

## Dynamicaly typed vs. statically typed programming languages

A language being statically typed means that in addition to runtime type checks there are also type checks done at compile time.

Because of this pre-runtime check many bugs are caught before they have a chance to cause danger while the software is running.

For something as safety critical as human-level AI it is critical that we use the safest meanst to design it and insure it will be friendly.

Using dynamically typed programming languages for other safety critical software is unacceptable so why should we risk using them for programming the most important safety critical system: human-level AI?

<!-- TODO:
## Powerful abstractions and code duplication

and their relation to bugs
Higher Kinded Types, Dependent Types -->

## What we should do

* Start using more safe programming languages with static type systems such as Haskell, Agda, Idris, etc.
* Create an unified communication platform which would allow HLAI researchers to more efficiently communicate and be made aware of the dangers and benefits of using certain tools for doing HLAI research

Note: HLAI = Human-Level Artificial Intelligence = AGI = Artificial Geneneral Intelligence