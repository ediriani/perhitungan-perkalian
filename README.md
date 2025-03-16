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

