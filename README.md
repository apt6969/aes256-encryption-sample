./encrypt -e filename 
./encrypt -d filename

The password to decrypt pokimane.jpg.aes is just 'pokimane'

Just change pokimane.jpg.aes.decrypt to pokimane.jpg or pokimane.jpeg to get the picture to load

Do it serially or sequentially to fool the NSA. Notice now pokimane.jpg.aes.decrypt is ciphertext, just like pokimane.jpg is plaintext (except it's represented as a picture by your OS)

For example you might want pokimane.jpg.aes.aes but you'd have to remember the order of, in this script, two different secret keys, for encryption.

the encrypt file is actually a text file i changed with chmod +x so it's executable; you can open it with a text editor
