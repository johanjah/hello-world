# java-copy-file
Menyalin file (copy) dari sumber folder ke tujuan folder tertentu.
1. hanya menyalin file (folder tidak disertakan).
2. jika ada folder di dalam folder sumber. file yang di dalam folder tersebut akan di salin juga. (looping membaca folder).
3. jika file sudah ada (exist) di tujuan. maka akan menghasilkan (x), dimana x >=1. misal filename.exe, jika sudah ada maka akan menjadi filename (1).exe (dst)
