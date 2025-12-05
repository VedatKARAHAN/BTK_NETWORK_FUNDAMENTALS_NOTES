## 📝 Modül 3: Kablolama Standartları ve Komutlar

| Kategori                    | Terim                          | Açıklama                                                                                                                      |
| :-------------------------- | :----------------------------- | :---------------------------------------------------------------------------------------------------------------------------- |
| **Kablo Türleri**           | **Copper cable**               | Veriyi elektrik sinyalleriyle ileten, genellikle bakırdan yapılmış kablo.                                                     |
|                             | **Coaxial cable**              | Merkezde bir iletken, etrafında yalıtkan ve örgü kaplama olan kablo (Örn: eski TV kabloları).                                 |
|                             | **Fiber-optical cable**        | Veriyi cam veya plastikten yapılmış ince teller üzerinden ışık sinyaliyle ileten kablo.                                       |
| **Twisted-Pair Kablolar**   | **Twisted-pair cable**         | Elektromanyetik girişimi azaltmak için birbirine bükülmüş çiftler halinde bakır teller içeren kablo.                          |
|                             | **UTP cable**                  | **Korumasız Bükümlü Çift**; En yaygın, ekranlama (shielding) olmayan bükümlü çift kablo.                                      |
|                             | **STP Cable**                  | **Korumalı Bükümlü Çift**; Veri bütünlüğünü artırmak için folyo veya örgü ekranlaması olan kablo.                             |
|                             | **UTP cable category**         | UTP kabloların veri hızına ve bant genişliğine göre sınıflandırılması (örn: Cat5e, Cat6).                                     |
| **Konektörler**             | **RJ-11 connector**            | Telefon hatlarında kullanılan, 4 pime kadar destekleyen küçük konektör.                                                       |
|                             | **RJ-45 connector**            | Ethernet ağlarında kullanılan, 8 pime kadar destekleyen standart konektör.                                                    |
| **Kablolama Standartları**  | **Twisted-pair wiring scheme** | Bükümlü çift kabloların (UTP/STP) konektörlere takılma düzenini belirleyen standart.                                          |
|                             | **TIE/EIA**                    | Kablolama standartlarını belirleyen iki ana kurum (Telecommunications Industry Association / Electronic Industries Alliance). |
|                             | **T568A**                      | TIE/EIA tarafından belirlenen bir uçtan uca kablo bağlantı pin dizilimi standardı (Yeşil Çift öncelikli).                     |
|                             | **T568B**                      | TIE/EIA tarafından belirlenen diğer pin dizilimi standardı (Turuncu Çift öncelikli).                                          |
| **Kablo Tipleri**           | **Straight-through cable**     | Her iki ucunda da aynı pin dizilimi (örn: T568A/A veya T568B/B) kullanılan, en yaygın bağlantı kablosu (Patch kablo).         |
|                             | **Patch cable**                | Genellikle kısa mesafeli bağlantılar için kullanılan, önceden hazırlanmış düz (Straight-through) kablo.                       |
|                             | **Crossover cable**            | Uçlarında farklı pin dizilimi (örn: T568A/B) kullanılan, **benzer cihazları** doğrudan bağlamak için kullanılan kablo.        |
| **Cihaz Bağlantıları**      | **Like devices**               | Aynı türden veya aynı katmanda çalışan cihazlar (örn: PC-PC, Router-Router). Crossover kablo ile bağlanır.                    |
|                             | **Unlike devices**             | Farklı türden cihazlar (örn: PC-Switch, Router-Switch). Straight-through kablo ile bağlanır.                                  |
| **Sorun Giderme Komutları** | **Ping utility**               | Bir cihaza IP paketi göndererek **bağlantı durumunu** ve gecikmeyi (latency) test eden araç/komut.                            |
|                             | **Traceroute utility**         | Bir paketin hedefine ulaşana kadar geçtiği **tüm router sıçramalarını** (hops) gösteren araç/komut.                           |
|                             | **TRACERT command**            | Windows işletim sistemlerinde `Traceroute` işlemini gerçekleştiren komut.                                                     |
