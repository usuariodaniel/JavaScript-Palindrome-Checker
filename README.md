# JavaScript Palindrome Checker

This is a simple JavaScript program that checks if a given word is a palindrome or not. A palindrome is a word, phrase, number, or other sequence of characters that reads the same backward or forward, ignoring spaces, punctuation, and capitalization.

## How to Use

1. Run the JavaScript code in a browser or a JavaScript environment like Node.js.
2. The program will prompt you to enter a word.
3. The program will then check if the entered word is a palindrome or not.
4. If the word is a palindrome, it will alert "Word is a palindrome!".
5. If the word is not a palindrome, it will alert "Word is not a palindrome!" along with the original and reversed words for comparison.

## Example

For example, if you enter the word "racecar", the program will alert "racecar is a palindrome!".

## How it Works

1. The first line `const word = prompt("Enter a word");` prompts the user to enter a word. The entered word is stored in the variable `word`.

2. The next line `let invertedWord = "";` initializes an empty string `invertedWord`. This string will later hold the reversed version of the user-inputted word.

3. The `for` loop that follows is used to reverse the user-inputted word. It starts from the end of the word `(index word.length - 1)` and goes to the beginning `(index 0)`. In each iteration, it appends the current character `(word[i])` to `invertedWord`.

4. After the word is reversed, the `if` statement checks whether the original word and the reversed word are the same. If they are, it means the word is a palindrome, and an alert is shown to the user stating that the word is a palindrome. If they are not the same, it means the word is not a palindrome, and an alert is shown to the user stating that the word is not a palindrome, along with the original and reversed words for comparison

## Note

This code doesn't handle cases where the input may contain special characters or spaces. For more robust palindrome checking, consider removing non-alphanumeric characters and converting the input to lowercase before checking.

## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these steps:

1. Fork this repository.
2. Create a branch with a descriptive name for your change.
3. Make your changes to the created branch.
4. Submit a pull request to the master branch of this repository.

---

## Contact

If you have any questions or suggestions, please contact me via my email or my GitHub profile.

---

## Thanks

This project was made possible thanks to the support and guidance of OneBitCode

---

## References

This project was inspired by a OneBitCode challenge
