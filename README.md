<img width="906" height="716" alt="Screenshot 2026-11-09 124107" src="https://github.com/user-attachments/assets/15a5220b-3471-4221-8a18-8803f0eae6f5" />
<img width="902" height="713" alt="Screenshot 2026-11-09 124058" src="https://github.com/user-attachments/assets/69c4420a-3c34-491c-bd01-4a1d8bc31e5a" />
<img width="902" height="711" alt="Screenshot 2026-11-09 124034" src="https://github.com/user-attachments/assets/f51401c8-9300-4431-b9b9-cfc9ca20d53a" />
<img width="898" height="710" alt="Screenshot 2026-11-09 124003" src="https://github.com/user-attachments/assets/f7e731eb-a20c-4547-9327-d172a5f791f0" />
<img width="910" height="723" alt="Screenshot 2026-11-09 123754" src="https://github.com/user-attachments/assets/4927c2a5-f6a8-4e24-ad9f-e7c68b56b0fb" />
<img width="917" height="717" alt="Screenshot 2026-11-09 123659" src="https://github.com/user-attachments/assets/e3674b2f-e7ae-4ee8-b33a-fb2e47b65e46" />
<img width="902" height="708" alt="Screenshot 2026-11-09 123650" src="https://github.com/user-attachments/assets/6ea5e0f7-b547-4836-a281-abbf434e2a88" />
<img width="922" height="713" alt="Screenshot 2026-11-09 123625" src="https://github.com/user-attachments/assets/c2ebc9b5-d097-4071-9583-12c5b5393fc1" />
<img width="913" height="725" alt="Screenshot 2026-11-09 123609" src="https://github.com/user-attachments/assets/aec678b8-b2d5-4b5c-a9ea-91049e4986d6" />
ProdukApp - JavaFX

Aplikasi desktop sederhana untuk manajemen data produk toko pakai JavaFX (MVC).

Fitur
1. Tabel daftar produk (`TableView`)
2. Pencarian nama produk
3. Tambah, Edit, dan Hapus data produk (pilihan kategori Makanan/Minuman)
4. Auto-generate kode produk (`PRD001`, `PRD002`, dst.)

Tech Stack
1. Java 17+
2. JavaFX 21
3. Maven

Cara Run (NetBeans)
1. Open project `ProdukApp` di NetBeans.
2. Clean & Build (`Shift + F11`).
3. Run project (`F6`).

Lewat Terminal / Command Prompt
```bash
mvn clean compile
mvn exec:java -Dexec.mainClass="toko.MainApp"
