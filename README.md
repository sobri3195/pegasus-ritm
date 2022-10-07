# Pegasus-RITM
This is a Python implementation of the man-in-the-middle attack described by Letda Kes dr. Muhammad Sobri Maulana, S.Kom, CEH, OSCP, OSCE

In short, this tool:
1. Melakukan teknik Spoofing ARP antara target dan pembatasan gateway di antara batas
2. Melakukan teknik sniffing
3. Menjalankan sniffing dengan cara masuk ke sistem yang ada sehingga dapat mengatasi apa yang ada di dalam keamanan
4. Hasilnya setelah itu bisa menyebabkan virus trojan masuk ke dalam sistem jaringan munggunakan ARP

## Install
Dahulukan dengan penginstalan 'pip3 install .' dengan path `ritm` or `roastinthemiddle`

## Development
pegasus-ritm menggunakan RichHandler untuk bisa mengembangkan getLogger dengan set Level dan setFormatter.

```bash
git clone https://github.com/sobri3195/pegasus-ritm
cd ritm
poetry install
poetry run ritm --help
```

## Contributors
- Muhammad Sobri Maulana

