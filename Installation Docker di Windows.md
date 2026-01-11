1. Pergi ke https://www.docker.com/get-started/
2. Download sesuai OS
3. Install Docker

## Troubleshoot
### WSL Update
1. Buka terminal/CMD dan jalankan
```bash
wsl --update
```

### Virtualization not enable
1. Buka `Task Manager` dan klik tab Performance
2. Cek `Virtualization` di CPU
3. Jika belum enable, buka terminal/CMD as Administrator
4. Ketik `shutdown -r -fw -t 0` untuk masuk BIOS
5. Setelah masuk BIOS, cari tab `CPU Config` atau semacamnya
6. Atur `Virtualization` ke *enable*
7. `Esc` dan simpan pengaturan BIOS
8. Nyalakan Docker
