| Command | Meaning | 
|---------|---------|
| smbclient //IPADDR/Folder -U username_server | Masuk ke mode _**smb: \>**_ |
| smbclient -L //IPADDR -U username_server | Lihat daftar folder yang dishare |
| smbclient //IPADDR/shared -N | Login tanpa credential |
| MODE **_smb: \>_** | | 
| get file.txt | Download file.txt |
| mget * | Download banyak file |
| del file.txt | Hapus file.txt |
