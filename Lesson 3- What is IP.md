**[TR](#tr) | [EN](#en)**

<a name="tr"></a>
# Ders 3: IP Adresleri

**Merhaba ve hoş geldiniz!**

Bu derste, IP adreslerinin ne olduğunu, nasıl çalıştığını, türlerini ve yapılarını detaylı bir şekilde inceleyeceğiz. IP adresleri, internet ve ağ iletişiminin temel taşlarından biridir.

## 1. IP Adresinin Tanımı

IP adresi (Internet Protocol Address), bir cihazın ağ üzerinde kimliğini belirten ve ona veri iletimini sağlayan benzersiz bir numaradır. IP adresleri, ağ cihazlarının birbirini tanımasını ve veri alışverişini mümkün kılar.

### Temel Özellikler
- **Benzersizlik:** Her cihazın ağda benzersiz bir IP adresi olmalıdır.
- **Yönlendirme:** IP adresleri, verilerin doğru cihazlara yönlendirilmesini sağlar.
- **Düzeyler:** IP adresleri, ağ üzerinde farklı düzeylerde çalışır (örneğin, yerel ağ veya geniş alan ağı).

![IP Adresi](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQg3YTbx6jdp94X1JPoUk5Xch71vEImom7lpfnyOTEdwOZEOGeNWhn9eBc&s=10)

## 2. IP Adresi Türleri

### IPv4 Adresleri
IPv4, IP adreslerinin en yaygın kullanılan versiyonudur. 32 bit uzunluğundadır ve dört oktet (byte) olarak gösterilir. Her bir oktet, 0 ile 255 arasında bir değeri temsil eder.

#### Yapı
- **Adres Formatı:** xxx.xxx.xxx.xxx (örneğin, 192.168.1.1)
- **Adres Uzunluğu:** 32 bit
- **Toplam Adres Sayısı:** 2^32 (yaklaşık 4.3 milyar adres)
- **Kullanım Alanları:** Ev ve küçük ofis ağları, bazı geniş alan ağları.

### IPv6 Adresleri
IPv6, IPv4'ün sınırlamalarını aşmak için geliştirilmiştir. 128 bit uzunluğundadır ve sekiz grup heksadesimal sayı olarak gösterilir.

#### Yapı
- **Adres Formatı:** xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx (örneğin, 2001:0db8:85a3:0000:0000:8a2e:0370:7334)
- **Adres Uzunluğu:** 128 bit
- **Toplam Adres Sayısı:** 2^128 (yaklaşık 3.4 x 10^38 adres)
- **Kullanım Alanları:** Gelecekteki ağlar, büyük ölçekli internet uygulamaları.

![IPv6 Adresi](https://cdn.ttgtmedia.com/rms/onlineimages/whatis-ipv6_address-h_half_column_mobile.png)

## 3. IP Adresi Sınıfları

### IPv4 Sınıfları
IPv4 adresleri, farklı sınıflara ayrılır ve her sınıfın belirli bir kullanım amacı vardır.

- **Sınıf A:** 0.0.0.0 ile 127.255.255.255 arası adresler. Büyük ağlar için kullanılır.
- **Sınıf B:** 128.0.0.0 ile 191.255.255.255 arası adresler. Orta ölçekli ağlar için kullanılır.
- **Sınıf C:** 192.0.0.0 ile 223.255.255.255 arası adresler. Küçük ağlar için kullanılır.
- **Sınıf D:** 224.0.0.0 ile 239.255.255.255 arası adresler. Multicast adresleri için kullanılır.
- **Sınıf E:** 240.0.0.0 ile 255.255.255.255 arası adresler. Deneysel ve özel kullanım için ayrılmıştır.

### IPv6 Sınıfları
IPv6'da sınıflandırma yerine, adresler farklı alanlara ve özelliklere göre düzenlenmiştir.

- **Unicast:** Tek bir cihazı hedefler.
- **Multicast:** Birden fazla cihazı hedefler.
- **Anycast:** En yakın cihazı hedefler.

## 4. Özel IP Adresleri ve Genel IP Adresleri

### Özel IP Adresleri
Özel IP adresleri, internet üzerinde doğrudan erişilemeyen ve yalnızca yerel ağlarda kullanılan adreslerdir. Özel IP aralıkları şunlardır:
- **Sınıf A:** 10.0.0.0 – 10.255.255.255
- **Sınıf B:** 172.16.0.0 – 172.31.255.255
- **Sınıf C:** 192.168.0.0 – 192.168.255.255

### Genel IP Adresleri
Genel IP adresleri, internet üzerinden herkes tarafından erişilebilen adreslerdir. Bu adresler, internet servis sağlayıcıları tarafından atanır ve geniş alan ağlarında kullanılır.

## 5. IP Adresi Alt Ağları

Alt ağ (subnet) kullanımı, büyük ağları daha küçük ve yönetilebilir parçalara ayırmak için kullanılır. Her alt ağın kendine özgü bir IP aralığı ve ağ maskesi vardır.

### Alt Ağ Maskesi
Alt ağ maskesi, IP adreslerinin hangi kısmının ağ adresini ve hangi kısmının cihaz adresini belirlediğini gösterir. Yaygın alt ağ maskeleri:
- **255.0.0.0 (Sınıf A)**
- **255.255.0.0 (Sınıf B)**
- **255.255.255.0 (Sınıf C)**

![Subnetting](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQr4KafVT5SO7-9XcK8b2xExvNJMh1dqeq1wLwp9dDnZVq7VDeLtidhHDrA&s=10)

### CIDR (Classless Inter-Domain Routing)
CIDR, IP adresleri ve alt ağ maskelerinin daha esnek bir şekilde yönetilmesini sağlar. CIDR notasyonu şu şekilde gösterilir: `192.168.1.0/24`.

## 6. IP Adresi Atama Yöntemleri

### Statik IP Adresi
Statik IP adresi, cihazlara manuel olarak atanır ve genellikle sabit bir bağlantı için kullanılır. Statik IP adresleri, sunucular ve ağ cihazları için yaygındır.

### Dinamik IP Adresi
Dinamik IP adresi, DHCP (Dynamic Host Configuration Protocol) sunucusu tarafından otomatik olarak atanır. Bu yöntem, IP adreslerinin ağ üzerindeki cihazlar arasında dinamik olarak dağıtılmasını sağlar.

![DHCP](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRq2Qlr-n2OE8phxTW3B7ZvFQ4S9ViqkEzrrWJ4AT4fEZ0m1OR6RrKZgQeG&s=10)

---

Bu ders, IP adreslerinin yapısını ve işleyişini anlamanızı sağlar. IP adreslerinin türlerini, sınıflarını, özel ve genel adresleri, alt ağları ve atama yöntemlerini detaylı bir şekilde öğrenerek, ağ yönetimi ve tasarımı konularında yetkinlik kazanabilirsiniz.

<a name="en"></a>
# Lesson 3: IP Addresses

**Hello and welcome!**

In this lesson, we will explore IP addresses in detail, including what they are, how they work, their types, and structures. IP addresses are fundamental to internet and network communication.

## 1. Definition of IP Address

An IP address (Internet Protocol Address) is a unique number that identifies a device on a network and enables data transmission. IP addresses allow network devices to identify each other and exchange data.

### Key Features
- **Uniqueness:** Each device on a network must have a unique IP address.
- **Routing:** IP addresses facilitate the routing of data to the correct devices.
- **Layers:** IP addresses operate at various levels on a network (e.g., local network or wide area network).

![IP Address](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQg3YTbx6jdp94X1JPoUk5Xch71vEImom7lpfnyOTEdwOZEOGeNWhn9eBc&s=10)

## 2. Types of IP Addresses

### IPv4 Addresses
IPv4 is the most commonly used version of IP addresses. It is 32 bits long and is represented in four octets (bytes). Each octet represents a value between 0 and 255.

#### Structure
- **Address Format:** xxx.xxx.xxx.xxx (e.g., 192.168.1.1)
- **Address Length:** 32 bits
- **Total Number of Addresses:** 2^32 (approximately 4.3 billion addresses)
- **Usage:** Home and small office networks, some wide area networks.

### IPv6 Addresses
IPv6 was developed to overcome the limitations of IPv4. It is 128 bits long and is represented in eight groups of hexadecimal numbers.

#### Structure
- **Address Format:** xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334)
- **Address Length:** 128 bits
- **Total Number of Addresses:** 2^128 (approximately 3.4 x 10^38 addresses)
- **Usage:** Future networks, large-scale internet applications.

![IPv6 Address](https://cdn.ttgtmedia.com/rms/onlineimages/whatis-ipv6_address-h_half_column_mobile.png)

## 3. IP Address Classes

### IPv4 Classes
IPv4 addresses are categorized into different classes, each serving specific purposes.

- **Class A:** Ranges from 0.0.0.0 to 127.255.255.255. Used for large networks.
- **Class B:** Ranges from 128.0.0.0 to 191.255.255.255. Used for medium-sized networks.
- **Class C:** Ranges from 192.0.0.0 to 223.255.255.255. Used for small networks.
- **Class D:** Ranges from 224.0.0.0 to 239.255.255.255. Used for multicast addresses.
- **Class E:** Ranges from 240.0.0.0 to 255.255.255.255. Reserved for experimental use.

### IPv6 Classes
IPv6 does not use classes but categorizes addresses based on their function and scope.

- **Unicast:** Targets a single device.
- **Multicast:** Targets multiple devices.
- **Anycast:** Targets the nearest device.

## 4. Private and Public IP Addresses

### Private IP Addresses
Private IP addresses are used within local networks and are not directly accessible from the internet. The ranges for private IP addresses are:
- **Class A:** 10.0.0.0 – 10.255.255.255
- **Class B:** 172.16.0.0 – 172.31.255.255
- **Class C:** 192.168.0.0 – 192.168.255.255

### Public IP Addresses
Public IP addresses are accessible over the internet and are assigned by internet service providers. These addresses are used for wide area networks and global internet connectivity.

## 5. IP Address Subnetting

Subnetting is used to divide larger networks into smaller, manageable parts. Each subnet has a specific IP range and subnet mask.

### Subnet Mask
A subnet mask indicates which portion of the IP address is the network address and which is the device address. Common subnet masks include:
- **255.0.0.0 (Class A)**
- **255.255.0.0 (Class B)**
- **255.255.255.0 (Class C)**

![Subnetting](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQr4KafVT5SO7-9XcK8b2xExvNJMh1dqeq1wLwp9dDnZVq7VDeLtidhHDrA&s=10)

### CIDR (Classless Inter-Domain Routing)
CIDR allows for more flexible IP address management. CIDR notation is shown as: `192.168.1.0/24`.

## 6. IP Address Assignment Methods

### Static IP Address
A static IP address is manually assigned to a device and remains constant. It is commonly used for servers and network devices.

### Dynamic IP Address
A dynamic IP address is automatically assigned by a DHCP (Dynamic Host Configuration Protocol) server. This method allows IP addresses to be dynamically allocated among devices on the network.

![DHCP](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRq2Qlr-n2OE8phxTW3B7ZvFQ4S9ViqkEzrrWJ4AT4fEZ0m1OR6RrKZgQeG&s=10)

---

This lesson provides a detailed understanding of IP addresses, including their types, classes, private and public addresses, subnetting, and assignment methods. By mastering these concepts, you will enhance your skills in network management and design.
