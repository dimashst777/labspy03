# labspy03

# LATIHAN 1

## SOURCE CODE  


n=int(input("Masukkan Nilai N: "))          ## Memperkenalkan variable n sebagai integer, kemudian menginputkan nilainya

from random import random                   ## Mengimport fungsi random
a=random()                                  ## Memperkenalkan variale a sebagai random

jumlah=n+1                                  ## Jumlah = varible n + 1
start=1                                     ## Dimulai dari angka 1
stop=jumlah                                 ## Berhenti ketika variable jumlah sudah sesuai
step=1                                      ## Step angka 1

for i in range(start,stop,step):            ## Perulangan i dengan nilai awal variable start, nilai akhir variable stop dan step variable step
    print("data ke : ",i,"=",(a))           ## Mencetak hasil
print("\nDone")


## ALGORITMA  

A. Input  
    Print
        >> print berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.  
    from random import random  
        >> import yaitu fungsi lanjut yang dipanggil oleh statement import.sedangankan random untuk menentukan suatu  
        pilihan. yang berarti menggabungkan dua operasi.  
    a=random()  
        >> memperkenalkan variabel a sebagai random  
    jumlah=n+1  
        >> Jumlah = varible n + 1  
    start=1  
        >> Dimulai dari angka 1  
    stop=jumlah  
        >> Berhenti ketika variable jumlah sudah sesuai  
    step=1  
        >> Step angka 1  
        
B. Process   
    n = int(input("Masukan Nilai N: "))  
        >>merupakan fungsi untuk menghasilkan integer  
    for i in range(start,stop,step):  
        >>Perulangan i dengan nilai awal variable start, nilai akhir variable stop dan step variable step\  
        
C. Output  
    print("data ke : ",i,"=",(a))
        >> Mencetak hasil
    print("\nDone")
        >>Berfungsi untuk mencetak teks "Done" yang bertanda bahwa program sudah berakhir




## SCREENSHOOT INPUT DAN OUTPUT    


![input/output](https://github.com/dimashst777/labspy03/blob/master/folder%20gambar/latihan1.png)   



# LATIHAN 2  

    ## SOURCE CODE   

x = int()                                ## Memperkenalkan variable x sebagai integer, kemudian menginputkan nilainya
y = 0                                    ## Memperkenalkan variable y dengan nilai 0
while x >= 0:                            ## Looping WHILE apabila nilai x tidak sama dengan 0
 x = int(input("Masukkan Bilangan: "))   ## Program yang akan dilooping
 if x > y:                               ## If kondisi apabila nilai x lebih besar dari nilai y
  y = int(x)                             ## Nilai y sama dengan nilai x
 if x == 0:                              ## If kondisi apabila nilai x sama dengan 0
  break                                  ## Fungsi yang menghentikan operasi dibawahna jika suatu kondisi yang ditentukan telah tercapai
print("\nAngka Terbesar Adalah ",y)      ## Mencetak bilangan terbesar


## ALGORITMA  


A. Input   
      Print
          >> berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.
      x = int()
          >> Memperkenalkan variable x sebagai integer, kemudian menginputkan nilainya
      y = 0
          >> Memperkenalkan variable y dengan nilai 0
          
B. Process  
      while x >= 0:  							 ## "while"	: disebut uncounted loop (perulangan yang tak terhitung),
       x = int(input("Masukkan Bilangan: "))				 ## "int"	: berfungsi mengkonversi bilangan maupun string angka menjadi bilangan bulat (integer).
       if x > y: 							 ## "int"	: berfungsi mengkonversi bilangan maupun string angka menjadi bilangan bulat (integer).
       y = int(x)							 
       if x == 0:							 ## "if"	= Bila suatu kondisi tertentu tercapai maka apa yang harus dilakukan.
         break								 ## "break"	: fungsi yang menghentikan operasi dibawahnya jika suatu kondisi yang ditentukan telah tercapai.
 
C. Output  
      print("\nAngka Terbesar Adalah ",y)
          >>Untuk menampilkan Hasil dengan mencetak bilangan terbesar yaitu y



## SREENSHOOT INPUT DAN OUTPUT


![input/output](https://github.com/dimashst777/labspy03/blob/master/folder%20gambar/latihan2.png)



   

## PROGRAM 1

## SOURCE CODE  

modal = 100000000                              ## Nilai modal
laba = 0                                       ## Nilai laba 0
untung = 0                                     ## Nilai untung 0
for i in range(1,9,1):                         ## Perulangan i dengan nilai awal 1, nilai akhir 9 dan step 1
 if(i<3):                                      ## Kondisi apabila belum bulan ke-3 laba masih 0%
  laba = 0
  untung = untung + laba
 elif(i<5):                                    ## Kondisi apabila belum memasuki bulan ke-5,  Mendapat laba sebesar 1%
  laba = modal*1/100
  untung = untung + laba
 elif(i<8):                                    ## Kondisi apabila belum memasukin bulan ke-8, Mendapat laba sebesar 5%
  laba = modal*5/100
  untung = untung + laba
 else:                                         ## Pada bulan ke-8 laba menurun 2%, sehingga laba bulan ke-8 sebesar 3%
  laba = modal*2/100
  untung = untung + laba
 print("Laba Bulan Ke-",i," Sebesar ",laba)    ## Mencetak laba per bulan
print("\nTotal Laba adalah: ",untung)          ## Menghitung total laba selama 8 bulan


## ALGORITMA  

A. Input   
        modal = 100000000
        laba = 0
        untung = 0 
        
            ##"print"	  = Fungsi "print()" berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (Layar).
            ##"modal"   = adalah variable dimana 100000000 adalah modal awalnya.,
            ##"laba"    = adalah variable laba
            ##"untung"  = adalah variable untung
            
  B. Process  
      for i in range(1,9,1):
       if(i<3):
        laba = 0
        untung = untung + laba
       elif(i<5):
        laba = modal*1/100
        untung = untung + laba
       elif(i<8):
        laba = modal*5/100
        untung = untung + laba
       else:
        laba = modal*2/100
        untung = untung + laba
      
        ##"for x in range(1,9,1" = Perulangan i dengan nilai awal 1, nilai akhir 9 dan step 1
        ##"if" = Bila suatu kondisi tertentu tercapai maka apa yang harus dilakukan. Dengan fungsi ini kita bisa menjalankan suatu perintah dalam kondisi tertentu. 
        ##"elif" = adalah ketika kondisi lainnya tidak tercapai maka jalankan program.
        ##"else" = adalah ketika tidak ada suatu kondisi yang terpenuhi maka jalankan program
        ##"for"	= Perulangan yang terhitung.
        ##"range" = Mengembalikan deret integer berurut pada range yang ditentukan dari start sampai stop.
        
   C.Output  
      print("Laba Bulan Ke-",i," Sebesar ",laba)    ## Mencetak laba per bulan'
      >> Mencetak laba per bulan
    print("\nTotal Laba adalah: ",untung)
      >> Mencetak total laba    

## SCREENSHOOT INPUT DAN OUTPUT   

![input/output](https://github.com/dimashst777/labspy03/blob/master/folder%20gambar/program1.png)   



Dimas Hidayat Parluhutan Hutasuhut  
T.I.19.A.1.  
NIM:311910159  

















                                                                      





  







