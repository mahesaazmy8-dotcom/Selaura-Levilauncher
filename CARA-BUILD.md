# Selaura → LeviLauncher

File ini adalah source Selaura Client yang sudah disiapkan untuk membuat mod Windows x64.

## Cara paling mudah

1. Buat repository baru di GitHub.
2. Upload semua isi folder ini ke repository tersebut.
3. Buka tab **Actions**.
4. Pilih **Build Selaura for LeviLauncher**.
5. Tekan **Run workflow**.
6. Setelah selesai, buka hasil run tersebut dan download artifact:
   **Selaura-LeviLauncher**
7. Di dalamnya ada `Selaura-LeviLauncher.zip`.
8. Import file ZIP tersebut ke LeviLauncher.

LeviLauncher membutuhkan mod native yang sesuai dengan versi Minecraft yang digunakan. Jangan dipasang pada versi Minecraft yang tidak kompatibel.

## Catatan
Build dilakukan di Windows melalui GitHub Actions karena source ini membutuhkan compiler/dependency Windows untuk menghasilkan DLL.
