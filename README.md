# Fix TTL pada OpenWrt

Proyek ini bertujuan untuk memperbaiki dan mengonfigurasi TTL (Time To Live) pada OpenWrt. Dengan menggunakan skrip `indowrt.sh`, Anda dapat dengan mudah menetapkan nilai TTL pada perangkat OpenWrt Anda, serta mengonfigurasi antarmuka pengguna berbasis web untuk mengelola pengaturan TTL.

## Fitur

- **Fix TTL**: Menetapkan nilai TTL pada OpenWrt menggunakan `nftables`.
- **Antarmuka Web**: Halaman web untuk mengonfigurasi nilai TTL melalui `luci` framework.
- **Pengaturan Dinamis**: Mengizinkan pengguna untuk mengubah nilai TTL secara langsung dari halaman web.

## Instalasi

### 1. Persiapkan Perangkat OpenWrt Anda

Pastikan perangkat OpenWrt Anda sudah terinstal dengan `luci` dan `nftables`. Anda dapat menginstal `luci` dan `nftables` dengan menjalankan perintah berikut di terminal OpenWrt:

```sh
opkg update
opkg install luci nftables
