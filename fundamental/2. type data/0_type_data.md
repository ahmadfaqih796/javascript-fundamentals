Primitive vs Reference Type

Ini penting banget nanti.

Primitive
string
number
boolean
null
undefined

Disimpan langsung di memory.

Reference
object
array

Disimpan sebagai reference/alamat memory.

Contoh:

const a = { name: "Faqih" };
const b = a;

b.name = "Budi";

console.log(a.name);

Output:

Budi

Kenapa?
Karena a dan b menunjuk object yang sama.

Ini penting banget di React state management nanti.