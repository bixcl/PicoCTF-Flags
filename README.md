# PicoCTF flags <br>
**Notes before solving:**<br>
--- anything i write it between < > mean that you need to write the name of the file giving to you <br>
--- some challenges contain 2 or more so you need to apply the steps and solve it your self with your file <br><br>
1- PW Crack 3 : picoCTF{m45h_fl1ng1ng_6f98a49f}<br>
2- HashingJobApp : picoCTF{4ppl1c4710n_r3c31v3d_3eb82b73} : https://www.md5hashgenerator.com/ <br>
3- PW Crack 4 : picoCTF{fl45h_5pr1ng1ng_cf341ff1} <br>
4- PW Crack 5 : picoCTF{h45h_sl1ng1ng_fffcda23} : use .strip() after inside for <br>
5- runme.py : picoCTF{run_s4n1ty_run} : just run the python file <br>
6- Serpentine : picoCTF{7h3_r04d_l355_7r4v3l3d_aa2340b2} : the code is ready , just you need it to run the function <br>
7- basic-mod1 : picoCTF{r0und_n_r0und_79c18fb3} <br>
8- Static ain't always noise : picoCTF{d15a5m_t34s3r_ae0b3ef2} || picoCTF{d15a5m_t34s3r_f6c48608} : use sh <bash file name> <static file > than search for the flag <br>
```bash
sh ltdis.sh static
```
```bash
cat static.ltdis.strings.txt | grep "pico"
```
<br>
    --- copy the flag and past it in web site <br> <br>
9- repetitions : picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_dfe803c6} || picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_492767d2} : need multible base 64 decode <br>
10- ASCII Numbers : picoCTF{45c11_n0_qu35710n5_1ll_t311_y3_n0_l135_445d4180} : ASCII codenc jupiter.challenges.picoctf.org 29221 <br>
11- mus1c : picoCTF{rrrocknrn0113r} : decrypt the song with https://codewithrockstar.com/online and convert the out from ascii to text <br>
12- The numbers : picoctf{thenumbersmason} : use the sub table - like the table of ceaser cipher <br>
13- crackme-py : picoCTF{1|\/|_4_p34|\|ut_a79b6c2d} : run the decode function <br>
14- Magikarp Ground Mission : picoCTF{xxsh_0ut_0f_\/\/4t3r_540e4e79} || picoCTF{xxsh_0ut_0f_\/\/4t3r_c1754242} : p1/ls , p2/cd / , p3/ cd ~ <br>
15- Glory of the Garden : picoCTF{more_than_m33ts_the_3y3657BaB2C} : 

```bash
string garden.jpg | grep "pico"
```
16- Lookey here : picoCTF{gr3p_15_@w3s0m3_4c479940} : 
```bash
cat anthem.flag.txt | grep "pico"
```
17- Inspect HTML : picoCTF{1n5p3t0r_0f_h7ml_1fd8425b} : just inspect HTML <br> <br>
18- file-run1 : picoCTF{U51N6_Y0Ur_F1r57_F113_47cf2b7b} : 
```bash
chmod +x <file name> / ./<file name>
```
19- includes : picoCTF{1nclu51v17y_1of2_f7w_2of2_df589022} : incpect the css code and the js <br>
20- Local Authority : picoCTF{j5_15_7r4n5p4r3n7_05df90c8} : enter random values than inspect the js file and you will get the id and pass <br>
21- keygenme-py : picoCTF{1n_7h3_|<3y_of_01582419} : this one is hard, you can search the internet <br>
22- tunn3l v1s10n : picoCTF{qu1t3_a_v13w_2020} <br><br>
    --- know that this is a bmp file by doing exiftool <br>
    --- its not opening becouse the file is currepted <br>
    --- try to fix the hex of the file by open it in < https://hexed.it/ > then comper the hex header with another image to fix it <br>
    --- after that you can open the image in photopea < https://www.photopea.com/ > becouse it can open this type of file even the currepted file that we start with <br><br>
23- Get aHEAD : picoCTF{r3j3ct_th3_du4l1ty_2e5ba39f} : <br><br>
    --- use burb suite <br>
    --- go to proxy and press open then a braowser will show up <past the link there> and go back burb suite <br>
    --- from proxy page you will have new thing called get or post of something like that <br>
    --- press right-click on that and then send to repeater <br>
    --- from repeater page change the POST to >> HEAD <br>
    --- then press send <br>
    --- you will have teh flag <br><br>
24- pw crack 1 : picoCTF{545h_r1ng1ng_1b2fd683} : <br><br>
    --- open the python file <br>
    --- read the code and you will find the password = **8713** <br>
    --- copy the password and run the python program using <br>
```bash
python3 level1.py level1.flag.txt.enc
```
<br>
25- pw crack 2 : picoCTF{tr45h_51ng1ng_9701e681} : <br><br>
    --- open the python file <br>
    --- read the code and you will find if statement to **chr** function copy all the **chr** and print it <br>
    --- the output will be **4ec9** <br>
    --- copy the password and run the python program using 

```bash
python3 level2.py level2.flag.txt.enc
```
<br>
26- Mind your Ps and Qs : picoCTF{sma11_N_n0_g0od_45369387} :

```bash
wget < link >
cat values
```

--- you will find < C, E, N > <br   >
--- open https://www.dcode.fr/rsa-cipher and past each value in there place and then press calculate / decrypt

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

28-Matryoshka doll : picoCTF{ac0072c423ee13bfc0b166af72e25b61} : <br>
**Note** you need to install ***binwalk tool***
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
use the location of **Target File**
--- last, you will find the flag 

29- Insp3ct0r : picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?832b0699} : <br>
--- easy challing, just inspect the page, the flage is splited into 3 part<br> 
---- first one you will find it in HTML part<br> 
---- second one you will find it in CSS part<br>
---- third one you will find it in JS part<br>

***Made by Bxl***

