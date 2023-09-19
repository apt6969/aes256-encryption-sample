./encrypt -e filename 
./encrypt -d filename

The password to decrypt pokimane.jpg.aes is just 'pokimane'

Just change pokimane.jpg.aes.decrypt to pokimane.jpg or pokimane.jpeg to get the picture to load

Do it serially or sequentially to fool the NSA. Notice now pokimane.jpg.aes is ciphertext but pokimane.jpg.aes.decrypt is plaintext which is the exact same plaintext as pokimane.jpg, except you have to change the file type to .jpg or .jpeg for your OS to recognize the plaintext as an image. (in most circumstances; here's where the potential zero-days come into play, because your OS may not notice some extra 1s or 0s being executed by an innocent looking pokimane.jpg, etc.)

For example, for serial/sequential encryption, you might want pokimane.jpg.aes.aes but you'd have to remember the order of, in this script, two different secret keys, for encryption.

The password to decrypt pokimane.jpg.aes.aes.decrypt is 'pokimane2'

You can imagine altering the script to encrypt whatever you want in more complex ways to really fool the NSA.

The encrypt file is actually a text file i changed with chmod +x so it's executable; you can open it with a text editor
