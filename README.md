# Radosław Rowicki

A computer scientist by passion and profession. Graduate at the University of Warsaw, [master's degree](https://github.com/radrow/masters-thesis), currently a PhD student at [DTU Compute](https://www.compute.dtu.dk/).

[![GitHub radrow](https://img.shields.io/github/followers/radrow?label=follow&style=social&cacheSeconds=86400)](https://github.com/radrow)
[![Linkedin radrow](https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/radrow-85ab63b4&cacheSeconds=864000)](https://www.linkedin.com/in/radrow)
[![Stack Exchange reputation](https://img.shields.io/stackexchange/stackoverflow/r/4400060)](https://stackoverflow.com/users/4400060/radrow?tab=profile)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=radrow&layout=compact&hide=TeX,HTML&theme=dark)](https://github.com/anuraghazra/github-readme-stats)


<details>
<summary><b>Skills</b></summary>
  
### Areas

- Functional programming
- Compiler construction
- Type theory
- Blockchain
- Formal verification

### Technologies & lanugages

- **Advanced:** Haskell, Erlang, Coq
- **Semi-advanced:** C#, Rust
- **Intermediate:** Python, Prolog

### Natural languages

- **Mothertongue:** Polish
- **Fluent:** English
- **Communicative:** German
  
<hr>
</details>

<details>
<summary><b>Professional experience</b></summary>

### 2023–present — PhD Student at **DTU Compute**

- Researching methods for verification of distributed systems
- Teaching assistance in computer science master's courses
  
### 2019–present — Erlang Developer at **æternity blockchain**

- Developing a compiler for a smart contract language
- Developing tooling for smart contract development
- Developing a virtual machine for smart contracts
- Conducting technical interviews and onboarding new members
  
### 2021–2022 — Software Engineer at **Microsoft Corporation**

- Developed the server behind Business Central 365
- Maintained site reliability
  
### 2018 — Haskell & Elm Developer Intern at **Vacation Labs**
  
- Introduced a new booking infra for the company's services
- Introduced Elm to the codebase

<hr>
</details>

<details>
<summary><b>Education</b></summary>

### 2023–2026 (est.) Technical University of Denmark

- Research project: "Hyben - Hybrid Verification of Heterogeneous Message-Passing Applications"
- Formalised methods of distributed deadlock detection via black-box monitors
- Mechanised theoretical results in [Rocq](https://github.com/radrow/dlstalk-coq)
- Implemented tools for deadlock detection in gen_server-based systems: [DDMon](https://github.com/radrow/ddmon) and [DDTrace](https://github.com/radrow/ddtrace)

### 2019–2022 University of Warsaw

Master's degree in computer science.
  
- Thesis: [Liquid types for verification of smart contracts](https://students.mimuw.edu.pl/~radrow/master.pdf)
- Grade: Very Good (5 in a 2–5 scale)
  
### 2020–2021 Ludwig Maximilian University of Munich

Student exchange programme

### 2016–2019 University of Warsaw

Bachelor's degree in computer science
  
- Thesis: [Variational autoencoder for collaborative filtering - implementation and performance optimization](https://students.mimuw.edu.pl/~radrow/bachelor.pdf)
- Grade: Good (4 in a 2–5 scale)

<hr>
</details>


<details>
<summary><b>Selected projects</b></summary>

### PhD related

- [`ddmon`](https://github.com/radrow/ddmon) — A prototype tool for distributed deadlock detection in Erlang/Elixir systems based on the `gen_server` behaviour. Implemented as *black-box proxy monitors*. Works as a drop-in replacement for the `gen_server` module.
- [`ddtrace`](https://github.com/radrow/ddtrace) — Another distributed deadlock detecting tool for generic servers in Erlang, but this time based on *observing monitors* that do not require any intervention in the code of the monitored process. Instead, uses built-in `trace` facility to make deadlock verdicts based solely on incoming and outgoing communication.
- [`dlstalk`](https://github.com/radrow/dlstalk-coq) — Fully mechanised formalisation of a deadlock detecting algorithm via proxy monitors. Specifies syntax and semantics of monitored and unmonitored services and networks and proves transparency and preciseness of deadlock verdicts. [`ddmon`](https://github.com/radrow/ddmon) is the implementation of this model.

### Work related

- [`aesophia`](https://github.com/aeternity/aesophia) — I developed the Sophia smart contract language for the [æternity blockchain](aeternity.com).
- [`aerepl`](https://github.com//aeternity/aerepl) — I designed and implemented a Read-Eval-Print Loop and debugger for the Sophia language.
- [`aerepl-web`](https://github.com//aeternity/aerepl-web) — Web interface for æREPL implemented by me.
- [`aeserialization-rust`](https://github.com/aeternity/aeserialization-rust/) — I rewrote core components of the æternity blockchain in Rust.
- [`tree-sitter-aesophia`](https://github.com/aeternity/tree-sitter-aesophia/) — I implemented a [Tree-sitter](https://tree-sitter.github.io/tree-sit) grammar for æternity's smart contract language.
- [`erlscripten`](https://github.com/erlscripten/erlscripten) — I took key part in the erlscripten project, which aims to port Erlang applications to the frontend of web applications by transpiling it into [PureScript](https://www.purescript.org/).
- [`erlscripten/purescript`](https://github.com/erlscripten/purescript) — For the erlscripten project I did a lot of tinkering in the source generator and optimizer of PureScript's compiler. My work resulted in a few contributions to the original project:
  - [#4006](https://github.com/purescript/purescript/pull/4006) — I identified and fixed a performance issue in one of PureScript's AST transformations. 
  - [#3968](https://github.com/purescript/purescript/pull/3968) — I proposed changes to how tail-call optimizations are triggered (unmerged).

### University related

- [`radlang`](https://github.com/radrow/radlang) — An interpreter of a Haskell-like language. Supports type classes, full type inference, higher kinded types, `for` notation for monads and lazy evaluation.
- [`latte`](https://github.com/radrow/latte) — An x86 compiler for a Java-like OOP language. Implements class inheritance, polymorphism via virtual methods and some simple optimization techniques.
- [`satisfaction`](https://github.com/radrow/satisfaction) — A SAT solver implementing CDCL and DPLL algorithms written in Rust as an assessment task for courses at LMU. 
- [`VAE-CF`](https://github.com/mkfilipiuk/VAE-CF) — Bachelor's thesis project. A variational autoencoder for collaborative filtering written in [Tensorflow](https://www.tensorflow.org/). Created in cooperation with NVIDIA Corporation to optimize it for their hardware and infrastructure.
- [`tftp-client-coq`](https://github.com/radrow/tftp-client-coq) — A TFTP client written in Coq/OCaml. Provides proofs for compliance with the RFC standard.
- [`Tiny-Semantics`](https://github.com/radrow/Tiny-Semantics) — A simple CPS-styled interpreter of an imperative language written in Haskell.
- [`instant-compiler`](https://github.com/radrow/instant-compiler) — A calculator-like language compiler that targets LLVM and JVM.
  
### Independent / personal
  
- [`i3hloc`](https://github.com/radrow/i3hloc2) — A customizable, parallelized scheduler for the [`i3status`](i3/i3status) status bar for i3 WM. Written in Haskell.
- [`fizzbuzz-coq`](https://github.com/radrow/fizzbuzz-coq) — A super defensive joke implementation of the [Fizz Buzz](https://en.wikipedia.org/wiki/Fizz_buzz) problem written as a sophisticated proposal to the [state-of-the-art implementation](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition). Written in Coq to prove correctness of every step of the algorithm. Obfuscation warning. 
- [`blockchain-toy`](https://github.com/radrow/blockchain-toy) — A simple centralized blockchain implementation written in Haskell.
- [`Iris`](https://github.com/jaedb/Iris) — I provided the Iris Mopidy frontend with Polish localization.

<hr/>
</details>
