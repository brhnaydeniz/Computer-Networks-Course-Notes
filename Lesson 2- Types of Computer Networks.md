**[TR](#tr) | [EN](#en)**

<a name="tr"></a>
# Ders: Bilgisayar Ağları Türleri

**Merhaba ve hoş geldiniz!**

Bu derste, beş ana ağ türünü detaylı bir şekilde inceleyeceğiz: Yerel Alan Ağı (LAN), Geniş Alan Ağı (WAN), Metropol Alan Ağı (MAN), Kampüs Alan Ağı (CAN), ve Kişisel Alan Ağı (PAN). Her bir ağ türünün teknik özelliklerini, bileşenlerini, topolojilerini ve protokollerini detaylı bir şekilde ele alacağız.

## 1. Yerel Alan Ağı (LAN)

### Tanım
Yerel Alan Ağı (LAN), genellikle bir bina veya kampüs içindeki cihazları birbirine bağlayan ağdır. LAN'lar, yüksek hızda veri transferi ve düşük gecikme süreleri sağlar.

### Temel Özellikler
- **Coğrafi Kapsama:** Sınırlı bir alanda, genellikle tek bir bina veya kampüs.
- **Hız:** Yüksek hızda veri transferi (10 Mbps – 10 Gbps).
- **Maliyet:** Genellikle düşük maliyetlidir.
- **Yönetim:** Kolay yönetim ve sorun giderimi.

### Bileşenler
- **Yönlendiriciler (Routers):** Cihazları birbirine bağlar.
- **Anahtarlar (Switches):** Veriyi cihazlar arasında yönlendirir.
- **Erişim Noktaları (Access Points):** Kablosuz bağlantı sağlar.
- **Ağ Kabloları:** Kablolu bağlantı sağlar.
- **Repeater:** Sinyal gücünü artırır.
- **Hub:** Birden fazla cihazın bağlantısını sağlar.
- **Bridge:** İki ağı birbirine bağlar.
- **Gateway:** Farklı ağ protokollerini birbirine bağlar.

### Topolojiler
- **Yıldız Topolojisi:** Merkezi anahtar ile tüm cihazlar bağlanır.
- **Bus Topolojisi:** Cihazlar ortak bir hat üzerinden bağlanır.
- **Halka Topolojisi:** Cihazlar bir halka şeklinde bağlanır.

### Protokoller
- **Ethernet:** IEEE 802.3 standardına dayanır.
- **Wi-Fi:** Kablosuz ağlar için IEEE 802.11 standardına dayanır.
- **Token Ring:** Veri iletimi için token kullanır.

![LAN](https://upload.wikimedia.org/wikipedia/commons/3/3d/Star_Topology.jpg)

## 2. Geniş Alan Ağı (WAN)

### Tanım
Geniş Alan Ağı (WAN), geniş coğrafi alanları kapsayan ve genellikle ülkeler veya kıtalar arasında veri iletimi sağlayan ağlardır. WAN'lar, genellikle internet bağlantısı için kullanılır.

### Temel Özellikler
- **Coğrafi Kapsama:** Ülkeler veya kıtalar arası geniş alan.
- **Hız:** Daha düşük hızda veri transferi (1 Mbps – 100 Gbps).
- **Maliyet:** Yüksek maliyetli olabilir.
- **Yönetim:** Karmaşık yönetim ve sorun giderimi.

### Bileşenler
- **Yönlendiriciler (Routers):** Büyük ölçekli yönlendirme sağlar.
- **Anahtarlar (Switches):** WAN içindeki trafiği yönetir.
- **Modemler:** İnternet bağlantısını sağlar.
- **Repeater:** Uzun mesafelerde sinyal güçlendirme sağlar.
- **Hub:** Ağ cihazlarının bağlantısını sağlar.
- **Bridge:** Farklı ağları bağlar.
- **Gateway:** Ağlar arasında veri alışverişini sağlar.

### Topolojiler
- **Yıldız Topolojisi:** Merkezi bir anahtar etrafında tüm cihazlar.
- **Bus Topolojisi:** Ortak bir hat üzerinden veri iletimi.
- **Halka Topolojisi:** Cihazlar bir halka şeklinde bağlanır.

### Protokoller
- **MPLS (Multi-Protocol Label Switching):** Etiket tabanlı yönlendirme sağlar.
- **ATM (Asynchronous Transfer Mode):** Sabit boyutlu hücrelerle veri iletimi yapar.
- **Frame Relay:** Veri paketlerini yönlendirir.

![WAN](https://upload.wikimedia.org/wikipedia/commons/9/98/Bus_network_topology_diagram.jpg)

## 3. Metropol Alan Ağı (MAN)

### Tanım
Metropol Alan Ağı (MAN), genellikle bir şehir veya büyük bir yerleşim alanı içinde cihazları ve ağları birbirine bağlayan geniş ölçekli ağlardır. MAN'lar, şehir içi ağlar için idealdir.

### Temel Özellikler
- **Coğrafi Kapsama:** Bir şehir veya büyük bir yerleşim alanı.
- **Hız:** Orta düzeyde veri transferi (10 Mbps – 1 Gbps).
- **Maliyet:** Orta düzeyde maliyet.
- **Yönetim:** Orta düzeyde yönetim ve sorun giderimi.

### Bileşenler
- **Yönlendiriciler (Routers):** Şehir içindeki ağları bağlar.
- **Anahtarlar (Switches):** Veriyi yönlendirir.
- **Fiber Optik Kablolar:** Yüksek hızda veri iletimi sağlar.
- **Modemler:** İnternet bağlantısını sağlar.
- **Repeater:** Sinyal güçlendirir.
- **Hub:** Bağlantı sağlar.
- **Bridge:** İki ağı bağlar.
- **Gateway:** Farklı ağ protokollerini bağlar.

### Topolojiler
- **Yıldız Topolojisi:** Merkezi bir anahtar etrafında cihazlar.
- **Bus Topolojisi:** Ortak bir hat üzerinden veri iletimi.
- **Halka Topolojisi:** Cihazlar halka şeklinde bağlanır.

### Protokoller
- **Metro Ethernet:** Şehir içindeki büyük ağları bağlar.
- **FDDI (Fiber Distributed Data Interface):** Yüksek hızda veri iletimi sağlar.

![MAN](https://upload.wikimedia.org/wikipedia/commons/2/2d/Metro-Ethernet.png)

## 4. Kampüs Alan Ağı (CAN)

### Tanım
Kampüs Alan Ağı (CAN), bir kampüs veya büyük bir eğitim kurumu gibi sınırlı bir coğrafi alan içinde bulunan ağları ifade eder. CAN'lar, büyük bir kampüste veri paylaşımı sağlar.

### Temel Özellikler
- **Coğrafi Kapsama:** Bir kampüs veya büyük bir bina.
- **Hız:** Yüksek hızda veri transferi (10 Mbps – 1 Gbps).
- **Maliyet:** Orta düzeyde maliyet.
- **Yönetim:** Orta düzeyde yönetim.

### Bileşenler
- **Yönlendiriciler (Routers):** Kampüs içindeki ağları bağlar.
- **Anahtarlar (Switches):** Veriyi yönlendirir.
- **Erişim Noktaları (Access Points):** Kablosuz bağlantı sağlar.
- **Ağ Kabloları:** Kablolu bağlantı sağlar.
- **Repeater:** Sinyal güçlendirir.
- **Hub:** Bağlantı sağlar.
- **Bridge:** İki ağı bağlar.
- **Gateway:** Farklı ağ protokollerini bağlar.

### Topolojiler
- **Yıldız Topolojisi:** Merkezi bir anahtar etrafında cihazlar.
- **Bus Topolojisi:** Ortak bir hat üzerinden veri iletimi.
- **Halka Topolojisi:** Cihazlar halka şeklinde bağlanır.

### Protokoller
- **Ethernet:** Yüksek hızda veri iletimi sağlar.
- **Wi-Fi:** Kablosuz bağlantı sağlar.

![CAN](https://upload.wikimedia.org/wikipedia/commons/6/66/Ethernet_1.jpg)

## 5. Kişisel Alan Ağı (PAN)

### Tanım
Kişisel Alan Ağı (PAN), bireysel cihazlar arasında veri aktarımını sağlayan ağları ifade eder. PAN'lar, kişisel kullanım için tasarlanmıştır.

### Temel Özellikler
- **Coğrafi Kapsama:** Kişisel cihazlar arasında kısa mesafe.
- **Hız:** Düşük ila orta düzeyde veri transferi (1 Mbps – 10 Mbps).
- **Maliyet:** Düşük maliyet.
- **Yönetim:** Basit yönetim.

### Bileşenler
- **Bluetooth:** Kablosuz cihazlar arasında veri aktarımı sağlar.
- **Kızılötesi (IR):** Kısa mesafelerde veri iletimi için kullanılır.
- **USB:** Kablolu veri aktarımı sağlar.

### Topolojiler
- **P2P (Peer-to-Peer):** Cihazlar doğrudan birbirine bağlanır.
- **Star Topolojisi:** Cihazlar bir merkez cihazla bağlanır.

### Protokoller
- **Bluetooth:** Kısa mesafelerde veri iletimi sağlar.
- **Infrared Data Association (IrDA):** Kızılötesi veri aktarımı sağlar.

![PAN](https://upload.wikimedia.org/wikipedia/commons/d/da/Bluetooth_Pan.jpg)

---

Bu ders, farklı ağ türlerinin teknik özelliklerini ve uygulama alanlarını anlamanızı sağlayacaktır. Her bir ağ türü hakkında derinlemesine bilgi edinerek, ağ tasarımı ve yönetimi konularında yetkinlik kazanabilirsiniz.

<a name="en"></a>
# Lesson: Types of Computer Networks

**Hello and welcome!**

In this lesson, we will explore five main types of networks in detail: Local Area Network (LAN), Wide Area Network (WAN), Metropolitan Area Network (MAN), Campus Area Network (CAN), and Personal Area Network (PAN). We will cover each network type’s technical features, components, topologies, and protocols in detail.

## 1. Local Area Network (LAN)

### Definition
A Local Area Network (LAN) is a network that connects devices within a limited geographical area, such as a single building or campus. LANs offer high-speed data transfer and low latency.

### Key Features
- **Geographic Coverage:** Limited to a single building or campus.
- **Speed:** High-speed data transfer (10 Mbps – 10 Gbps).
- **Cost:** Generally low cost.
- **Management:** Easy to manage and troubleshoot.

### Components
- **Routers:** Connect devices within the network.
- **Switches:** Directs data between devices.
- **Access Points:** Provides wireless connectivity.
- **Network Cables:** Provides wired connectivity.
- **Repeater:** Amplifies signal strength.
- **Hub:** Connects multiple devices.
- **Bridge:** Connects two networks.
- **Gateway:** Connects different network protocols.

### Topologies
- **Star Topology:** All devices are connected to a central switch.
- **Bus Topology:** Devices are connected along a common line.
- **Ring Topology:** Devices are connected in a circular fashion.

### Protocols
- **Ethernet:** Based on IEEE 802.3 standard.
- **Wi-Fi:** Based on IEEE 802.11 standard for wireless networks.
- **Token Ring:** Uses tokens for data transmission.

![LAN](https://upload.wikimedia.org/wikipedia/commons/3/3d/Star_Topology.jpg)

## 2. Wide Area Network (WAN)

### Definition
A Wide Area Network (WAN) covers large geographic areas and typically spans countries or continents. WANs are commonly used for internet connectivity.

### Key Features
- **Geographic Coverage:** Covers countries or continents.
- **Speed:** Lower data transfer speeds (1 Mbps – 100 Gbps).
- **Cost:** Can be high cost.
- **Management:** Complex management and troubleshooting.

### Components
- **Routers:** Provides large-scale routing.
- **Switches:** Manages traffic within the WAN.
- **Modems:** Provides internet connectivity.
- **Repeaters:** Amplifies signals over long distances.
- **Hub:** Connects network devices.
- **Bridge:** Connects different networks.
- **Gateway:** Facilitates data exchange between networks.

### Topologies
- **Star Topology:** Devices connect around a central hub.
- **Bus Topology:** Data is transmitted along a common line.
- **Ring Topology:** Devices are arranged in a ring.

### Protocols
- **MPLS (Multi-Protocol Label Switching):** Provides label-based routing.
- **ATM (Asynchronous Transfer Mode):** Uses fixed-size cells for data transfer.
- **Frame Relay:** Manages data packet routing.

![WAN](https://upload.wikimedia.org/wikipedia/commons/9/98/Bus_network_topology_diagram.jpg)

## 3. Metropolitan Area Network (MAN)

### Definition
A Metropolitan Area Network (MAN) connects devices and networks within a metropolitan area, such as a city or large campus. MANs are ideal for city-wide networks.

### Key Features
- **Geographic Coverage:** A city or large metropolitan area.
- **Speed:** Medium-speed data transfer (10 Mbps – 1 Gbps).
- **Cost:** Moderate cost.
- **Management:** Medium-level management and troubleshooting.

### Components
- **Routers:** Connects networks within the city.
- **Switches:** Directs data within the MAN.
- **Fiber Optic Cables:** Provides high-speed data transfer.
- **Modems:** Provides connectivity.
- **Repeater:** Amplifies signals.
- **Hub:** Connects network devices.
- **Bridge:** Links different networks.
- **Gateway:** Connects various protocols.

### Topologies
- **Star Topology:** Central switch connects all devices.
- **Bus Topology:** Common line used for data transmission.
- **Ring Topology:** Devices connected in a circular pattern.

### Protocols
- **Metro Ethernet:** Connects large city networks.
- **FDDI (Fiber Distributed Data Interface):** Provides high-speed data transfer.

![MAN](https://upload.wikimedia.org/wikipedia/commons/2/2d/Metro-Ethernet.png)

## 4. Campus Area Network (CAN)

### Definition
A Campus Area Network (CAN) is a network that connects devices and networks within a campus or large educational institution. CANs facilitate data sharing across large campuses.

### Key Features
- **Geographic Coverage:** A campus or large building.
- **Speed:** High-speed data transfer (10 Mbps – 1 Gbps).
- **Cost:** Moderate cost.
- **Management:** Medium-level management.

### Components
- **Routers:** Connects campus networks.
- **Switches:** Directs data traffic.
- **Access Points:** Provides wireless connectivity.
- **Network Cables:** Provides wired connectivity.
- **Repeater:** Amplifies signal strength.
- **Hub:** Connects network devices.
- **Bridge:** Links networks.
- **Gateway:** Connects different protocols.

### Topologies
- **Star Topology:** Devices connect around a central hub.
- **Bus Topology:** Common line used for data transmission.
- **Ring Topology:** Devices are connected in a ring.

### Protocols
- **Ethernet:** Provides high-speed data transfer.
- **Wi-Fi:** Provides wireless connectivity.

![CAN](https://upload.wikimedia.org/wikipedia/commons/6/66/Ethernet_1.jpg)

## 5. Personal Area Network (PAN)

### Definition
A Personal Area Network (PAN) is a network that connects personal devices within a short range. PANs are designed for individual use.

### Key Features
- **Geographic Coverage:** Short range between personal devices.
- **Speed:** Low to medium-speed data transfer (1 Mbps – 10 Mbps).
- **Cost:** Low cost.
- **Management:** Simple management.

### Components
- **Bluetooth:** Provides wireless data transfer between devices.
- **Infrared (IR):** Used for short-range data transfer.
- **USB:** Provides wired data transfer.

### Topologies
- **P2P (Peer-to-Peer):** Devices connect directly.
- **Star Topology:** Devices connect through a central hub.

### Protocols
- **Bluetooth:** Facilitates short-range data transfer.
- **Infrared Data Association (IrDA):** Provides infrared data transfer.

![PAN](https://upload.wikimedia.org/wikipedia/commons/d/da/Bluetooth_Pan.jpg)

---

This lesson will give you a comprehensive understanding of different network types, including their technical features and practical applications. With detailed information on each network type, you will be equipped to design and manage various types of networks effectively.
