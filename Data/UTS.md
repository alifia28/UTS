1202190021_ALIFIA KHAIRUNNISA_IT 02-02

 ### Ujian Tengan Semester Sistem Administrasi Server 
Download ISO Installer Windows Server 2022
      Kwmudian klik link : 
    https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022
    ```

     
![A1](SAS/p1.png)
        
    Atur memory dengan size 2048 MB kemudian next 
![A1]SAS/p2.jpg)

    Buat virtual machine pada hard disk kemudian next 
![A1](SAS/p3.png)

    Buat  Hard disk file type kemudian next
![A1](SAS/p4.png)

    Selanjutnya buat stroge on physical hard disk dan next saja 
![A1](SAS/p5.png)

    Buat File Location and size kemudian next 
![A1](SAS/p6.png)

    Masuk ke > Setting > Network dan ubah Nat menjandi Bridge Adapter lalu ok 
![A1](SAS/p7.png)

    Klik Start kemudia masukan file yang sudah di download tadi 
![A1](SAS/p8.png)

    Kemudian klik next dan install now
![A1](SAS/p9.png)
![A1](SAS/p27.png)

    Pilih Windows Server 2022 Standart (desktop) dan next
![A1](SAS/p10.png)

    Centang dan next kemudian 
    Pilih custome : install Microsoft Server Operating System Only (advanced)
![A1](SAS/p11.png)
![A1](SAS/p12.png)

    Klik next dan tunggu proses installasi hingga selesai 
![A1](SAS/p13.png)
![A1](SAS/p14.png)

    Setelah proses installasi selesai maka sistem akan reboot ke cpmplate proses
![A1](SAS/p15.png)

    Enter dan buat password baru pada customize setting 
![A1](SAS/p16.png)

    Setelah selesai buat password, akses menu input > keyboard > Insert Ctrl + Alt + Del , kemudian enter masukkan password yang sudah dibuat 
![A1](SAS/p17.png)
![A1](SAS/p18.png)

    Kemudian kembali ke menu Device > Insert Guest Additions Cd Image >  cd Drive Virtual box > pilih VBox WindiwsAdditions
![A1](SAS/p19.png)
![A1](SAS/p20.png)
![A1](SAS/p21.png)

    Lalu klik install 
![A1](SAS/p22.png)
![A1](SAS/p23.png)

    Reboot machine dan akses menu input – keyboard – Insert Ctrl + Alt + Del , kemudian enter masukkan password kembali 
![A1](SAS/p24.png)

    Jalankan winver untuk memvalidasi mesin 
![A1](SAS/p25.png)

    Windows Server 2022 terinstall 
![A1](SAS/p26.png)

###  INSTALLASI ACTIVE DIRECTORY DOMAIN SERVER 

    Ubah nama di windows powershell  dengan ketik > “rename -computer -Newname Server 2022” 
![A1](SAS/p28.png)

    Kemudian masuk pada server manager pilih menu Manage > Add roles features dan next 
![A1](SAS/p29.png)

    Kemudian pilih Role-Based  or feature-based installation dan next 
![A1](SAS/p30.png)

    Pilih select a server from the server pool , setelah itu pilih active directory domain server 
![A1](SAS/p31.png)

    Setelah itu klik add features 
![A1](SAS/p32.png)

    Masuk pada features kemudian centang Group Policy Management dan next 
![A1](SAS/p33.png)

    Kemudian masuk pada confirm installation selection dan install 
![A1](SAS/p34.png)
![A1](SAS/p35.png)
![A1](SAS/p36.png)
![A1](SAS/p37.png)
![A1](SAS/p38.png)
![A1](SAS/p39.png)
![A1](SAS/p40.png)
![A1](SAS/p41.png)
![A1](SAS/p42.png)
![A1](SAS/p43.png)
![A1](SAS/p44.png)
![A1](SAS/p45.png)
![A1](SAS/p46.png)
![A1](SAS/p47.png)
![A1](SAS/p48.png)
![A1](SAS/p49.png)
![A1](SAS/p50.png)
![A1](SAS/p51.png)
![A1](SAS/p52.png)
![A1](SAS/p53.png)
![A1](SAS/p54.png)
![A1](SAS/p55.png)
![A1](SAS/p56.png)
![A1](SAS/p57.png)
![A1](SAS/p58.png)


    Maaf pak masih ada yag error