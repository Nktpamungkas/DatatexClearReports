Documentation for setting i-net Crystal Reports

1. Instal Java jdk-11.0.1
  a. Copy folder jdk-11.0.1 > **Paste** folder tersebut ke C:\Program Files\Java
  b. Pada Windows lakukan pencarian "**environment**" > klik "Environment Variables..."
  c. Pada Group "System variables" cari "PATH" > lalu NEW dan pastekan alamat berikut "C:\Program Files\Java\jdk-11.0.1" (tanpa tanda kutip)
  d. Untuk memeriksa bahwa komputer sudah terinstal JAVA Version 11.0.1
    - Buka CMD
    - Ketikkan perintah "Java -version"
    - Jika berhasil maka muncul tulisan "openjdk version "11.0.1" 2018-10-16...................
2. Download Folder "Datatex Clear Reports"
3. Paste folder tersebut ke C:\Program Files
4. Buka file "startDesigner.bat" didalam folder "Datatex Clear Reports"
5. jika sudah terbuka, klik **option** > **Data Sources...** >
   a. pada tab user anda silahkan klik "add"
   b. pilih "user-definded driver" > ok
   c. masukan settingan dibawah ini :
     - Data Source Name : NOWPRD
     - JDBC driver : com.ibm.db2.jcc.DB2Driver
     - library : http:\\10.0.0.22\jboss-eap-7.4\modules\system\layers\base\com\ibm\db2\main\db2jcc4.jar http:\\10.0.0.22\jboss-eap-7.4\modules\system\layers\base\com\ibm\db2\main\db2jcc_license_cu.jar
     - JDBC Driver URL : jdbc:db2://10.0.0.21:25000/NOWPRD
     - User : db2admin
     - Password : <<Jika sudah sampai step ini silahkan bertanya di group Programmer ITTI>>
6. selesai

***Note ** : Jika ada yang ingin ditanyakan silahkan tanya langsung saja.

Terima kasih
