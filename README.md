# Лаборатори 6 — Тест тохиолдол боловсруулах

- **Оюутны нэр:** Б. Намуундарь
- **Оюутны код:** B232270037


## Алхам 1: PICT-ийг эх кодоос бүтээх

PICT-ийн эх кодыг лабын репоос гадна (`~/tools/pict`) clone хийж, CMake ашиглан бүтээгээд `/usr/local/bin/pict` руу суулгав.

```bash
mkdir -p ~/tools && cd ~/tools && git clone https://github.com/microsoft/pict && cd pict
cmake -S . -B build -DCMAKE_BUILD_TYPE=Release
cmake --build build -j4
sudo cp build/cli/pict /usr/local/bin/
```

**Нотолгоо:**

- Текст нотолгоо: [results/pict-build.txt](results/pict-build.txt)

  ```
  pict commit ab76c25 2026-09-08
  Pairwise Independent Combinatorial Testing

  Usage: pict model [options]
  ```

- Дэлгэцийн зураг: [Screenshot/alham1_batalgaa.png](Screenshot/alham1_batalgaa.png)