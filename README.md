**Write-Up: FOX-FOSTER Cryptography CTF Challenge - Step-by-Step Guide**

Welcome to the detailed step-by-step write-up for the FOX-FOSTER Cryptography CTF challenge on TryHackMe. This comprehensive guide will walk you through each question, providing detailed explanations of the techniques used to decrypt the messages.

**Question 1: Decrypt with a Keyword (Caesar Cipher)**

1. Analyze the encrypted message: "Uvagxh kj rwx ygp qtvfgk."
2. The hint suggests that a keyword helps in decrypting. The keyword provided is 'CRYPTO.'
3. Apply the Caesar cipher technique with the keyword 'CRYPTO.' Shift each letter by the corresponding letter's position in the keyword.
4. Decrypt the message to unveil the hidden meaning: "Secret is the key secret."

**Question 2: Deciphering with a Shift (Vigenère Cipher)**

1. Examine the encrypted message: "Hyhub lv d wuxh pbvwhub."
2. The hint indicates a simple shift is involved.
3. Apply the Vigenère cipher technique by shifting each letter in the message using a certain pattern.
4. Decrypt the message to reveal the original text: "Every is a true mystery."

**Question 3: Keyword Decryption Revisited (Playfair Cipher)**

1. Observe the encrypted message: "EUHXKDQLVKRZIT."
2. The hint advises using a keyword for decryption and replacing uncommon letters.
3. The keyword provided is 'KEYWORD.'
4. Apply the Playfair cipher technique using the keyword 'KEYWORD' to decrypt the message.
5. Uncover the original message: "UNIVERSITYCTF."

**Question 4: Binary Decoding and Transposition**

1. Examine the given binary sequence: "01000101 01001111 01010010 01001000 01001100 01001111 01000100 01001100 01010111 01001100."
2. Decode the binary sequence into text: "EORHLODLWL."
3. The hint suggests manipulating the characters using a distinct pattern to achieve the transposed message.
4. Rearrange the characters using a transposition pattern to reveal the final message: "Hello World."

**Question 5: Decoding with a Morse Code Twist**

1. Interpret the Morse code message: "--- -... -.-- -.-- ..-. / -... .-- / -.-. .--. --.. .--. .- / -- ...- . -- ...- --.. .- .-.. -.-- .-.-.- .--- ...- -."
2. Convert the Morse code into text: "OBYYF BW CPZPA MVEMVZALY.JVT."
3. The hint suggests starting by converting Morse code to readable text and then using a small shift for decryption.
4. Apply a small shift to decode the text: "HURRY UP VISIT FOXFOSTER.COM."

Congratulations! You've successfully completed the FOX-FOSTER Cryptography CTF challenge. Your mastery of various cryptographic techniques has enabled you to decipher encrypted messages and uncover their hidden meanings. We hope you enjoyed the challenge and gained insights into the fascinating world of cryptography.

Thank you for participating, and keep honing your cryptographic skills for even greater adventures in the realm of codebreaking!

