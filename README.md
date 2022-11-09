<p style="font-size:14px" align="right">
<a href="https://t.me/PemulungAirdropID" target="_blank">Join our telegram <img src="https://user-images.githubusercontent.com/72949170/194228482-0f875615-e155-4b12-8716-8111addd6cba.jpg" width="30"/></a>
</p>

<p align="center">
  <img width="60%" height="auto" src="https://user-images.githubusercontent.com/72949170/200721952-cd40b64b-70e8-42b8-bc60-c289891e49cb.png">
</p>

# EXORDE LABS TESTNET

|  Komponen |  Persyaratan Minimum |
| ------------ | ------------ |
| CPU  | Intel Core i3 or i5  |
| RAM | 4 GB DDR4 |
| Penyimpanan  | 500 GB HDD |
| Koneksi | 100 Mbit/s |

Twitter :
> https://twitter.com/ExordeLabs

Discord :
> https://discord.com/invite/exordelabs

## 1. Install bahan (Kalau udah, skip aja)

- Install Docker 
```
rm /usr/bin/docker-compose /usr/local/bin/docker-compose
curl -fsSL https://get.docker.com -o get-docker.sh && sh get-docker.sh
systemctl restart docker
curl -SL https://github.com/docker/compose/releases/download/v2.5.0/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
docker --version
```

- Install Screen
```
sudo apt install -y build-essential libssl-dev libffi-dev git curl screen
```

## 2. Install Node

- Clone Git
```
git clone https://github.com/exorde-labs/ExordeModuleCLI.git
```

![image](https://user-images.githubusercontent.com/72949170/200723559-9152e055-c0f8-43e9-96b9-db051156c7b0.png)


- Install Node
```
cd ExordeModuleCLI
```
```
docker build -t exorde-cli . 
```

![image](https://user-images.githubusercontent.com/72949170/200723730-9acdb6e0-4bb5-487b-8f9e-2bbe1d3f0a2c.png)


![image](https://user-images.githubusercontent.com/72949170/200723783-55d1293d-c372-4b0d-9421-ff731e1aaffb.png)

## 3. Jalankan Node

```
screen -S exorde
```
```
docker run -it exorde-cli -m AddressKalian(0x) -l (pilih 1-4)
```
> Contoh
> docker run -it exorde-cli -m 0x0000000000000000000000000000000000 -l 4

``Saran pilih 4 karena lebih lengkap``

|  Logging Level |  Detail |
| ------------ | ------------ |
| 0  | Tidak ada log  |
| 1  | Log biasa  |
| 2 | Log validasi |
| 3  | Log validasi dan scrapping |
| 4 | Log validasi (detail) + log scrapping (untuk troubleshoot) |


![image](https://user-images.githubusercontent.com/72949170/200724698-db1a4a7d-5aa3-4e03-b036-043e479d3804.png)

Kalian bisa close screen ```CTRL A + D``` atau langsung tutup tab 

Untuk melihat log kalian bisa command ```screen -Rd exorde```

## 4. DONE, UNTUK UPDATE SELANJUTNYA KALIAN BISA PANTAU <a href="https://t.me/PemulungAirdropID" target="_blank">CHANNEL KITA </a>
</p>
