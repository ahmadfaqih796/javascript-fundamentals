1. Variable & Data Type (Fundamental JavaScript)

Ini pondasi paling dasar JavaScript.

Kalau ini kuat, nanti belajar React, Node.js, bahkan TypeScript bakal jauh lebih gampang.

3. var (HINDARI)
var city = "Bekasi";

Dulu dipakai sebelum ES6.

Sekarang hampir tidak dipakai karena:

behavior aneh
hoisting membingungkan
scope tidak aman

Nanti kita bahas lebih dalam.

Untuk sekarang:

pakai const dulu
kalau perlu berubah → let

Rule Praktis
Gunakan const secara default
const name = "Faqih";
Pakai let kalau memang berubah
let counter = 0;
counter++;
Hindari var