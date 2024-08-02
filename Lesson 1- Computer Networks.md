# Bilgisayar Ağlarına Giriş / Introduction to Computer Networks

**[TR](#tr) | [EN](#en)**

---

<a name="tr"></a>
## TR: Bilgisayar Ağlarına Giriş

**Merhaba ve hoş geldiniz!**

Bu derste, bilgisayar ağlarının temellerini öğreneceğiz. Bilgisayar ağları, günümüzün dijital dünyasında hayati bir rol oynar. İnternete bağlanmaktan, verileri paylaşmaya ve iletişim kurmaya kadar birçok günlük işimizi ağlar sayesinde yapıyoruz. Bu derste, ağların nasıl çalıştığını, temel bileşenlerini ve ağ yönetiminin önemini anlayacaksınız.

### 1. Bilgisayar Ağlarının Tanımı

Bilgisayar ağları, iki veya daha fazla bilgisayarın ve diğer cihazların birbiriyle iletişim kurmasını sağlayan sistemlerdir. Bu ağlar, veri paylaşımı, kaynak kullanımı ve iletişim gibi amaçlarla kullanılır. Ağlar, çeşitli cihazlar arasında veri alışverişini ve kaynak paylaşımını mümkün kılar.

![Bilgisayar Ağı](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3w0rnqZY5g2nmllYlcUietPwmYCzOHEBoTqMnKRmryr8rfcWK5zi0LPSC&s=10)

 ### 2. Ağ Türleri
 
 Ağlar, kapsadıkları alanlara göre isimlendirilir;

- **Yerel Alan Ağı (LAN):** Sınırlı bir alanda (örneğin, bir bina veya kampüs) bulunan cihazları birbirine bağlar.
- **Geniş Alan Ağı (WAN):** Birbirinden uzak coğrafi konumlarda bulunan cihazları bağlar. İnternet, en büyük WAN örneğidir.
- **Metropol Alan Ağı (MAN):** Bir şehir veya büyük bir yerleşim yeri gibi daha geniş alanları kapsar.
- **Kişisel Alan Ağı (PAN):** Kişisel cihazlar arasında veri aktarımı sağlar, örneğin, bilgisayar ve akıllı telefonlar arasındaki Bluetooth bağlantısı.
- **Kampüs Alan Ağı (CAN):** Bir üniversite kampüsü veya büyük bir kurumsal kampüs gibi birden fazla bina ve lokasyonu birbirine bağlayan ağ türüdür.

![Ağ Türleri](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRxu-Rmqp1E7m5lbfO_G3f9NnLBg9drkeqT-smhBA5vOI2doDXIbg8ZBp31&s=10)

### 3. Ağ Topolojileri

Ağ topolojisi, ağın fiziksel veya mantıksal düzenini ifade eder. Başlıca ağ topolojileri şunlardır:

- **Yıldız Topolojisi:** Tüm cihazlar merkezi bir noktaya bağlanır.
- **Halka Topolojisi:** Cihazlar bir halka şeklinde bağlanır.
- **Bus Topolojisi:** Tüm cihazlar ortak bir hat üzerinde bağlanır.
- **Mesh Topolojisi:** Her cihaz, diğer cihazlarla doğrudan bağlantı kurar.

![Ağ Topolojileri](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRM-MYArnJj6mtUheA45qOpmvsE0S_HVX4QTclKi9MkFpk9NR95vdcDgdA&s=10)

### 4. OSI ve TCP/IP Modelleri

Ağ iletişiminin standartlarını ve işleyişini anlamak için iki temel model kullanılır:

#### OSI Modeli (Open Systems Interconnection)

Yedi katmandan oluşur ve her katman, ağ iletişiminin belirli bir yönünü ele alır.
  - Fiziksel Katman
  - Veri Bağlantı Katmanı
  - Ağ Katmanı
  - Taşıma Katmanı
  - Oturum Katmanı
  - Sunum Katmanı
  - Uygulama Katmanı

![OSI Modeli](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkVodcX7K1_DUeMnKtn7KtJI_wHk1ltF282gtqZf3bOMHrAALbZ_3-Eto&s=10)

#### TCP/IP Modeli

İnternetin temelini oluşturan dört katmanlı bir modeldir.
  - Ağ Erişim Katmanı
  - İnternet Katmanı
  - Taşıma Katmanı
  - Uygulama Katmanı

![TCP/IP Modeli](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT70ZApekEeRWXYd506X85_b6AA3IqqYMFItfuOFEXFuOXYs6QgVF9FTm4J&s=10)

### 5. Temel Ağ Bileşenleri

Ağlar, çeşitli donanım ve yazılım bileşenlerinden oluşur. Temel bileşenler şunlardır:

- **Yönlendiriciler (Routers):** Farklı ağlar arasında veri paketlerini yönlendirir.
- **Anahtarlar (Switches):** Aynı ağdaki cihazlar arasında veri iletimini sağlar.
- **Erişim Noktaları (Access Points):** Kablosuz cihazların ağa bağlanmasını sağlar.
- **Tekrarlayıcılar (Repeaters):** Zayıflayan sinyalleri yeniden güçlendirir ve iletim mesafesini artırır.
- **Hub:** Birden fazla cihazı aynı ağda toplar ve verileri tüm portlara ileterek cihazların iletişim kurmasını sağlar.
- **Köprüler (Bridges):** İki veya daha fazla ağ segmentini birbirine bağlar ve veri trafiğini yönlendirir.
- **Ağ Geçidi (Gateway):** Farklı protokoller arasında veri dönüştürmesi yaparak ağlar arasında iletişimi sağlar.
- **Ağ Kabloları:** Cihazlar arasındaki fiziksel bağlantıları sağlar.

#### Fiziksel Aktarım Birimleri

- **Kablolar:**
  - **Bakır Kablolar:**
    - **Çift Bükümlü Kablolar (Twisted Pair):** İki tel çiftinin bükülmesiyle oluşur ve genellikle veri iletiminde kullanılır. İki türü vardır:
      - **Korumalı Çift Bükümlü Kablolar (Shielded Twisted Pair - STP):** Elektromanyetik paraziti azaltmak için ek bir koruma tabakası içerir.
      - **Korumalı Olmayan Çift Bükümlü Kablolar (Unshielded Twisted Pair - UTP):** Ek koruma tabakası bulunmayan, daha yaygın kullanılan kablo türüdür.
  - **Fiber Optik Kablolar:** Işık sinyalleri kullanarak veri iletimini sağlar ve yüksek hızda veri aktarımı için kullanılır.


![Ağ Bileşenleri](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRdwdTcnv8VtDkySZMDLjiyoUfkfv20EiyxWpPp46HUQiDSElbxRsedlDk&s=10)

### 6. IP Adresleme ve Alt Ağlar

- **IP Adresleri:** Her cihazın ağa bağlanabilmesi için benzersiz bir IP adresine ihtiyacı vardır. IPv4 ve IPv6 olmak üzere iki tür IP adresleme sistemi vardır.
- **Alt Ağlar:** Büyük ağları daha küçük parçalara ayırarak yönetimi kolaylaştırır ve ağ performansını artırır.

![IP Adresleme](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbdbPiE0bR_l91GFZU2U-Lxa9zDmNmFo3LxZshncUfyMkUjdpc2n_3Xq_B&s=10)


<a name="en"></a>
## EN: Introduction to Computer Networks

**Hello and welcome!**

In this lesson, we will learn the fundamentals of computer networks. Computer networks play a crucial role in today's digital world. From connecting to the internet to sharing data and communicating, we rely on networks for many daily tasks. In this lesson, you will understand how networks work, their basic components, and the importance of network management.

### 1. Definition of Computer Networks

Computer networks are systems that allow two or more computers and other devices to communicate with each other. These networks are used for data sharing, resource utilization, and communication. Networks enable data exchange and resource sharing among various devices.

![Computer Network](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3w0rnqZY5g2nmllYlcUietPwmYCzOHEBoTqMnKRmryr8rfcWK5zi0LPSC&s=10)

### 2. Types of Networks

- **Local Area Network (LAN):** Connects devices within a limited area (e.g., a building or campus).
- **Wide Area Network (WAN):** Connects devices located in different geographical locations. The internet is the largest WAN example.
- **Metropolitan Area Network (MAN):** Covers larger areas such as a city or large town.
- **Personal Area Network (PAN):** Allows data transfer between personal devices, such as the Bluetooth connection between a computer and a smartphone.
- **Campus Area Network (CAN):** Connects multiple buildings and locations within a university campus or large corporate campus.

![Network Types](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRxu-Rmqp1E7m5lbfO_G3f9NnLBg9drkeqT-smhBA5vOI2doDXIbg8ZBp31&s=10)

### 3. Network Topologies

Network topology refers to the physical or logical arrangement of a network. The main network topologies are:

- **Star Topology:** All devices are connected to a central point.
- **Ring Topology:** Devices are connected in a circular arrangement.
- **Bus Topology:** All devices are connected along a single line.
- **Mesh Topology:** Each device is connected directly to every other device.

![Network Topologies](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRM-MYArnJj6mtUheA45qOpmvsE0S_HVX4QTclKi9MkFpk9NR95vdcDgdA&s=10)

### 4. OSI and TCP/IP Models

To understand the standards and operation of network communication, two primary models are used:

#### OSI Model (Open Systems Interconnection)

It consists of seven layers, with each layer addressing a specific aspect of network communication.
  - Physical Layer
  - Data Link Layer
  - Network Layer
  - Transport Layer
  - Session Layer
  - Presentation Layer
  - Application Layer

![OSI Model](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkVodcX7K1_DUeMnKtn7KtJI_wHk1ltF282gtqZf3bOMHrAALbZ_3-Eto&s=10)

#### TCP/IP Model

A four-layered model that forms the basis of the internet.
  - Network Access Layer
  - Internet Layer
  - Transport Layer
  - Application Layer

![TCP/IP Model](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT70ZApekEeRWXYd506X85_b6AA3IqqYMFItfuOFEXFuOXYs6QgVF9FTm4J&s=10)

### 5. Basic Network Components

Networks consist of various hardware and software components. The basic components are:

- **Routers:** Direct data packets between different networks.
- **Switches:** Facilitate data transmission between devices within the same network.
- **Access Points:** Allow wireless devices to connect to the network.
- **Repeaters:** Amplify weakened signals to extend transmission distance.
- **Hub:** Connects multiple devices on the same network and broadcasts data to all ports, allowing devices to communicate.
- **Bridges:** Connect two or more network segments and direct data traffic between them.
- **Gateways:** Facilitate communication between networks with different protocols by performing data conversion.

- **Network Cables:** Provide physical connections between devices.

#### Physical Transmission Units

- **Cables:**
  - **Copper Cables:**
    - **Twisted Pair Cables:** Consist of pairs of twisted wires and are commonly used for data transmission. There are two types:
      - **Shielded Twisted Pair (STP):** Includes an additional shielding layer to reduce electromagnetic interference.
      - **Unshielded Twisted Pair (UTP):** Does not have additional shielding and is more commonly used.
  - **Fiber Optic Cables:** Use light signals for data transmission and are used for high-speed data transfer.


![Network Components](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRdwdTcnv8VtDkySZMDLjiyoUfkfv20EiyxWpPp46HUQiDSElbxRsedlDk&s=10)

### 6. IP Addressing and Subnets

- **IP Addresses:** Each device needs a unique IP address to connect to a network. There are two types of IP addressing systems: IPv4 and IPv6.
- **Subnets:** Divide large networks into smaller, more manageable segments, enhancing network performance.

![IP Addressing](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbdbPiE0bR_l91GFZU2U-Lxa9zDmNmFo3LxZshncUfyMkUjdpc2n_3Xq_B&s=10)

---

With this basic knowledge, you will understand how computer networks work and their general structure. In the following lessons, we will delve deeper into each topic and reinforce your knowledge with practical applications.

If you have any questions or need more information on any topic, please feel free to ask. I wish you all a productive and successful lesson!
