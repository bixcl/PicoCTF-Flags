
44 - St3g0
```
this challeng is cool, i started by checking the image using exif tool

exiftool flag.png // found nothing there

than trys strings and there where something in the last line, file called secrete

strings flag.png

thats mean there are hidden files and this mean that this is steganography challend and we should use tools like binwalk

binwalk -e flag.png

// note: i face problem in running binwalk on ubuntu at first becouse there is a library calld angr was not installed by default

sudo apt install binwalk
pip install angr

than we will find a folder called secret and inside this folder there is a new image, if we try to open it we will find the flag : picoCTF{Hiddinng_An_imag3_within_@n_ima9e_cda72af0}
![flag](https://github.com/user-attachments/assets/88171a03-7d0e-4efa-be87-b2334b78c078)

flag is : 
```
