Documentation for setting i-net Crystal Reports

PERTAMA-TAMA YANG HARUS DILAKUKAN ADALAH COPY FOLDER **"Datatex Clear Reports"** & **"jdk-11.0.1"** KE FOLDER DATA D MASING-MASING.

INSTAL JAVA 11.0.1
1. Instal Java jdk-11.0.1
2. Copy folder jdk-11.0.1 > **Paste** folder tersebut ke C:\Program Files\Java
3. Klik Windows lakukan pencarian "**environment**" > klik "Environment Variables..."
4. Pada Group "System variables" cari "PATH" > lalu NEW dan pastekan alamat berikut "C:\Program Files\Java\jdk-11.0.1" (tanpa tanda kutip)
5. Untuk memeriksa bahwa komputer sudah terinstal JAVA Version 11.0.1
    - Buka CMD
    - Ketikkan perintah "Java -version"
    - Jika berhasil maka muncul tulisan "openjdk version "11.0.1" 2018-10-16...................

INSTAL I-NET CRYSTAL REPORTS
1. Download Folder "Datatex Clear Reports"
2. Paste folder tersebut ke C:\Program Files
3. Buka file "startDesigner.bat" didalam folder "Datatex Clear Reports"
4. Jika sudah terbuka, klik **option** > **Data Sources...** >
5. Pada tab user anda silahkan klik "add"
6. Pilih "user-definded driver" > ok
7. Masukan settingan dibawah ini :
     - Data Source Name : NOWPRD
     - JDBC driver : com.ibm.db2.jcc.DB2Driver
     - library : http:\\10.0.0.22\jboss-eap-7.4\modules\system\layers\base\com\ibm\db2\main\db2jcc4.jar http:\\10.0.0.22\jboss-eap-7.4\modules\system\layers\base\com\ibm\db2\main\db2jcc_license_cu.jar
     - JDBC Driver URL : jdbc:db2://10.0.0.21:25000/NOWPRD
     - User : db2admin
     - Password : <<Jika sudah sampai step ini silahkan bertanya di group Programmer ITTI>>
8. Selesai

***Note ** : Jika ada yang ingin ditanyakan silahkan tanya langsung saja.

Terima kasih
