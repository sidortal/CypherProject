
<p align="center">
  <img src="https://github.com/sidortal/assests/blob/main/shield_animation.gif" width="300" height="200" />
</p>

### 🛡️ In-Depth Explanation of Caesar Cipher Functions 🔐

1. **`caesar_cipher_encrypt` Function:**
   - 🛠️ This function encrypts a given plaintext string using the Caesar cipher technique.
   - 🔄 It iterates through each character in the input string.
   - 🔠 If a character is a letter (either uppercase or lowercase), it shifts the character by a specified amount (shift) to generate the encrypted character.
   - ➰ The shift amount is calculated using modulo 26 to ensure it wraps around when exceeding the alphabet range.
   - 🔣 Non-alphabetic characters remain unchanged.

2. **`caesar_cipher_decrypt` Function:**
   - 🔓 This function decrypts a given encrypted text using the Caesar cipher technique.
   - 🔄 It simply calls the `caesar_cipher_encrypt` function with the negative shift value to reverse the encryption.
   - 🔁 The same shift value that was used for encryption is now used for decryption, but in the opposite direction.

3. **`main` Function:**
   - ⌨️ This function prompts the user to input a text string and a shift value.
   - 🔒 It calls the `caesar_cipher_encrypt` function to encrypt the text using the specified shift.
   - 🔓 It then calls the `caesar_cipher_decrypt` function to decrypt the encrypted text and display the original text.
   - 🎯 The goal is to showcase the symmetric nature of the encryption and decryption mechanism using the same shift value.

In summary, the code implements a symmetric Caesar cipher encryption and decryption mechanism using a specified shift value and showcases user interaction to process input and output.


<p align="center">
  <img src="https://github.com/sidortal/assests/blob/main/encryptiondribble.gif" width="300" height="200" />
</p>

---

### 🔗 Additional Resources and Links:

📁 **Main Code File (.txt)**  
[View Code](https://github.com/sidortal/CypherProject/blob/main/CypherMainCode.txt)  

📖 **What is Cypher? Resources and Article**  
[Watch Video](https://youtu.be/aOdxWtqibCI)  

📚 **Resources and Article**  
[Read Article](https://www.techtarget.com/searchsecurity/definition/cipher)  

📄 **Issued LOR by DBATU University**  
[View LOR](https://github.com/sidortal/CypherProject/blob/main/CybersecurityLOR.pdf)  

---



---

> "Encryption: Turning the ordinary into the extraordinary, one character at a time!" 🎉🔐

---
