package Data


class Buku(judul :String) {
    var judul: String = judul
    get() {
        println("Memanggil getters")
        return field
    }
    set(value) {
        println("Memanggil setters")
        if (value.isNotBlank()) {
            field = value
        } else {
        println("judul tidak ada")
             }
        }
}
class Pengarang(val nama : String){
    val kapital : String
    get() = nama.toUpperCase()
}
package App

import Data.Buku
import Data.Pengarang

fun main() {
    val buku = Buku("Belajar OOP")
    val pengarang = Pengarang("Dani")

    println(buku.judul)
    buku.judul =""
    println(pengarang.nama)
    println(pengarang.kapital)
}
