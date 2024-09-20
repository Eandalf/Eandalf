# Programming Game (2020-21 FYP YIKE2)

[Back to Home](../../../README.md).

Associated with The Hong Kong University of Science and Technology.

Sep. 2020 ~ Apr. 2021

This project aimed to build a programming game to help teenagers and advanced learners learn Python more interestingly and competitively. We built the game by using Unity and .Net Core 5. For implementing Python language features, we did not take the text recognition approach, which would be specific to each challenge and could not scale well. Instead, we implemented a mini Python interpreter upon C# running on .Net Core 5. It recognized the tokens using Pegasus with the lexical analysis approach. After recognition, the interpreter built the abstract syntax tree (AST) using the information obtained from the tokens, with scoping, data types, and built-in functions taken into consideration and transformed into Node classes in C# to append to the AST. After the interpreter finished creating the AST for the whole code file, the interpreter used its evaluator to go through the tree and execute the statements. Apart from the interpreter, we created challenges and levels to guide the players from the basics of Python, basic data types, and operators, all the way to common built-in functions. To integrate the interpreter with the game built upon Unity, we lowered the .Net version to .Net Framework 3.x for compatibility reasons. To prevent players' buggy code, such as infinite loops, from blocking the main thread of the game, we isolated the interpreter to another thread, while passing the commands to and from the main thread using the producer-consumer pattern. The game created an interesting approach to learning Python with a real interpreter while conquering game levels and challenges.

## WIP
