#include <stdio.h>
#include <string.h>

int main() {
    // Jika dosa dan kesalahan disimpan dalam sebuah variabel array,
    char dosa[][20] = {
        "kesalahan",
        "iri",
        "cemburu",
        "benci",
        "penistaan",
        "penghinaan",
        "amarah",
        "kebohongan"
        // Tambahkan dosa lainnya di sini
    };

    int jumlah_dosa = sizeof(dosa) / sizeof(dosa[0]);

    // Jika dosa-dosa tersebut disimpan dalam sebuah array, pada hari yang suci ini mari kita bersama-sama mengosongkan variabel tersebut.
    memset(dosa, 0, sizeof(dosa));

    // Selamat Hari Raya Idul Fitri 1 Syawal 1445 H, Minal Aidin Wal Faidzin, Taqabalallahu minnaa wa minkum.
    printf("Selamat Hari Raya Idul Fitri 1445H!\n");
    printf("Taqabbalallahu minna wa minkum, minal aidin wal faidzin.\n");
    printf("Mohon maaf lahir dan batin.\n\n");

    printf("Dosa telah dikosongkan: 0 - 0\n");
    for (int i = 0; i < jumlah_dosa; i++) {
        printf("%s\n", dosa[i]);
    }

    // Segala puji bagi Allah, sekarang sudah kosong
    return 0;
}
