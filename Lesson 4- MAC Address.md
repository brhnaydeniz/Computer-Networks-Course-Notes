**[TR](#tr) | [EN](#en)**

<a name="tr"></a>
# MAC Adresleri: Fiziksel Adresleme

Bu derste, MAC (Media Access Control) adreslerinin ne olduğunu, nasıl çalıştığını ve ağ iletişiminde neden önemli olduğunu öğreneceksiniz. MAC adresleri, ağ donanımlarının benzersiz olarak tanımlanmasını sağlar ve veri iletiminde kritik bir rol oynar.

## İçindekiler

1. [MAC Adresinin Tanımı](#mac-tanimi)
2. [MAC Adreslerinin Yapısı](#mac-yapisi)
3. [MAC Adreslerinin Çalışma Prensibi](#mac-prensip)
4. [MAC Adreslerinin Kullanım Alanları](#mac-kullanim)
5. [MAC Adreslerinin Yönetimi ve Güvenliği](#mac-yonetim)

---

<a name="mac-tanimi"></a>
## 1. MAC Adresinin Tanımı

MAC adresi, ağ arayüz kartlarına (NIC) atanmış 48-bit uzunluğunda benzersiz bir tanımlayıcıdır. Bu adres, cihazların yerel ağlarda birbirini tanıması ve veri alışverişi yapabilmesi için kullanılır. MAC adresi, genellikle onaltılık (hexadecimal) biçiminde yazılır ve altı oktet (bayt) içerir.

![MAC Adresi](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEdX4SG8wZpk0gsdzaxWSe0H_zGdjM71QcZDsvOJ9KNg1TPPr1t1TDe_mF&s=10)

<a name="mac-yapisi"></a>
## 2. MAC Adreslerinin Yapısı

MAC adresi, iki ana bölümden oluşur:

1. **Organizationally Unique Identifier (OUI):** İlk üç oktet, üreticiye özgü bir tanımlayıcıdır ve cihazın hangi firma tarafından üretildiğini gösterir.
2. **Cihaz Tanımlayıcısı:** Son üç oktet, cihazın benzersiz kimliğini belirtir.

### MAC Adresinin Görünümü

MAC adresleri genellikle şu biçimlerde yazılır:

- **XX:XX:XX:YY:YY:YY**
- **XX-XX-XX-YY-YY-YY**

Örneğin: 00:1A:2B:3C:4D:5E

![MAC Adresinin Yapısı](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfGktH_s8MRKNSsH1ahiFN2BUItHHi2UjlUCF-Wgp9W18w-M0IDmTI56yI&s=10)

<a name="mac-prensip"></a>
## 3. MAC Adreslerinin Çalışma Prensibi

MAC adresleri, yerel ağlarda cihazların birbirini tanıması ve iletişim kurması için kullanılır. Veri iletimi sırasında, kaynak cihazın MAC adresi ve hedef cihazın MAC adresi veri çerçevesine eklenir. Switchler, MAC adres tablosu kullanarak veriyi doğru cihazlara yönlendirir.

### MAC Adresinin Rolü

- **Adres Çözümleme Protokolü (ARP):** IP adreslerini MAC adreslerine dönüştürür.
- **Switchler:** MAC adres tablosu oluşturarak veriyi doğru portlara iletir.
- **Güvenlik:** Belirli MAC adreslerine izin vererek ağ güvenliği sağlanabilir.

![MAC Adres Çalışma Prensibi](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4mPpdVXwsQVVMgQhfU2VUTEIZkW8eiXIMs1nx3DsBQUvPW1S63Tfe6tE&s=10)

<a name="mac-kullanim"></a>
## 4. MAC Adreslerinin Kullanım Alanları

MAC adresleri, çeşitli ağ uygulamalarında ve protokollerinde kullanılır:

- **Ethernet:** Ethernet çerçevelerinde MAC adresleri kullanılır.
- **Wi-Fi:** Kablosuz ağlarda cihazlar, MAC adresleri ile tanımlanır.
- **Bluetooth:** Bluetooth cihazlarının tanımlanmasında kullanılır.
- **Ağ Yönetimi:** Ağ yöneticileri, cihazları MAC adresleri ile izleyebilir ve yönetebilir.


<a name="mac-yonetim"></a>
## 5. MAC Adreslerinin Yönetimi ve Güvenliği

### Yönetim

- **MAC Adres Filtreleme:** Ağ yöneticileri, belirli MAC adreslerine erişim izni vererek güvenliği artırabilir.
- **MAC Adres Tablosu:** Switchler, ağdaki cihazları tanımak için MAC adres tablosu kullanır.

### Güvenlik

- **MAC Adres Sahteciliği:** Saldırganlar, ağda yetkisiz erişim sağlamak için MAC adreslerini taklit edebilir. Bu tür saldırılara karşı önlem almak önemlidir.
- **Ağ İzleme:** MAC adreslerini izleyerek anormal etkinlikler tespit edilebilir.

![MAC Adres Güvenliği](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT9jw8YkUPtcM4pyqjuTYejTH-H_sVWBoQsssW4b_RXZXr_vQl_mAXOhoEi&s=10)

---

Bu ders, MAC adreslerinin ne olduğunu, nasıl çalıştığını ve ağ iletişimindeki önemini anlamanızı sağlamıştır. Daha fazla bilgi ve uygulama için diğer derslerimize göz atabilirsiniz.

<a name="en"></a>
# MAC Addresses: Physical Addressing

In this lesson, you will learn what MAC (Media Access Control) addresses are, how they work, and why they are important in network communication. MAC addresses uniquely identify network hardware and play a critical role in data transmission.

## Contents

1. [Definition of MAC Address](#mac-definition)
2. [Structure of MAC Addresses](#mac-structure)
3. [How MAC Addresses Work](#mac-principle)
4. [Uses of MAC Addresses](#mac-usage)
5. [Management and Security of MAC Addresses](#mac-management)

---

<a name="mac-definition"></a>
## 1. Definition of MAC Address

A MAC address is a 48-bit unique identifier assigned to network interface cards (NICs). This address allows devices on local networks to recognize each other and exchange data. MAC addresses are usually written in hexadecimal format and consist of six octets (bytes).

![MAC Address](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEdX4SG8wZpk0gsdzaxWSe0H_zGdjM71QcZDsvOJ9KNg1TPPr1t1TDe_mF&s=10)

<a name="mac-structure"></a>
## 2. Structure of MAC Addresses

A MAC address consists of two main parts:

1. **Organizationally Unique Identifier (OUI):** The first three octets identify the manufacturer of the device.
2. **Device Identifier:** The last three octets provide the unique identity of the device.

### MAC Address Appearance

MAC addresses are typically written in the following formats:

- **XX:XX:XX:YY:YY:YY**
- **XX-XX-XX-YY-YY-YY**

For example: 00:1A:2B:3C:4D:5E

![Structure of MAC Address](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfGktH_s8MRKNSsH1ahiFN2BUItHHi2UjlUCF-Wgp9W18w-M0IDmTI56yI&s=10)

<a name="mac-principle"></a>
## 3. How MAC Addresses Work

MAC addresses are used for devices on local networks to recognize and communicate with each other. During data transmission, the source device's MAC address and the destination device's MAC address are added to the data frame. Switches use a MAC address table to route data to the correct devices.

### Role of MAC Addresses

- **Address Resolution Protocol (ARP):** Converts IP addresses to MAC addresses.
- **Switches:** Use MAC address tables to direct data to the correct ports.
- **Security:** Network security can be enhanced by allowing only certain MAC addresses.

![How MAC Addresses Work](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4mPpdVXwsQVVMgQhfU2VUTEIZkW8eiXIMs1nx3DsBQUvPW1S63Tfe6tE&s=10)

<a name="mac-usage"></a>
## 4. Uses of MAC Addresses

MAC addresses are used in various network applications and protocols:

- **Ethernet:** Used in Ethernet frames.
- **Wi-Fi:** Devices in wireless networks are identified by their MAC addresses.
- **Bluetooth:** Used to identify Bluetooth devices.
- **Network Management:** Network administrators can monitor and manage devices using MAC addresses.

<a name="mac-management"></a>
## 5. Management and Security of MAC Addresses

### Management

- **MAC Address Filtering:** Network administrators can enhance security by allowing access only to certain MAC addresses.
- **MAC Address Table:** Switches use a MAC address table to recognize devices on the network.

### Security

- **MAC Address Spoofing:** Attackers may mimic MAC addresses to gain unauthorized access to the network. It is important to take measures against such attacks.
- **Network Monitoring:** Anomalous activities can be detected by monitoring MAC addresses.

![MAC Address Security](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT9jw8YkUPtcM4pyqjuTYejTH-H_sVWBoQsssW4b_RXZXr_vQl_mAXOhoEi&s=10)

---

This lesson has provided you with an understanding of what MAC addresses are, how they work, and their importance in network communication. For more information and practice, check out our other lessons.
