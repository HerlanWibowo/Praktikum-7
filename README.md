### Membuat Program daftar Nilai Mahasiswa dan Flowchartnya
### Ini Flowchartnya
![Flowchart](/flowchart.png)

### Begini Tutorialnya

Buat Variabel Global untuk menyimpan data Mahasiswa dan buat fungsi tambah

data = {}

def tambah():
    print("Tambah Data")
    nama = input("Nama\t\t: ")
    nim = int(input("NIM\t\t: "))
    tugas = int(input("NIlai Tugas\t: "))
    uts = int(input("Nilai UTS\t: "))
    uas = int(input("Nilai UAS\t: "))
    nilaiakhir = (tugas * 0.3 + uts * 0.35 + uas * 0.35)
    data[nama] = nim, tugas, uts, uas, nilaiakhir