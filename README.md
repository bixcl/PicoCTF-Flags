# PicoCTF flags //writeups <br>
**Notes before solving:**<br>
--- anything i write it between < > mean that you need to write the name of the file giving to you 
--- some challenges contain 2 or more so you need to apply the steps and solve it your self with your file 
<br><br><br>
1- PW Crack 3 : picoCTF{m45h_fl1ng1ng_6f98a49f}
<br><br><br>
2- HashingJobApp : picoCTF{4ppl1c4710n_r3c31v3d_3eb82b73} : https://www.md5hashgenerator.com/ 
<br><br><br>
3- PW Crack 4 : picoCTF{fl45h_5pr1ng1ng_cf341ff1} 
<br><br><br>
4- PW Crack 5 : picoCTF{h45h_sl1ng1ng_fffcda23} : use .strip() after inside for 
<br><br><br>
5- runme.py : picoCTF{run_s4n1ty_run} : just run the python file 
<br><br><br>
6- Serpentine : picoCTF{7h3_r04d_l355_7r4v3l3d_aa2340b2} : the code is ready , just you need it to run the function 
<br><br><br>
7- basic-mod1 : picoCTF{r0und_n_r0und_79c18fb3} 
<br><br><br>
8- Static ain't always noise : picoCTF{d15a5m_t34s3r_ae0b3ef2} || picoCTF{d15a5m_t34s3r_f6c48608} : use sh <bash file name> <static file > than search for the flag <br>
```bash
sh ltdis.sh static
```
```bash
cat static.ltdis.strings.txt | grep "pico"
```
<br>
    --- copy the flag and past it in web site 

<br><br><br>
9- repetitions : picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_dfe803c6} || picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_492767d2} : need multible base 64 decode 
<br><br><br>
10- ASCII Numbers : picoCTF{45c11_n0_qu35710n5_1ll_t311_y3_n0_l135_445d4180} : ASCII codenc jupiter.challenges.picoctf.org 29221 
<br><br><br>
11- mus1c : picoCTF{rrrocknrn0113r} : decrypt the song with https://codewithrockstar.com/online and convert the out from ascii to text 
<br><br><br>
12- The numbers : picoctf{thenumbersmason} : use the sub table - like the table of ceaser cipher 
<br><br><br>
13- crackme-py : picoCTF{1|\/|_4_p34|\|ut_a79b6c2d} : run the decode function 
<br><br><br>
14- Magikarp Ground Mission : picoCTF{xxsh_0ut_0f_\/\/4t3r_540e4e79} || picoCTF{xxsh_0ut_0f_\/\/4t3r_c1754242} : p1/ls , p2/cd / , p3/ cd ~ 
<br><br><br>
15- Glory of the Garden : picoCTF{more_than_m33ts_the_3y3657BaB2C} : 

```bash
string garden.jpg | grep "pico"
```

<br><br><br>
16- Lookey here : picoCTF{gr3p_15_@w3s0m3_4c479940} : 
```bash
cat anthem.flag.txt | grep "pico"
```

<br><br><br>
17- Inspect HTML : picoCTF{1n5p3t0r_0f_h7ml_1fd8425b} : just inspect HTML 
<br><br><br>
18- file-run1 : picoCTF{U51N6_Y0Ur_F1r57_F113_47cf2b7b} : 
```bash
chmod +x <file name> / ./<file name>
```

<br><br><br>
19- includes : picoCTF{1nclu51v17y_1of2_f7w_2of2_df589022} : incpect the css code and the js 
<br><br><br>
20- Local Authority : picoCTF{j5_15_7r4n5p4r3n7_05df90c8} : enter random values than inspect the js file and you will get the id and pass <br>
<br><br><br>
21- keygenme-py : picoCTF{1n_7h3_|<3y_of_01582419} : this one is hard, you can search the internet 

<br><br><br>
22- tunn3l v1s10n : picoCTF{qu1t3_a_v13w_2020} <br><br>
    --- know that this is a bmp file by doing exiftool <br>
    --- its not opening becouse the file is currepted <br>
    --- try to fix the hex of the file by open it in < https://hexed.it/ > then comper the hex header with another image to fix it <br>
    --- after that you can open the image in photopea < https://www.photopea.com/ > becouse it can open this type of file even the currepted file that we start with

<br><br><br>
23- Get aHEAD : picoCTF{r3j3ct_th3_du4l1ty_2e5ba39f} : <br><br>
    --- use burb suite <br>
    --- go to proxy and press open then a braowser will show up <past the link there> and go back burb suite <br>
    --- from proxy page you will have new thing called get or post of something like that <br>
    --- press right-click on that and then send to repeater <br>
    --- from repeater page change the POST to >> HEAD <br>
    --- then press send <br>
    --- you will have teh flag 

<br><br><br>
24- pw crack 1 : picoCTF{545h_r1ng1ng_1b2fd683} : <br><br>
    --- open the python file <br>
    --- read the code and you will find the password = **8713** <br>
    --- copy the password and run the python program using <br>
```bash
python3 level1.py level1.flag.txt.enc
```

