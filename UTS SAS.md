# UTS-Sistem Administrasi Server
------
## Budhi Priambodo 1202192065    IT0201
------
Pada kesempatan kali ini terdapat soal, yang menginstruksikan untuk melakukan instalasi windows server 2022 pada virtual machine.
------
<img width="461" alt="bbbb" src="https://user-images.githubusercontent.com/92350603/143621126-49a7a818-0d3d-4a3f-b737-ff4fafdae37f.PNG">
------

1. Download ISO Installer windows server 2022

   https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022
   
   Select download the ISO then follow it step by step.
<img width="874" alt="cccc" src="https://user-images.githubusercontent.com/92350603/143621513-6da949ad-311d-4c4b-af20-f8dc3031a9e4.PNG">

```markdown
2.	Langkah Langkah instalasi :
```

```markdown
-	Open VirtualBox and go to the “machine – New” Menu


```
![1](https://user-images.githubusercontent.com/61863147/143667927-70ca21ad-d42b-491a-bcba-ac3b6a89f9c8.PNG)


```markdown
- Enter the name of the machine and type of system to use
```
![2](https://user-images.githubusercontent.com/61863147/143667956-203ab460-0cbe-41ce-816b-66798d09775d.PNG)

```markdown
- Define ram, create the disk defining type and size
```
![3](https://user-images.githubusercontent.com/61863147/143667986-d19de223-5e3f-44e7-b0a2-1a914a2bd09c.PNG)
![4](https://user-images.githubusercontent.com/61863147/143667988-f0ad987a-5779-4833-a4c6-ff41bc312a76.PNG)
![5](https://user-images.githubusercontent.com/61863147/143667992-f8b901a4-18bf-4184-a34c-d05524731edf.PNG)
![6](https://user-images.githubusercontent.com/61863147/143667993-e6dbf021-837c-4135-ab85-8ca17a3024a6.PNG)
![7](https://user-images.githubusercontent.com/61863147/143667996-51de2c63-852c-46e3-ba3d-72f6cc43addc.PNG)

```markdown
- Go to the machine configuration and in the “Network” section set “Bridge adapter”
```
![14](https://user-images.githubusercontent.com/61863147/143668019-09ad530a-4fb8-4271-9c6c-7a7c1b6ea685.PNG)

```markdown
- Setting Storage ISO
```
![9](https://user-images.githubusercontent.com/61863147/143668097-2190f266-2e24-46f1-b4c9-4d664d9063c0.PNG)
![10](https://user-images.githubusercontent.com/61863147/143668098-68445f93-4306-4955-927b-22fa4b612329.PNG)
![11](https://user-images.githubusercontent.com/61863147/143668099-3c25b985-925b-4ba4-acfa-d855bd63cbf4.PNG)
![12](https://user-images.githubusercontent.com/61863147/143668105-9157c189-f7d2-4a2b-ab19-78e1b121de89.PNG)
![13](https://user-images.githubusercontent.com/61863147/143668107-ed5019c3-3ff6-4b4b-b854-e35957f69ba2.PNG)

```markdown
- Click on “Start” and the Windows Server 2022 installation wizard will load
```
![16](https://user-images.githubusercontent.com/61863147/143668124-8daac09f-6509-494c-8965-e900197850e1.PNG)



```markdown
- Click on “Install now”
```
![17](https://user-images.githubusercontent.com/61863147/143668128-c890729c-7bb9-4cc9-8ea6-7179ff803a88.PNG)

```markdown
- Enter the license (if you have on) and then define the edition to use, Accept the license and then proceed with the installation of Windows Server 2022
```
![18](https://user-images.githubusercontent.com/61863147/143668135-a214004c-d7d2-496a-88b8-6611c2b6a611.PNG)
![19](https://user-images.githubusercontent.com/61863147/143668137-d08d79ed-4dbb-4215-8e90-abb6fa31bcd1.PNG)
![20](https://user-images.githubusercontent.com/61863147/143668139-99afef71-2a2e-4eb8-9dcc-85cec5476b9e.PNG)
![21](https://user-images.githubusercontent.com/61863147/143668140-bd7b2a8e-46e8-41d0-9092-aac50bae9b18.PNG)
![22](https://user-images.githubusercontent.com/61863147/143668185-6664f222-af69-47bf-9719-531606b2030d.PNG)


```markdown
- Access the menu “Input – Keyboard – Insert Ctrl + Alt + Del”. Enter the password created and wait for the configuration to load
```
![23](https://user-images.githubusercontent.com/61863147/143668194-734a88ea-4b27-4e78-bb97-44a965f42b26.PNG)
![24](https://user-images.githubusercontent.com/61863147/143668199-72115b09-8583-4c8f-b093-1abd89bd9cf5.PNG)

```markdown
A. Instalasi Active Directory Domain Services

```markdown
- Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next”.
```
![b26](https://user-images.githubusercontent.com/61863147/143668245-08406686-0298-4996-b5fd-19a165a6d1ec.PNG)

```markdown
- Pilih opsi “Role-based or feature-based installation”. Lalu “Next”
```

![b27](https://user-images.githubusercontent.com/61863147/143668267-5644a268-d267-4ab3-9a6f-2e5ce79ec8e1.PNG)


```markdown
- Klik “Select a server from the server pool” untuk memilih direktori penyimpanan lokal. Lalu “Next”
```

![b28](https://user-images.githubusercontent.com/61863147/143668272-de449656-4af6-4cb8-85e2-ab84ca545451.PNG)


```markdown
- Selanjutnya, berikan tanda centang di kotak “Active Directory Domain Services”. Saat anda mencentang kotak, disebelah kanan muncul penjelasan singkat tentang ADDS dan cara kerjanya. Lalu klik “Add Features”.
```
![b29](https://user-images.githubusercontent.com/61863147/143668292-f815ed2a-1eac-46fa-89e6-0dc5f7667f01.PNG)

```markdown
- Kemudian centang kotak “Group Policy Management” dan tekan tombol “Next”.
```
![b31](https://user-images.githubusercontent.com/61863147/143668373-0a5fb82f-d923-406e-a8f2-c6d4637f7dc3.PNG)

```markdown
- Selanjunya klik “Next” lagi.
```
![b32](https://user-images.githubusercontent.com/61863147/143668389-20ea5bb3-f9d0-43ba-a0c9-2645a08a53bd.PNG)

![b33](https://user-images.githubusercontent.com/61863147/143668393-8b69b724-6378-4a04-8db5-875230e087ec.PNG)

```markdown
- Klik “Install”.
```

![b34](https://user-images.githubusercontent.com/61863147/143668396-3019f5ed-eb36-4689-9c3a-5de15db26692.PNG)


```markdown
- Tunggu hingga proses instalasi selesai kemudian melakukan konfigurasi ADDS
```

![b35](https://user-images.githubusercontent.com/61863147/143668426-162eca70-2c07-412a-8b09-2a4af6e21e53.PNG)



```markdown
B. Instalasi DNS server
```

```markdown
- Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next”. Stepnya sama seperti instalasi active directory. Kita perlu menginstal dan mengonfigurasi peran Active Directory dan server DNS untuk bekerja bersama. 
```
![b30](https://user-images.githubusercontent.com/61863147/143668501-93feebcc-97e3-456d-afee-dd5f974cf80a.PNG)


```markdown
C. Instalasi Net Framework 3.5
```

```markdown
- Centang “.NET Framework 3.5 features”
```
![b31](https://user-images.githubusercontent.com/61863147/143668506-8a27483f-eca7-4bbe-a1cc-a35e4eac7cbb.PNG)

```markdown
- Selanjunya klik “Next” lagi.
```
![b32](https://user-images.githubusercontent.com/61863147/143668523-39e2f7c4-876c-4bdd-a990-fc241ccb7133.PNG)

```markdown
- Selanjutnya klik “Install”.
```
![b34](https://user-images.githubusercontent.com/61863147/143668529-aea144cb-2d05-45e0-9bdd-502697aeaae9.PNG)


```markdown
- Tunggu hingga proses instalasi selesai
```
![b36](https://user-images.githubusercontent.com/61863147/143668563-1f11d208-344b-43c6-bbe9-30ab46f708e5.PNG)


```markdown
**Promote Server to a Domain Controller**
```

```markdown
- Seting ke ip static menggunakan cmd, ketik sconfig
```
![e1](https://user-images.githubusercontent.com/61863147/143681927-5dea2976-5614-40f5-aaff-95241be6d31e.PNG)
![e2](https://user-images.githubusercontent.com/61863147/143681931-10c1d2ba-386a-45f6-a4cf-4988b5548858.PNG)
![e3](https://user-images.githubusercontent.com/61863147/143681934-e69c90e1-ee67-4b34-b26d-f411d929e1d2.PNG)


```markdown
- Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan.
```
![e4](https://user-images.githubusercontent.com/61863147/143681962-5e47590d-c084-40c3-b715-11469babd3bf.PNG)

```markdown
- Pilih “Add a new forest” dan masukkan nama domain yang akan digunakan pada Root Domain Name. Misalnya disini saya menggunakan domain “Budhi.com”
```
![e5](https://user-images.githubusercontent.com/61863147/143681991-bd38a60b-b943-4ca6-968d-5bbf7c26fe6b.PNG)

```markdown
- Pilih “Windows Server 2016” pada functional level, beri tanda centang pada “Domain Name System (DNS) server” dan ”Global Catalog (GC)”. Serta mengisi password Directory Services Restore Mode dengan kriteria strong password.
```
![e6](https://user-images.githubusercontent.com/61863147/143681998-f78546dc-4fcf-4a64-bf56-0e31fb5753cd.PNG)

```markdown
- Lewati bagian DNS Options, lalu klik “Next”.
```
![e7](https://user-images.githubusercontent.com/61863147/143682011-3b3073ee-eb7b-46a8-8d30-5432f149d4e4.PNG)

```markdown
- Mengisi “The NetBIOS domain name” sesuai dengan nama domain yang digunakan.
```
![e8](https://user-images.githubusercontent.com/61863147/143682022-d79fd5ff-f108-4e14-8fd0-abe526bada0b.PNG)

```markdown
- Lewati bagian Paths, klik “Next”.
```
![e9](https://user-images.githubusercontent.com/61863147/143682035-f4f1bedf-0c63-4ef4-84db-b1644e82581f.PNG)

```markdown
- Cek konfigurasi yang ditentukan pada Review Options, jika suda ok. Klik “Next”.
```
![e10](https://user-images.githubusercontent.com/61863147/143682042-b891a99f-54a8-4141-bf5c-8612a52fbfdb.PNG)

```markdown
- Jika sudah ada tulisan All prerequisite checks passed successfully. Klik “Install” untuk apply konfigurasi yang sudah ditentukan.
```
![e11](https://user-images.githubusercontent.com/61863147/143682047-68050723-0631-4140-8b79-5fe6dbcd52fe.PNG)

```markdown
- Tunggu hingga proses instalasi selesai.
```
![e12](https://user-images.githubusercontent.com/61863147/143682068-3b84f875-c52e-402b-bb57-2a5c3263e8eb.PNG)

```markdown
- Setelah selesai menginstal, maka laptop akan ke restart otomatis. Kemudian login menggunakan password administrator
```
![e13](https://user-images.githubusercontent.com/61863147/143682075-5780a553-ef69-481c-93b3-535dd9f5b314.PNG)

```markdown
- Untuk mengecek hasil konfigurasi, buka cmd dan ketikkan “netdom query fsmo”

```markdown
- Setelah login dengan Active Directory Domain Controller, buka properti TCP/IP koneksi jaringan Anda. Anda dapat melihat Alamat IP server DNS yang disukai
```
![e14](https://user-images.githubusercontent.com/61863147/143682121-1965533a-392b-4699-93b4-e3da7a34f9f7.PNG)

```markdown
FINISH YEAY !!
```
