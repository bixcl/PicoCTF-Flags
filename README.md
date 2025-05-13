in this repo i explain how to solve some of PicoCTF challenge, some of them i upload only the flage, and some i explain in short.


39-Super SSH:
```bash
ssh ctf-player@titan.picoctf.net -p 52828
```
```bash
picoCTF{s3cur3_c0nn3ct10n_65a7a106}
```
<br><br><br>
40- introtobutp : intersting one, you need to download burp suite and go to proxy tab than intercption on, than open the burp suite browser and paste url than enter, the site will load so you need to return to burp and press forword, than fill all filed and press forword than the site will ask for OTP, enter anything and press enter but don't do forword yet, go back to burp suite and you will see some info go down and change otp to otgp than press forword
```bash
picoCTF{#0TP_Bypvss_SuCc3$S_9090d63c}
```
<br><br><br>
41- Secret of the Polyglot : this is an intersting one,<br>
1- open the pdf normaly and you will found part of the flag, if you try to read it you will notice that it said, "in png and pdf", that mean one part in png file and other is this that you are reading.<br>
2- to convert pdf file into png file you can use :
```bash
cp flag2of2-final.pdf flag.png

where flag2of2-final.pdf is the orginal pdf file and , flag.png is the converted fiel
```
3. after converting try to open png file and you will found that the other part of the flag is visible for you.<br>
4. marge them togather to form complete flag and submit.
```bash
picoCTF{f1u3n7_1n_pn9_&_pdf_724b1287}
```
<br><br><br>
41 - dont-use-client-side : <br>
1- inspect the page and expand all under the script, you will find check statement<br>
2- sort this check based on split number<br>
```bash
picoCTF{no_clients_plz_7723ce}
```
<br><br><br>
42 - endianess:<br>
```text
one of the best ctf i ever solve, it make me learn the convept of endian in computer,
1- to solver this prolem you shouls first understand endian concept
endiant convept where every hex numbers is suprated into group of 2,
left side to right side will be little endian and righ to left will be big endian,
2- to solve this you need first to reverse the word given, that will help you to get little endian first becouse they ask for it first
3- than convert the new word to hex and copy the result and paste it in the nc program
4- copy the flag and submit

the flag could be diffrent
picoCTF{3ndi4n_sw4p_su33ess_91bc76a4}

```
<br>
43 - Collaborative Development:

```text
this challeng is fantastic to learn more about git command, it will teach you how to switch betweem branches
```

```bash
cd drop-in/
git log
git show
git brach -a
git switch <branch1 name>
git show => part one of the flag
git switch <branch3 name>
git show => part two of the flag
git switch <branch3 name>
git show => part three of the flag
```

```flag
picoCTF{t3@mw0rk_m@k3s_th3_dr3@m_w0rk_7ffa0077}
```

44 - St3g0
```
this challend is cool, i started by checking the image using exif tool

exiftool flag.png // found nothing there

than trys strings and there where something in the last line, file called secrete

strings flag.png

thats mean there are hidden files and this mean that this is steganography challend and we should use tools like binwalk

binwalk -e flag.png

// note: i face problem in running binwalk on ubuntu at first becouse there is a library calld angr was no installed by default

sudo apt install binwalk
pip install angr

than we will find a folder called secret and inside this folder there is a new image, if we try to open it we will find the flag : picoCTF{Hiddinng_An_imag3_within_@n_ima9e_cda72af0}
![flag](https://github.com/user-attachments/assets/88171a03-7d0e-4efa-be87-b2334b78c078)

flag is : 
```

***Made by Bxl***



