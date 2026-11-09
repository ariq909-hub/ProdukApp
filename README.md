<img width="913" height="725" alt="Screenshot 2026-11-09 123609" src="https://github.com/user-attachments/assets/110ce9c9-f8ce-447a-a1d0-0eafb8b31c62" />
<img width="922" height="713" alt="Screenshot 2026-11-09 123625" src="https://github.com/user-attachments/assets/f294f0de-aa91-49b6-bd8c-dcdb7720a20a" />
<img width="917" height="717" alt="Screenshot 2026-11-09 123659" src="https://github.com/user-attachments/assets/a2508646-ca8e-4da3-8c70-43b9bbc38c90" />
<img width="902" height="708" alt="Screenshot 2026-11-09 123650" src="https://github.com/user-attachments/assets/0751db6e-8784-4cb2-844e-20fc564da0fa" />
<img width="910" height="723" alt="Screenshot 2026-11-09 123754" src="https://github.com/user-attachments/assets/c9aae89b-186e-4279-af1d-a240516c2a50" />
<img width="898" height="710" alt="Screenshot 2026-11-09 124003" src="https://github.com/user-attachments/assets/294634dc-bcc7-4cfc-8ef5-f180ff6ef1f7" />
<img width="902" height="711" alt="Screenshot 2026-11-09 124034" src="https://github.com/user-attachments/assets/9c5d6a51-a7a3-4453-a723-64d656e36fda" />
<img width="902" height="713" alt="Screenshot 2026-11-09 124058" src="https://github.com/user-attachments/assets/2f41823e-fac6-4ab8-86e2-5949cb0b91f8" />
<img width="906" height="716" alt="Screenshot 2026-11-09 124107" src="https://github.com/user-attachments/assets/d7fcd81a-1628-40f1-8b8c-c2e5d0263dae" />

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
