Media penyimpanan yang bersifat persisten

```bash
docker volume --help
````

Tampilkan bantuan

```
docker volume create <nama_volume>
```

Membuat volume baru untuk penyimpanan data yang persisten

```
docker volume ls
```

Menampilkan daftar volume yang ada di komputer lokal

```
docker volume inspect <nama_volume>
```

Menampilkan informasi detail mengenai volume tertentu

```
docker run -d --name <nama_container> -v <nama_volume>:<path_di_container> <nama_image>
```

Menjalankan kontainer sekaligus melakukan mounting volume ke dalam folder tertentu di kontainer

Bash

```
docker volume rm <nama_volume>
```

Menghapus volume yang sudah tidak digunakan