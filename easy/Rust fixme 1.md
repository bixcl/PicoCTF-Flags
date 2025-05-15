<b>resource<b><br> 
1-Gemini<br>
2-println -> https://doc.rust-lang.org/std/macro.println.html <br>

downloading the file:

```
wget https://challenge-files.picoctf.net/c_verbal_sleep/3f0e13f541928f420d9c8c96b06d4dbf7b2fa18b15adbd457108e8c80a1f5883/fixme1.tar.gz
tar -xf fixme1.tar.gz
cd fixme2
```

If you try to build the code you will see the erros and you can fix it

```
cargo build
```

fixes: before and after

```
# line 5
before:    let key = String::from("CSUCKS")
after:     let key = String::from("CSUCKS");

# line 18
before:        ret;
after:         return;

# line 24
before:    println!(":?",
after:     println!("{}",
```

```flag
picoCTF{*r*_*0*_*_*u*t*c*0*_*0*?}
```

<!--picoCTF{4r3_y0u_4_ru$t4c30n_n0w?}-->
