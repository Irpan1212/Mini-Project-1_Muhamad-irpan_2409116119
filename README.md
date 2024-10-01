# Mini-Project-1_Muhamad-irpan_2409116119
![flowchart_Muhamad Irpan_2409116119-Copy of Muhamad Irpan_2409116119](https://github.com/user-attachments/assets/bd2a81d7-eafe-487e-acb6-fd82b4f5870a)
_____________________________________________________________________________________________________________________________________________________
![Screenshot 2024-10-01 014458](https://github.com/user-attachments/assets/baac5f10-a3b8-43a1-a0b5-66fb1a7f9dff)
[Uploading DASPRO_Muhamad Irpan

while True:

    print("___________________________________")
    print("GAJI KARYAWAN")
    print("___________________________________")
    Nama =(input("Nama                   :"    ))
    Jam = int(input("jumlah jam kerja    :"))
    tarif = int(input("Tarif Kerja       :"))
    print("___________________________________")
    gaji = tarif
    bonus = gaji * 0.10 
    if Jam >= 160:
        print(int(gaji+bonus))
        print("total gaji kamu diatas")
        print("------------------------")
        print("kamu bekerja lebih dari 160 jam")
        print("Yeee,kamu dapat bonus,SEMANGAT TERUS YAA!")
    elif Jam < 160:
        print(gaji)
        print("total gaji kamu diatas")
        print("------------------------")
        print("jam kerja kamu sesuai")
        print("Terima kasih,SEMANGAT TERUS YAA!")
        print("------------------------")
    ulangi_pesanan = str(input("kurang puas,mau coba cek lagi?(ya/tidak) ")).lower()
    if ulangi_pesanan != "ya":           
        print("SELESAI^-^")
        break

**pejelesan :**
 
* untuk paling atas itu ada **While True** dimana itu berguna sebagai pengulangan
* lalu saya lanjut memasukkan inputnya dimana ada **input nama,jumlah jam kerja, tarif kekrja** dan disini juga terlihat kode **int** dimana ini berguna untuk mengubah arti menjadi angka
* lalu untuk gaji disini itu, **GAJI=TARIF** dan untuk bonus itu B**ONUS*0.10 ini berarti 10%**
* lanjut saya memeasukkan** if** yang dimana jika gaji melebihi jam kerja maka menedapatkan bonus** "total gaji=bonus)**,saya memakai kode int dimana itu berguna mengubah angka desimal dari perkalian 0.10 itu menjadi bilangan pecahan
* disini juga saya menambahkan semacan keterangan jika melebihi jam kerja akan ada pesan tertentu
* lanjut disini saya ada **elif** yang dimana ini berguna jika jam kerjnya tidak melebihi 160jam maka masuk dipilihan kedua yaitu tidak dapat bonus **"print(gaji)"**
* disini juga saya menambahkan semacan keterangan jika melebihi jam kerja akan ada pesan tertentu
* ini ada** ulang_pesanan **= disini berguna untuk pilihan apakah mau ulang atau tidak, ada juga kode** str**,itu berguna mmembuat outputnya menjadi huruf, diakhir itujuga ada lower yang berguna untuk mengecilkan huruf besar
* nah disini ada** if** untuk pilihan yang dipilih jika dia memilih ya maka ulang kemenu awal dan jika memlih tidak maka selesai 
* disini ada **break** yang berguna sebagai penyelesain jika memilih tidak
            
 _2409116119.py…]()

