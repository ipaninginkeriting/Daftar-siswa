public class DaftarSiswa {
    public static void main(String[] args) {
        // Membuat array dengan nama-nama siswa
        String[] siswa = {"Andi", "Budi", "Citra", "Dewi", "Eka"};
        
        // Menampilkan daftar nama siswa dengan nomor urut
        System.out.println("Daftar Nama Siswa:");
        for (int i = 0; i < siswa.length; i++) {
            // Menampilkan nomor urut dan nama siswa
            System.out.println("Nama ke-" + (i + 1) + ": " + siswa[i]);
        }
    }
}

