$(document).ready(function() {
    let clickCount = 0; // Variabel untuk menyimpan jumlah klik

    $('#clickButton').click(function() {
        clickCount++; // Tambah 1 setiap kali tombol diklik
        $('#count').text('Jumlah Klik: ' + clickCount); // Update teks dengan jumlah klik terbaru
    });
});
