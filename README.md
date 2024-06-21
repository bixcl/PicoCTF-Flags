1- PW Crack 3 : picoCTF{m45h_fl1ng1ng_6f98a49f}

2- HashingJobApp : picoCTF{4ppl1c4710n_r3c31v3d_3eb82b73} : https://www.md5hashgenerator.com/

3- PW Crack 4 : picoCTF{fl45h_5pr1ng1ng_cf341ff1}

4- PW Crack 5 : picoCTF{h45h_sl1ng1ng_fffcda23} : use .strip() after inside for 

5- runme.py : picoCTF{run_s4n1ty_run} : just run the python file 

6- Serpentine : picoCTF{7h3_r04d_l355_7r4v3l3d_aa2340b2} : the code is ready , just you need it to run the function 

7- basic-mod1 : picoCTF{r0und_n_r0und_79c18fb3}

8- Static ain't always noise : picoCTF{d15a5m_t34s3r_ae0b3ef2} || picoCTF{d15a5m_t34s3r_f6c48608} : use sh <bash file name> <static file > than search for the flag 

i-

```bash
sh ltdis.sh static
```
ii-

```bash
cat static.ltdis.strings.txt | grep "pico"
```

iii-copy the flag and past it in web site

9- repetitions : picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_dfe803c6} || picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_492767d2} : need multible base 64 decode

10- ASCII Numbers : picoCTF{45c11_n0_qu35710n5_1ll_t311_y3_n0_l135_445d4180} : ASCII codenc jupiter.challenges.picoctf.org 29221

11- mus1c : picoCTF{rrrocknrn0113r} : decrypt the song with https://codewithrockstar.com/online and convert the out from ascii to text

12- The numbers : picoctf{thenumbersmason} : use the sub table - like the table of ceaser cipher

13- crackme-py : picoCTF{1|\/|_4_p34|\|ut_a79b6c2d} : run the decode function 

14- Magikarp Ground Mission : picoCTF{xxsh_0ut_0f_\/\/4t3r_540e4e79} || picoCTF{xxsh_0ut_0f_\/\/4t3r_c1754242} : p1/ls , p2/cd / , p3/ cd ~

15- Glory of the Garden : picoCTF{more_than_m33ts_the_3y3657BaB2C} : string garden.jpg | grep "pico"

16- Lookey here : picoCTF{gr3p_15_@w3s0m3_4c479940} : cat anthem.flag.txt | grep "pico"

17- Inspect HTML : picoCTF{1n5p3t0r_0f_h7ml_1fd8425b} : just inspect HTML

18- file-run1 : picoCTF{U51N6_Y0Ur_F1r57_F113_47cf2b7b} : chmod +x <file name> / ./<file name>

19- includes : picoCTF{1nclu51v17y_1of2_f7w_2of2_df589022} : incpect the css code and the js

20- Local Authority : picoCTF{j5_15_7r4n5p4r3n7_05df90c8} : enter random values than inspect the js file and you will get the id and pass

21- keygenme-py : picoCTF{1n_7h3_|<3y_of_01582419} : this one is hard, you can search the internet

22- tunn3l v1s10n : picoCTF{qu1t3_a_v13w_2020} 
    how i solve it ?     
i- know that this is a bmp file by doing exiftool

ii- its not opening becouse the file is currepted

iii- try to fix the hex of the file by open it in < https://hexed.it/ > then comper the hex header with another image to fix it 

iv-after that you can open the image in photopea < https://www.photopea.com/ > becouse it can open this type of file even the currepted file that we start with


23- Get aHEAD : picoCTF{r3j3ct_th3_du4l1ty_2e5ba39f} : 

i- use burb suite 

ii- go to proxy and press open then a braowser will show up <past the link there> and go back burb suite

iii- from proxy page you will have new thing called get or post of something like that 

iv- press right-click on that and then send to repeater

v- from repeater page change the POST to >> HEAD

vi- then press send 

vii- you will have teh flag

24- pw crack 1 : picoCTF{545h_r1ng1ng_1b2fd683} :


i- open the python file

ii- read the code and you will find the password = **8713**

iii- copy the password and run the python program using 

```bash
python3 level1.py level1.flag.txt.enc
```

25- pw crack 2 : picoCTF{tr45h_51ng1ng_9701e681} :

i- open the python file

ii- read the code and you will find if statement to **chr** function copy all the **chr** and print it 

iii- the output will be **4ec9**

iv- copy the password and run the python program using 

```bash
python3 level2.py level2.flag.txt.enc
```

 
