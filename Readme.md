
# Workflow With Git & Github

Penjelasan tentang alur kerja saat proses development aplikasi

- Clone project sesuai arahan di github
- Buat branch baru sesuai tugas yang di assign
- Pindah ke branch yang baru saja dibuat 
- Jika sudah selesai mengerjakan silahkan di commit (disimpan)
- Lalu push (upload) kode ke github
- Lakukan pull request di github

## Git Commands 
Membuat branch baru
```bash
  git branch <nama-branch>
```
Pindah ke branch yang diinginkan
```bash
  git switch <nama-branch> 
 ```

Memindah perubahan ke staging area
```bash
  git add .
 ```

Commit / simpan hasil kerja 
```bash
  git commit -m "pesan commit"
 ```

Push / upload hasil kerja ke github
```bash
  git push -u origin <nama-branch>
 ```
## Konvensi penamaan branch
Branch untuk fitur baru
```bash
  feat/<nama-feature>
  contoh : git branch feat/home || git branch <feat/autentikasi-user>
```

Branch untuk memperbaiki bug
```bash
  fix/<nama-feature>
  contoh : git branch fix/home || git branch <fix/autentikasi-user>
```

## Konvensi pesan commit
Contoh pesan commit
```bash
  (<nama branch>): pesan commit
  contoh : git commit -m "(feat/home):menambah input search pengumuman"
```
