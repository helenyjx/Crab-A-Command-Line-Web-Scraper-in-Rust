# Jiaxin-week5-mini-demo

## Goals
This demo is about building a simple Calculator Microservice based on Rust that can only do four types of operation: addition, substracion, multiplication and division. 

## Prepration
1. Set virtual environment: 
* `python3 -m venv env`
* `source env/bin/activate`

2. Install rust: 
* `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
* `source "$HOME/.cargo/env"`

3. Create new project:
*  `cargo new src` (src is the project name)

## Check format and test errors:
1. Format code: `make format`

2. Test code: `make lint`

## Update main.rs and lib.rs at src
1. main.rs
* The "main.rs" file is the entry point of a Rust program. It defines the starting point of the execution of the program and serves as the root of the program's structure. In other words, the "main.rs" file is where the program begins when it is run.
* Without a "main.rs" file, a Rust program would not have a defined starting point and would not be able to run. The "main.rs" file can import code from other parts of the program, including libraries defined in other files or external crates, and use that code to perform various tasks.
* In short, the "main.rs" file is required to build a Rust program because it defines the starting point of the program's execution and serves as the root of the program's structure.

2. lib.rs
* The purpose of building a library in Rust is to create reusable, modular code that can be used in multiple projects. The library can be a collection of functions, structures, and traits that perform specific tasks, and can be easily imported and used in other parts of your project. The main file of a library in Rust is usually named "lib.rs".
* By creating a library, you can encapsulate functionality and reduce code duplication across your projects, making it easier to maintain and update your code. This also makes it easier to share code with others, as libraries can be published to crates.io, the Rust package registry, allowing others to easily integrate them into their own projects.
* In short, the "lib.rs" file is used to build a library in Rust because it provides a way to create reusable, modular code that can be used across multiple projects.

### Run the Calculator Microservice
1. Type: `cargo run` in terminal directly (my result e.g. is shown below)
<img width="1114" alt="Screen Shot 2023-02-09 at 10 35 19 PM" src="https://user-images.githubusercontent.com/112274822/217998469-04409de3-14cd-40bf-a5c8-c2df5352b35f.png">

2. There are 4 routes:

A. type: "/add/a/b" that returns a result after adding a and b
<img width="705" alt="Screen Shot 2023-02-09 at 10 33 02 PM" src="https://user-images.githubusercontent.com/112274822/217998576-b1244f5c-b705-4405-a561-d94b2c28ca14.png">

B. type: "/subtract/a/b" that returns a result after subtracting a and b
<img width="739" alt="Screen Shot 2023-02-09 at 10 33 37 PM" src="https://user-images.githubusercontent.com/112274822/217998603-7d5b3db1-1d2c-4690-bb01-c7e5cb8b4a94.png">

C. type: "/multiply/a/b" that returns a result after multiplying a and b
<img width="741" alt="Screen Shot 2023-02-09 at 10 34 04 PM" src="https://user-images.githubusercontent.com/112274822/217998642-e158451c-0650-45bd-9882-493fd0155a28.png">

D. type: "/divide/a/b" that returns a result after dividing a and b
<img width="743" alt="Screen Shot 2023-02-09 at 10 34 42 PM" src="https://user-images.githubusercontent.com/112274822/217998659-05d01c61-af64-4cd7-946e-4ba21f593c6b.png">

**Reference**: https://github.com/noahgift/rust-mlops-template
