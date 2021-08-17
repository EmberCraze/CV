# My Projects and Lessons Learned

## Infix to Postfix

### Link

https://github.com/EmberCraze/rust_prefix_to_postfix

### Project Description

A rust library that converts general math operations (infix) to reverse polish notation (postfix) by using the shunting-yard algorithm in https://en.wikipedia.org/wiki/Shunting-yard_algorithm.

### Lessons Learned
This project taught me the following:

- To use Cargo to compile and configure the library
- To create, test, and compile a rust library
- To use result as a return type to detect possible errors
- To establish different error types to clerify the type of error that has occured
- To use different datatypes and vector types such as String, &str, and Vec\<char> when required
- To iterate and enumerate vectors to process their data
- To use the std::mem:take funtion to optimize the move of data between variables
- To debug and refactor code for optimization
- The shunting-yard algorithm

## Calculator

### Link

https://github.com/EmberCraze/rust_calculator

### Project Description

A graphical calculator developed in rust. <br />The back-end of the calculator uses the [infix to postfix](https://github.com/EmberCraze/rust_prefix_to_postfix) to convert the input to postfix notation and then uses another algorithm to parse the posfix notation and calculate the parsed values two elements at a time. <br /> The back-end is compiled to a wasm binary that the front-end can access through [wasm-bindgen](https://github.com/rustwasm/wasm-bindgen). <br /> The front-end uses both JavaScript and HTML to show a functional graphical interface and bind graphical buttons to functions in the wasm binary.

### Lessons Leaned
TODO
