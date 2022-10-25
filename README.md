Bu fonksiyon "async" olarak tanımlanmalı ve default olarak dışa aktarılmalıdır. Fonksiyonun içindeki asenkron fonksiyonlar "await" ile tanımlanmalıdır.

Fonksiyon Number tipinde tek parametre alır. Bu parametre user id'yi belirtir.

Fonksiyonun görevi aşağıdaki endpoint'e giderek parametrede verilen user id ile ilgili kullanıcının verilerini çekmek olmalı. İstekleri "axios" kütüphanesini kullanarak yapmanız gerekiyor. İsteği yaparken aşağıdaki endpointin sonundaki rakamı parametrede gelen user id'ile değiştirmeniz gerekiyor.

https://jsonplaceholder.typicode.com/users/1

Yine aynı fonksiyonun içerisinde ve yine aynı user id için bir de "posts" isteği yapılmalıdır.İsteği yaparken aşağıdaki endpoint'in sonundaki rakamı parametrede gelen user id'ile değiştirmeniz gerekiyor.

https://jsonplaceholder.typicode.com/posts?userId=1

Artık elimizde kullanıcı bilgileri ve bu kullanıcının post'ları var. Bu iki veriyi birleştirip return edin. Birleştirme sonucunda elinizde aşağıdaki gibi bir obje bulunması gerekiyor.

![output](https://user-images.githubusercontent.com/97432389/197807666-b34753ee-1fb1-4023-8afe-46a0ed70c265.png)
