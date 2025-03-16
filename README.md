def perkalian(a, b):
  """
  Fungsi untuk menghitung perkalian a * b menggunakan penjumlahan berulang.

  Args:
    a: Bilangan pertama.
    b: Bilangan kedua.

  Returns:
    Hasil perkalian a * b.
  """

  hasil = 0
  for _ in range(b):
    hasil += a
  return hasil

# Contoh penggunaan
angka1 = 6
angka2 = 5
hasil_perkalian = perkalian(angka1, angka2)
print(f"{angka1} x {angka2} = {hasil_perkalian}")

angka3 = 7
angka4 = 10
hasil_perkalian2 = perkalian(angka3, angka4)
print(f"{angka3} x {angka4} = {hasil_perkalian2}")
