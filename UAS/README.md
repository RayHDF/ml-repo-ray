### Tiap folder memiliki 1 notebook atau lebih
### Pada regresi, menggunakan preprocessing yang dilakukan di UTS, dan ditambahkan beberapa tahap lagi untuk menyesuikan dengan MLP -> Standardized Target.
### Pada classification MLP, menargetkan kolom "Class" (type int). Ada 2 kelas, 0 dan 1, namun kelas 1 sangat sedikit, jadi menggunakan teknik weights untuk menyesuaikan.
### Pada classification CNN, awalnya menggunakan custom CNN dari awal (from scratch), lalu menggunakan transfer learning dari ResNet50.
