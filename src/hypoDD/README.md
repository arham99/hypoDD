## Cara Menjalankan program hypoDD
program hypoDD dijalankan dengan menggunakan output program ph2dt sebagai input.
input file yang digunakan diantaranya adalah :
- file cross correlation ==> dt.cc
- file catalog ==> dt.ct
- file event ==> event.sel
- file stasiun ==> sta_TA.dat

penjelasan lebih lanjut mengenai file input dapat diakses melalui [link](https://www.ldeo.columbia.edu/~felixw/papers/Waldhauser_OFR2001.pdf) ini, 
dokumen tersebut juga ada di file doc

untuk menjalankan program hypoDD. nama file input harus dimasukkan pada control file `hypoDD.inp`

### Running Program hypoDD
buka terminal ==> masuk ke direktori file ==> run
```
cd src/hypoDD
./hypoDD hypoDD.inp

```

