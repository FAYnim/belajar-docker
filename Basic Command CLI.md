```bash
docker run -d --name <nama-server> <image. e.g. nginx>
```
Menjalankan docker Nginx secara *detach* agar bisa dijalankan di background

```bash
docker ps -a
```
Untuk melihat container yang sedang berjalan

```bash
# lihat semua bantuan
docker --help

# lihat bantuan run
docker run --help

# lihat bantuan container
docker container --help
```
Melihat bantuan

```bash
docker container start <nama_container>
#atau
docker start <id_container>
```
Menjalankan container

```bash
docker stop <id_container>
```
Mematikan container

```bash
docker inspect <nama_container>
```
Melihat detail container
```bash
docker logs <nama_container>
```
Melihat logs container

```bash
docker exec <nama_container> <nama_perintah>
# contoh
docker exec web-server-1 hostname
```
Menjalankan command di dalam container

```bash
docker exec -it <nama_container> bash
```
Menjalankan command di dalam container seperti remote ssh