<br><br><br>
25- pw crack 2 : picoCTF{tr45h_51ng1ng_9701e681} : <br><br>
    --- open the python file <br>
    --- read the code and you will find if statement to **chr** function copy all the **chr** and print it <br>
    --- the output will be **4ec9** <br>
    --- copy the password and run the python program using 

```bash
python3 level2.py level2.flag.txt.enc
```

<br><br><br>
26- Mind your Ps and Qs : picoCTF{sma11_N_n0_g0od_45369387} :

```bash
wget < link >
cat values
```
--- you will find < C, E, N > <br   >
--- open https://www.dcode.fr/rsa-cipher and past each value in there place and then press calculate / decrypt

<br><br><br>
27- Tab. Tab, Attack : picoCTF{l3v3l_up!_t4k3_4_r35t!_76266e38} :  <br>

--- first, get the file with **wget** <br>
--- second, unzip the file with <br>
```bash
unzip <file-name >
```
third, just write cd - than space and press tab untl no file there to go <br>
forth, in this step u will find a file with out extesion. this mean this file need to conver to executable file, do this<br>
```bash
chmod +x <file-name >
```

last, run the exicutable file by typing:

```bash
./file-name
```

<br><br><br>
28-Matryoshka doll : picoCTF{ac0072c423ee13bfc0b166af72e25b61} : <br>
**Note** you need to install ***binwalk tool***<br>
--- first, download the image with **wget** <br>
--- second, from the challend name we know that ther is file insider files so we will use the **binwalk** to extract it but if we use it like that nothin will happend, becouse we need to make sure that the extesion of file is right by writing: <br>
```bash
file <image-name >
dolls.jpg: PNG image data, 594 x 1104, 8-bit/color RGBA, non-interlaced
```
the image in jpg type but the real type is png, so we need to change it by typing<br>
```bash
mv <old-image-name.jpg > <new-image-name.png > 
``` 
--- third, now we can use **binwalk** and we know that binwalk has a function called **-M** that can extract file from file form file that mean it can extract the file form matroyshka doll, so the command will be:<br>
```bash
binwalk -M -e <new-image-name.png >
```
--- forth, you will have lot of output in your terminal page but if you go all the way down, you will find somthing called ***Target File** , simply copy the file extesion and do this: <br>
```bash
cat /home/bxl/Desktop/pico2/_dolls.png.extracted/base_images/_2_c.jpg.extracted/base_images/_3_c.jpg.extracted/base_images/_4_c.jpg.extracted/flag.txt
```
**Note**<br>
use the location of **Target File** <br>
--- last, you will find the flag 

<br><br><br>
29- Insp3ct0r : picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?832b0699} : <br>
--- easy challing, just inspect the page, the flage is splited into 3 part<br> 
---- first one you will find it in HTML part<br> 
---- second one you will find it in CSS part<br>
---- third one you will find it in JS part<br>

30- Warmed UP : picoCTF{61} <br>
--- copy the hex number giver (**3D**) and use this website to convert it to decimal (base 19) : https://www.unitconverters.net/numbers/base-16-to-base-10.htm
<br><br><br>

31- 2warm : picoCTF{101010} : <br>
--- u can solve it by using the tool that i made, you can find it in my github : @bixcl , the repository called (**D2B**) or u can use this website : https://www.unitconverters.net/numbers/base-10-to-base-2.htm
<br><br><br>

32- strings it : picoCTF{5tRIng5_1T_827aee91} <br>
--- first, you need to download the file given <br>
```bash
strings strings | grep pico
```
<br><br><br>

33- Easy1 : picoCTF{CRYPTOISFUN} => easy one just you need to use this web site or even use the table given to decrypt the message.<br>
```bash
website : https://www.boxentriq.com/code-breaking/one-time-pad
```

<br><br><br>

34- Heap 0 :(the flag could differ) => yout need to make buffer overflow by entring buffer page (2) and give latters more than 64 time, after that just press enter and the flag will be availabe if you go to (4).<br>
```bash
picoCTF{my_first_heap_overflow_c3935a08}
```

<br><br><br>
35- format string 0 : at first i solve it using brute force by tring al choises but then after read the code file and knowing that it writen in C, i understande that i should choose the words that contain something could intract with C lang like % <br>
```bash
picoCTF{7h3_cu570m3r_15_n3v3r_SEGFAULT_a1d85b3e}

the flag could be diffrent
```
<br><br><br>

36 - WebDecode : <br> 1- go to the website<br>2- go to about page<br>3- inspect this page and you will find encrypted code in inspector page<br>4- copy this link and paste it to any base64 decrypter

```bash
picoCTF{web_succ3ssfully_d3c0ded_f6f6b78a}

the flag could be diffrent
```
<br><br><br>
37-
<br>ispect the page and you will find it within HTML text
```bash
picoCTF{pr3tty_c0d3_622b2c88}
```
<br><br><br>
38-Time Machine:install git by
```bash
sudo apt install git
```
than inside the unzipped folder write this:
```bash
git log
```
```bash
picoCTF{t1m3m@ch1n3_e8c98b3a}
```
<br><br><br>
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



