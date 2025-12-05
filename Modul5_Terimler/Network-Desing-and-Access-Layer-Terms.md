## 📝 Modül 5: Veri Akışı, Adresleme ve Tasarım Modelleri

| Kategori                    | Terim                         | Açıklama                                                                                                          |
| :-------------------------- | :---------------------------- | :---------------------------------------------------------------------------------------------------------------- |
| **Veri Paketleme**          | **Encapsulation**             | Üst katmandan gelen verinin, protokol başlıkları (header) eklenerek alt katmana iletilmesi süreci (paketleme).    |
|                             | **Frame**                     | Verinin **Veri Bağlantı (Data Link) Katmanı**'nda (Layer 2) taşınan haline verilen isim.                          |
|                             | **Ethernet frame**            | Ethernet protokolüne uygun olarak başlık ve kuyruk bilgileri (header/trailer) eklenmiş veri birimi.               |
| **Adresleme Türleri**       | **Physical address**          | Cihazın ağ kartına (NIC) üretici tarafından kalıcı olarak atanan **fiziksel** adres.                              |
|                             | **MAC address**               | **Ortam Erişim Kontrolü Adresi**; Cihazın fiziksel adresi (Layer 2 adreslemesi).                                  |
|                             | **Logical address**           | Cihaza ağ yöneticisi tarafından mantıksal olarak atanan ve yönlendirmeye imkan veren adres.                       |
|                             | **IP address**                | **İnternet Protokol Adresi**; Cihazın mantıksal adresi (Layer 3 adreslemesi).                                     |
| **Hiyerarşik Tasarım**      | **Hierarchical design**       | Ağın, yönetimi, ölçeklenebilirliği ve performansı artırmak için katmanlara ayrılarak tasarlanması.                |
|                             | **Hierarchical design model** | Büyük ağları **Erişim (Access), Dağıtım (Distribution) ve Çekirdek (Core)** katmanlarına ayıran mimari model.     |
|                             | **Access layer**              | Son kullanıcı cihazlarının (PC, telefon) ağa bağlandığı katman (Genellikle Switch'ler bulunur).                   |
|                             | **Distribution layer**        | Erişim katmanından gelen trafiği yönlendiren ve filtreleyen, politikaları uygulayan katman.                       |
|                             | **Core layer**                | Tüm ağ trafiğini en hızlı şekilde taşımaktan sorumlu olan, yüksek hızlı omurga katmanı.                           |
| **Ağ Cihazları ve İşlevi**  | **Ethernet hub**              | Gelen veriyi tüm portlara kopyalayan (tekrarlayan) eski ve verimsiz ağ cihazı.                                    |
|                             | **Ethernet switch**           | Gelen veriyi sadece hedef MAC adresinin bağlı olduğu porta ileten akıllı ağ cihazı.                               |
|                             | **MAC address table**         | Switch'in hangi porta hangi MAC adresinin bağlı olduğunu kaydettiği tablo (CAM Tablosu).                          |
| **Yayın (Broadcast) Akışı** | **Broadcast**                 | Ağdaki **tüm** cihazlara aynı anda gönderilen tek bir mesaj.                                                      |
|                             | **Broadcast domain**          | Bir mesajın yayın (broadcast) olarak gönderildiğinde ulaşabileceği cihazların grubu.                              |
|                             | **ARP**                       | **Adres Çözümleme Protokolü**; Bir IP adresi verilen cihazın MAC adresini bulmak için kullanılan yayın protokolü. |
|                             | **Broadcast containment**     | Yayın trafiğinin (broadcast) belirli ağ sınırlarında kalmasını sağlamak ve ağ performansını korumak.              |
