# Spell Check++

## Introduction
Spell Check++ is an intelligent spelling companion that ensures error-free writing by providing smart suggestions. It leverages an open-source dictionary library to check the correctness of words and offer possible corrections for misspelled terms.

## How it Works
Spell Check++ is built on top of an existing library called "dictionary," which was developed and open-sourced by [madhav-dutt](https://github.com/madhav-datt/spell-check). The project offers two main functionalities:

1. **Word Correctness Check**: The program checks the given word against a trie data structure, which is built by loading all the words from the dictionary text file. This functionality utilizes the "check" function provided by the dictionary library.

2. **Word Correction**: When a word is misspelled, the program manipulates the word and uses the "check" function to determine the correctness of the modified word. If the modified word is found in the dictionary, it is suggested as a possible correct spelling.

In addition to these core functions, the program also utilizes the "load" and "unload" functions to build and destroy the trie tree, respectively.

## Demo
[Embed a Demo video here]

## Usage
To use Spell Check++, follow these steps:

1. Fork this repository and open it in Codespaces, or clone it if you prefer to run it locally.
2. Open the terminal and navigate to the "source" directory.
3. Run the `make` command to compile the program.
4. Execute the program using the command: `./a.out "THE_ACTUAL_WORD_YOU_WANT_TO_CHECK_OR_CORRECT"`.

## Acknowledgments
Special thanks to[madhav-dutt](https://github.com/madhav-datt/spell-check) for their bulding and open-sourcing the dictionary library.

## Contributing
There is always room for improvement. If you have any feedback or suggestions, please feel free to open an issue or submit a pull request. Together, we can build a better future through open-source collaboration.

Happy coding!
