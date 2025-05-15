I solve this one fully using the erros showing when ```cargo build``` this is my first time dealing with language that explain the error and how to fix it, rust is a great language

```
sudo apt install rustc
wget https://challenge-files.picoctf.net/c_verbal_sleep/babfbee79718a6363826ba86300173ffde6d81577e9dd07d4130c53a7eecf6c3/fixme2.tar.gz
tar -xf fixme2.tar.gz
cd fixme2
cargobuild
```

```
line#3 - before: fn decrypt(encrypted_buffer:Vec<u8>, borrowed_string: &String){
line#3 - after: fn decrypt(encrypted_buffer:Vec<u8>, borrowed_string: &mut String){

line#34 - before: let party_foul = String::from("Using memory unsafe languages is a: ");
line#34 - after: let mut party_foul = String::from("Using memory unsafe languages is a: ");

line#35 - before:     decrypt(encrypted_buffer, party_foul);
line#35 - after:    decrypt(encrypted_buffer, &mut party_foul);
```

```
 picoCTF{*r*_*0*_*4*1*5*f*n*y*1*}
```

<!--picoCTF{4r3_y0u_h4v1n5_fun_y31?}-->
