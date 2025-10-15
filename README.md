# bora.github.io

Bu repository basit bir statik site içerir.

Dosyalar:
- `index.html` — Anasayfa
- `proje.h` — Boş olan başlık dosyası örnek bir include guard ve helper ile güncellendi

Yerelde çalıştırma (kolay yöntemler):

1) Python 3 kullanarak hızlı bir HTTP sunucusu başlatın:

```bash
cd /Users/boraakin/Documents/GitHub/bora.github.io
python3 -m http.server 8000
```

Sonra tarayıcıdan `http://localhost:8000` adresini açın.

2) macOS üzerinde `open` komutuyla doğrudan açabilirsiniz:

```bash
open http://localhost:8000
```

Değişiklik: `proje.h` içine basit bir fonksiyon eklendi (`proje_topla`).
