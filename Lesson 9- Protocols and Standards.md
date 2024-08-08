**[TR](#tr) | [EN](#en)**

<a name="tr"></a>

# Protokoller ve Standartlar Hakkında Detaylı Bilgi

## 1. Giriş

Bilgisayar ağlarında, protokoller ve standartlar, cihazların verimli ve güvenilir bir şekilde iletişim kurmasını sağlar. Bu doküman, çeşitli ağ protokollerini, yaygın olarak kullandıkları portları ve bu protokollerin uygulanmasını yönlendiren standartları kapsar.

## 2. Ağ Protokolleri

### 2.1 TCP/IP Protokol Ailesi

#### 2.1.1 İletim Kontrol Protokolü (TCP)

- **Port Aralığı**: 0 - 1023 (iyi bilinen portlar)
- **Yaygın Portlar**:
  - **HTTP**: TCP 80
  - **HTTPS**: TCP 443
  - **FTP (Kontrol)**: TCP 21
  - **SMTP**: TCP 25
  - **Telnet**: TCP 23
- **Fonksiyonalite**: Ağdaki uygulamalar arasında sıralı, güvenilir ve hataya dayanıklı veri akışını sağlar.

#### 2.1.2 Kullanıcı Datagram Protokolü (UDP)

- **Port Aralığı**: 0 - 1023 (iyi bilinen portlar)
- **Yaygın Portlar**:
  - **DNS**: UDP 53
  - **DHCP**: UDP 67 (sunucu), 68 (istemci)
  - **TFTP**: UDP 69
  - **SNMP**: UDP 161
- **Fonksiyonalite**: Bağlantısız bir datagram hizmeti sağlar ve hız, güvenilirliğin önünde gelir.

### 2.2 Uygulama Katmanı Protokolleri

#### 2.2.1 Hiper Metin Transfer Protokolü (HTTP)

- **Port**: TCP 80
- **Açıklama**: World Wide Web için veri iletişiminin temelini oluşturur.
- **Kullanım Durumu**: Web üzerinde hiper metin belgelerinin ve diğer verilerin iletilmesi.

#### 2.2.2 Hiper Metin Transfer Protokolü Güvenli (HTTPS)

- **Port**: TCP 443
- **Açıklama**: HTTP'nin uzantısı olup, bir istemci ve sunucu arasındaki veri değişimini şifreleme kullanarak güvenli hale getirir.
- **Kullanım Durumu**: Güvenli web taraması, çevrimiçi bankacılık ve güvenli veri aktarımı gerektiren diğer uygulamalar.

#### 2.2.3 Dosya Transfer Protokolü (FTP)

- **Portlar**: 
  - **Kontrol**: TCP 21
  - **Veri**: TCP 20
- **Açıklama**: Bir ağ üzerindeki bir istemci ile sunucu arasında bilgisayar dosyalarının transferi için kullanılan standart bir ağ protokolü.
- **Kullanım Durumu**: Uzak bir sunucuya dosya yüklemek ve indirmek.

#### 2.2.4 Basit Posta Aktarım Protokolü (SMTP)

- **Port**: TCP 25
- **Açıklama**: Sunucular arasındaki e-postaların gönderimi için kullanılan protokol.
- **Kullanım Durumu**: E-posta iletimi.

#### 2.2.5 Alan Adı Sistemi (DNS)

- **Portlar**: 
  - **Sorgu**: UDP 53
  - **Bölge Transferi**: TCP 53
- **Açıklama**: İnsan tarafından okunabilir alan adlarını IP adreslerine çevirir.
- **Kullanım Durumu**: Alan adlarını IP adreslerine çözme.

### 2.3 Ağ Katmanı Protokolleri

#### 2.3.1 İnternet Protokolü (IP)

- **Açıklama**: Ağ sınırları boyunca datagramların iletimini sağlayan temel protokol.
- **Versiyonlar**: 
  - **IPv4**: 32-bit adresleme, yaygın olarak kullanılır.
  - **IPv6**: 128-bit adresleme, kademeli olarak IPv4'ün yerini alıyor.

#### 2.3.2 İnternet Kontrol Mesaj Protokolü (ICMP)

- **Açıklama**: Ağ cihazları tarafından hata mesajları ve operasyonel bilgi göndermek için kullanılır.
- **Yaygın Kullanım**: 
  - **Ping**: Bir ana bilgisayarın erişilebilirliğini test etmek.
- **Port**: ICMP, port kullanmaz ancak IP paketleri içinde kapsüllenir.

### 2.4 Veri Bağlantı Katmanı Protokolleri

#### 2.4.1 Ethernet

- **Açıklama**: En yaygın LAN teknolojisi olup, fiziksel katman için kablolama ve sinyalizasyonu tanımlar.
- **Standart**: IEEE 802.3
- **Çerçeve Yapısı**: Kaynak ve hedef için MAC adreslerini içerir.

#### 2.4.2 Noktadan Noktaya Protokol (PPP)

- **Açıklama**: İki düğüm arasında doğrudan bağlantı kurmak için kullanılan bir veri bağlantı katmanı protokolü.
- **Yaygın Kullanım**: 
  - **Çevirmeli internet erişimi**.
  - **VPN'ler**.

### 2.5 Taşıma Katmanı Protokolleri

#### 2.5.1 İletim Kontrol Protokolü (TCP)

- **Fonksiyonalite**: Uygulamalar arasında güvenilir, sıralı ve hataya dayanıklı veri iletimi sağlar.
- **Yaygın Kullanım**: HTTP, HTTPS, FTP.

#### 2.5.2 Kullanıcı Datagram Protokolü (UDP)

- **Fonksiyonalite**: Hızlı, güvenilmez bir bağlantısız datagram hizmeti sağlar.
- **Yaygın Kullanım**: DNS, VoIP, video akışı.

### 2.6 Kontrol Protokolleri

#### 2.6.1 Basit Ağ Yönetim Protokolü (SNMP)

- **Port**: UDP 161
- **Açıklama**: IP ağlarında yönetilen cihazlar hakkında bilgi toplama ve düzenleme için bir internet standardı protokolü.
- **Kullanım Durumu**: Ağ yönetimi.

#### 2.6.2 Dinamik Ana Bilgisayar Yapılandırma Protokolü (DHCP)

- **Portlar**: 
  - **Sunucu**: UDP 67
  - **İstemci**: UDP 68
- **Açıklama**: Bir ağdaki cihazlara IP adresleri ve diğer ağ yapılandırma parametrelerini otomatik olarak atar.
- **Kullanım Durumu**: Büyük ağlarda IP yapılandırma sürecini otomatikleştirme.

## 3. Ağ Standartları

### 3.1 IEEE 802 Standartları

#### 3.1.1 IEEE 802.3 (Ethernet)

- **Açıklama**: Kablolu yerel alan ağları (LAN) için standart.
- **Veri Hızı**: 
  - **10 Mbps** (Ethernet)
  - **100 Mbps** (Hızlı Ethernet)
  - **1 Gbps** (Gigabit Ethernet)
  - **10 Gbps** (10-Gigabit Ethernet)

#### 3.1.2 IEEE 802.11 (Wi-Fi)

- **Açıklama**: Kablosuz yerel alan ağları (WLAN) için standart.
- **Frekans Bantları**:
  - **2.4 GHz**: Eski Wi-Fi cihazları için yaygın.
  - **5 GHz**: Daha hızlı, modern Wi-Fi cihazları için kullanılır.
  - **6 GHz**: Yeni, daha az kalabalık bant, Wi-Fi 6E cihazları için.

#### 3.1.3 IEEE 802.15 (Bluetooth)

- **Açıklama**: Kısa mesafeli kablosuz iletişim için standart.
- **Yaygın Kullanım**: 
  - **Kişisel Alan Ağları (PAN)**.
  - **Cihaz eşleştirme**: Mobil telefonlar, dizüstü bilgisayarlar, vb.

### 3.2 IETF Standartları

#### 3.2.1 RFC Belgeleri

- **Açıklama**: İnternet protokolleri ve teknolojileri için standartları tanımlayan RFC (Request for Comments) belgeleri.
- **Örnekler**:
  - **RFC 791**: IPv4.
  - **RFC 2460**: IPv6.
  - **RFC 793**: TCP.

### 3.3 ISO Standartları

#### 3.3.1 ISO/IEC 7498 (OSI Modeli)

- **Açıklama**: Ağ protokollerini anlamak ve tasarlamak için kullanılan yedi katmanlı OSI modelini tanımlar.
- **Katmanlar**:
  1. Fiziksel
  2. Veri Bağlantısı
  3. Ağ
  4. Taşıma
  5. Oturum
  6. Sunum
  7. Uygulama

### 3.4 ITU Standartları

#### 3.4.1 ITU-T X.25

- **Açıklama**: Paket anahtarlamalı ağlar için erken bir standart.
- **Kullanım Durumu**: Frame Relay ve ATM ağları, modern IP ağlarının öncüsü.

## 4. Protokoller ve Standartların Kullanım Durumları

Protokoller ve standartlar, küresel internet iletişiminden özel şirket ağlarına kadar çeşitli senaryolarda kullanılır. Ağ tasarımı, sorun giderme ve cihazlar ve sistemler arasında birlikte çalışabilirliği sağlamak için bu protokollerin ve standartların anlaşılması çok önemlidir.

## 5. Sonuç

Bu doküman, anahtar ağ protokollerini ve standartlarını, bu protokollerle yaygın olarak ilişkili portlar da dahil olmak üzere kapsamaktadır. Ağ mühendislerinden BT yöneticilerine kadar ağlarla ilgilenen herkes için, bu kavramların ayrıntılı bir şekilde anlaşılması, ağ performansını yönetmek ve optimize etmek için hayati öneme sahiptir.

<a name="en"></a>

# Detailed Information on Protocols and Standards

## 1. Introduction

In computer networking, protocols and standards are essential for enabling devices to communicate efficiently and reliably. This document covers various network protocols, the ports they commonly use, and the standards that guide their implementation.

## 2. Network Protocols

### 2.1 TCP/IP Protocol Suite

#### 2.1.1 Transmission Control Protocol (TCP)

- **Port Range**: 0 - 1023 (well-known ports)
- **Common Ports**:
  - **HTTP**: TCP 80
  - **HTTPS**: TCP 443
  - **FTP (Control)**: TCP 21
  - **SMTP**: TCP 25
  - **Telnet**: TCP 23
- **Functionality**: Provides reliable, ordered, and error-checked delivery of a stream of data between applications running on hosts in a network.

#### 2.1.2 User Datagram Protocol (UDP)

- **Port Range**: 0 - 1023 (well-known ports)
- **Common Ports**:
  - **DNS**: UDP 53
  - **DHCP**: UDP 67 (server), 68 (client)
  - **TFTP**: UDP 69
  - **SNMP**: UDP 161
- **Functionality**: Provides a connectionless datagram service that emphasizes speed over reliability.

### 2.2 Application Layer Protocols

#### 2.2.1 HyperText Transfer Protocol (HTTP)

- **Port**: TCP 80
- **Description**: The foundation of data communication for the World Wide Web.
- **Use Case**: Transmitting hypertext documents and other data on the web.

#### 2.2.2 HyperText Transfer Protocol Secure (HTTPS)

- **Port**: TCP 443
- **Description**: An extension of HTTP that uses encryption to secure the data exchanged between a client and a server.
- **Use Case**: Secure web browsing, online banking, and other applications requiring secure data transfer.

#### 2.2.3 File Transfer Protocol (FTP)

- **Ports**: 
  - **Control**: TCP 21
  - **Data**: TCP 20
- **Description**: A standard network protocol used for the transfer of computer files between a client and a server on a network.
- **Use Case**: Uploading and downloading files from a remote server.

#### 2.2.4 Simple Mail Transfer Protocol (SMTP)

- **Port**: TCP 25
- **Description**: The protocol used for sending emails between servers.
- **Use Case**: Email transmission.

#### 2.2.5 Domain Name System (DNS)

- **Ports**: 
  - **Query**: UDP 53
  - **Zone Transfer**: TCP 53
- **Description**: Translates human-readable domain names to IP addresses.
- **Use Case**: Resolving domain names into IP addresses.

### 2.3 Network Layer Protocols

#### 2.3.1 Internet Protocol (IP)

- **Description**: The principal protocol in the Internet Protocol Suite for relaying datagrams across network boundaries.
- **Versions**: 
  - **IPv4**: 32-bit addressing, commonly used.
  - **IPv6**: 128-bit addressing, gradually replacing IPv4.

#### 2.3.2 Internet Control Message Protocol (ICMP)

- **Description**: Used by network devices to send error messages and operational information.
- **Common Use**: 
  - **Ping**: To test the reachability of a host.
- **Port**: ICMP does not use ports but is encapsulated within IP packets.

### 2.4 Data Link Layer Protocols

#### 2.4.1 Ethernet

- **Description**: The most common LAN technology, which defines wiring and signaling for the physical layer.
- **Standard**: IEEE 802.3
- **Frame Structure**: Includes MAC addresses for source and destination.

#### 2.4.2 Point-to-Point Protocol (PPP)

- **Description**: A data link layer protocol used to establish a direct connection between two nodes.
- **Common Use**: 
  - **Dial-up Internet access**.
  - **VPNs**.

### 2.5 Transport Layer Protocols

#### 2.5.1 Transmission Control Protocol (TCP)

- **Functionality**: Ensures reliable, ordered, and error-checked delivery of data between applications.
- **Common Use**: HTTP, HTTPS, FTP.

#### 2.5.2 User Datagram Protocol (UDP)

- **Functionality**: Provides a connectionless datagram service, prioritizing speed over reliability.
- **Common Use**: DNS, VoIP, video streaming.

### 2.6 Control Protocols

#### 2.6.1 Simple Network Management Protocol (SNMP)

- **Port**: UDP 161
- **Description**: An Internet-standard protocol for collecting and organizing information about managed devices on IP networks.
- **Use Case**: Network management.

#### 2.6.2 Dynamic Host Configuration Protocol (DHCP)

- **Ports**: 
  - **Server**: UDP 67
  - **Client**: UDP 68
- **Description**: Automatically assigns IP addresses and other network configuration parameters to devices on a network.
- **Use Case**: Automating the IP configuration process in large networks.

## 3. Network Standards

### 3.1 IEEE 802 Standards

#### 3.1.1 IEEE 802.3 (Ethernet)

- **Description**: The standard for wired local area networks (LANs).
- **Data Rate**: 
  - **10 Mbps** (Ethernet)
  - **100 Mbps** (Fast Ethernet)
  - **1 Gbps** (Gigabit Ethernet)
  - **10 Gbps** (10-Gigabit Ethernet)

#### 3.1.2 IEEE 802.11 (Wi-Fi)

- **Description**: The standard for wireless local area networks (WLANs).
- **Frequency Bands**:
  - **2.4 GHz**: Common for older Wi-Fi devices.
  - **5 GHz**: Used for faster, modern Wi-Fi devices.
  - **6 GHz**: Newer, less congested band for Wi-Fi 6E devices.

#### 3.1.3 IEEE 802.15 (Bluetooth)

- **Description**: The standard for short-range wireless communication.
- **Common Use**: 
  - **Personal Area Networks (PANs)**.
  - **Device pairing**: Mobile phones, laptops, etc.

### 3.2 IETF Standards

#### 3.2.1 RFC Documents

- **Description**: Request for Comments (RFC) documents define standards for internet protocols and technologies.
- **Examples**:
  - **RFC 791**: IPv4.
  - **RFC 2460**: IPv6.
  - **RFC 793**: TCP.

### 3.3 ISO Standards

#### 3.3.1 ISO/IEC 7498 (OSI Model)

- **Description**: Defines the seven-layer OSI model, which is used to understand and design network protocols.
- **Layers**:
  1. Physical
  2. Data Link
  3. Network
  4. Transport
  5. Session
  6. Presentation
  7. Application

### 3.4 ITU Standards

#### 3.4.1 ITU-T X.25

- **Description**: An early standard for packet-switched networks.
- **Use Case**: Frame Relay and ATM networks, precursor to modern IP networks.

## 4. Use Cases of Protocols and Standards

Protocols and standards are used in various scenarios, from global internet communication to private corporate networks. Understanding these protocols and standards is crucial for network design, troubleshooting, and ensuring interoperability between devices and systems.

## 5. Conclusion

This document has covered key network protocols and standards, including the ports commonly associated with these protocols. For anyone involved in networking, from engineers to IT administrators, a detailed understanding of these concepts is essential for managing and optimizing network performance.
