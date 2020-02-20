#### Problem 2

##### Unique Queue

Queue adalah suatu antrian, yang mana siapa yang masuk duluan akan keluar terlebih dahulu. Berarti jika queue fix adalah antrian yang batas antriannya tetap dan tidak pernah bertambah.

Karena batas antrian tetap dan tidak pernah bertambah. Maka saya mengasumsikan bahwa jika batas antrian penuh, antrian pertama akan keluar dari antrian. Oleh karena itu pada saat membuat program ini saya membuat batasan pada push, jika antrian sudah penuh, atau index sudah sampai ke max. Maka saya akan mengeluarkan Orang pertama yang mengantri, atau index ke 0 dari slice tersebut.
