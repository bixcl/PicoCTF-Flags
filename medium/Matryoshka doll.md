28-Matryoshka doll : picoCTF{ac0072c423ee13bfc0b166af72e25b61} : <br>
Category: Forensics<br>
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
