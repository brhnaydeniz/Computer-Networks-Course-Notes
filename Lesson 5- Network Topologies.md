**[TR](#tr) | [EN](#en)**

<a name="tr"></a>
# Ağ Topolojileri

Bu derste, ağ topolojilerinin ne olduğunu, nasıl çalıştıklarını, avantajlarını ve dezavantajlarını öğreneceksiniz. Ağ topolojisi, bir ağın fiziksel veya mantıksal düzenini ifade eder ve ağın performansı ile yönetimini doğrudan etkiler.

## İçindekiler

1. [Ağ Topolojilerinin Tanımı](#topoloji-tanimi)
2. [Ağ Topolojisi Türleri](#topoloji-turleri)
   - [Yıldız Topolojisi](#yildiz-topoloji)
   - [Halka Topolojisi](#halka-topoloji)
   - [Bus Topolojisi](#bus-topoloji)
   - [Mesh Topolojisi](#mesh-topoloji)
   - [Ağaç (Tree) Topolojisi](#agac-topoloji)
3. [Ağ Topolojilerinin Avantajları ve Dezavantajları](#avantaj-dezavantaj)

---

<a name="topoloji-tanimi"></a>
## 1. Ağ Topolojilerinin Tanımı

Ağ topolojisi, ağ cihazlarının ve bağlantılarının düzenlenme biçimidir. Topoloji, ağın nasıl yapılandırıldığını ve veri iletim yollarını belirler. Ağ topolojileri, fiziksel (donanım yerleşimi) veya mantıksal (veri akışı) olabilir.

![Ağ Topolojileri](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRZgXaRr_krPgMQWcWmdf17TlfmRPWrBk_L7_SxXgNaASkV31Nv3wLuUVU&s=10)

<a name="topoloji-turleri"></a>
## 2. Ağ Topolojisi Türleri

### [Yıldız Topolojisi](#yildiz-topoloji)

Yıldız topolojisinde tüm cihazlar merkezi bir düğüme (hub veya switch) bağlıdır. Veri, merkez düğüm üzerinden iletilir.

#### Avantajları:
- Kolay kurulum ve yönetim.
- Bir cihaz arızalandığında ağın geri kalanı etkilenmez.

#### Dezavantajları:
- Merkezi düğüm arızalanırsa tüm ağ çalışmaz hale gelir.
- Yüksek kablo maliyeti.

![Yıldız Topolojisi](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1V3Jhnqh0Guc7utdLaDGEfKGofO-tpIz1e6jQ_I1S7HjL8pGh_DL_yj4&s=10)

### [Halka Topolojisi](#halka-topoloji)

Halka topolojisinde her cihaz, bir önceki ve bir sonraki cihazla doğrudan bağlantılıdır, böylece halka şeklinde bir yapı oluşturur.

#### Avantajları:
- Veri, belirli bir yönde dolaşır ve çarpışma riski azalır.
- Basit veri iletim yöntemi.

#### Dezavantajları:
- Bir cihaz arızalandığında tüm ağ etkilenir.
- Sorun tespiti ve çözümü zordur.

![Halka Topolojisi](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJHJoKFHbk9f_w8cUQFr53HN_iXum9zUuSJJYuYAO8XQ0_XGvLTa47cR5g&s=10)

### [Bus Topolojisi](#bus-topoloji)

Bus topolojisinde tüm cihazlar ortak bir iletim hattına (bus) bağlanır. Veri, bu ortak hat üzerinden iletilir.

#### Avantajları:
- Az kablo gerektirir ve ekonomik maliyeti düşüktür.
- Kolay kurulum.

#### Dezavantajları:
- Ortak hat arızalandığında tüm ağ çalışmaz hale gelir.
- Ağ genişledikçe performans düşer.

![Bus Topolojisi](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFedcE2fVb90zcPcJOrUEoMSHx9FmK-JOaIBkFvRCRQvE8PMrKGOZ7lWux&s=10)

### [Mesh Topolojisi](#mesh-topoloji)

Mesh topolojisinde her cihaz, diğer tüm cihazlarla doğrudan bağlantılıdır. Bu, yüksek düzeyde yedeklilik sağlar.

#### Avantajları:
- Yüksek güvenilirlik ve hata toleransı.
- Verimli veri iletimi ve yük dengeleme.

#### Dezavantajları:
- Yüksek kurulum maliyeti.
- Karmaşık yapı ve yönetim zorluğu.

![Mesh Topolojisi](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR1SO3rx0TW4BOi11xPVXojLOy0MTmpHBQlzQ&usqp=CAU)

### [Ağaç (Tree) Topolojisi](#agac-topoloji)

Ağaç topolojisi, yıldız topolojilerinin hiyerarşik bir yapıda birleşmesiyle oluşur. Bu yapı, büyük ağlarda yaygındır.

#### Avantajları:
- Kolay genişletilebilir.
- Hiyerarşik yapı, kolay yönetim sağlar.

#### Dezavantajları:
- Ana hat arızalandığında tüm ağ etkilenir.
- Karmaşık yapı ve yüksek kablo maliyeti.

![Ağaç Topolojisi](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSwII8eBsB4hLnS47V7CrumrhW_0TqHeSFBXLO0bl5XSCvBDZmr-fDYNNM&s=10)

<a name="avantaj-dezavantaj"></a>
## 3. Ağ Topolojilerinin Avantajları ve Dezavantajları

Her ağ topolojisinin kendine özgü avantajları ve dezavantajları vardır. Aşağıda bu özelliklerin özet tablosunu bulabilirsiniz:

| Topoloji       | Avantajları                                      | Dezavantajları                                    |
| -------------- | ------------------------------------------------ | ------------------------------------------------- |
| Yıldız         | Kolay kurulum, bir arıza diğerlerini etkilemez   | Merkezi düğüm arızalanırsa tüm ağ çalışmaz        |
| Halka          | Veri çarpışması azalır, basit veri iletimi       | Bir cihaz arızalanırsa tüm ağ etkilenir           |
| Bus            | Ekonomik, kolay kurulum                          | Ortak hat arızalandığında tüm ağ çalışmaz, performans düşer |
| Mesh           | Yüksek güvenilirlik, verimli veri iletimi        | Yüksek kurulum maliyeti, karmaşık yapı            |
| Ağaç           | Kolay genişletilebilir, hiyerarşik yönetim       | Ana hat arızalanırsa tüm ağ etkilenir, yüksek kablo maliyeti |

---

Bu derste, ağ topolojilerinin temel prensiplerini, avantajlarını ve dezavantajlarını öğrendiniz. Daha fazla bilgi ve uygulama için diğer derslerimize göz atabilirsiniz.

<a name="en"></a>
# Network Topologies

In this lesson, you will learn what network topologies are, how they work, their advantages, and their disadvantages. A network topology refers to the physical or logical arrangement of a network and directly impacts the network's performance and management.

## Contents

1. [Definition of Network Topologies](#topology-definition)
2. [Types of Network Topologies](#topology-types)
   - [Star Topology](#star-topology)
   - [Ring Topology](#ring-topology)
   - [Bus Topology](#bus-topology)
   - [Mesh Topology](#mesh-topology)
   - [Tree Topology](#tree-topology)
3. [Advantages and Disadvantages of Network Topologies](#advantages-disadvantages)

---

<a name="topology-definition"></a>
## 1. Definition of Network Topologies

A network topology is the arrangement of a network's devices and connections. Topology determines how the network is structured and the data transmission paths. Network topologies can be physical (hardware layout) or logical (data flow).

![Network Topologies](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRZgXaRr_krPgMQWcWmdf17TlfmRPWrBk_L7_SxXgNaASkV31Nv3wLuUVU&s=10)

<a name="topology-types"></a>
## 2. Types of Network Topologies

### [Star Topology](#star-topology)

In a star topology, all devices are connected to a central node (hub or switch). Data is transmitted through the central node.

#### Advantages:
- Easy to install and manage.
- A failure in one device does not affect the rest of the network.

#### Disadvantages:
- If the central node fails, the entire network goes down.
- High cable cost.

![Star Topology](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1V3Jhnqh0Guc7utdLaDGEfKGofO-tpIz1e6jQ_I1S7HjL8pGh_DL_yj4&s=10)

### [Ring Topology](#ring-topology)

In a ring topology, each device is connected directly to the previous and next device, forming a circular layout.

#### Advantages:
- Data travels in a specific direction, reducing collision risk.
- Simple data transmission method.

#### Disadvantages:
- If one device fails, the entire network is affected.
- Troubleshooting and fixing issues are challenging.

![Ring Topology](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJHJoKFHbk9f_w8cUQFr53HN_iXum9zUuSJJYuYAO8XQ0_XGvLTa47cR5g&s=10)

### [Bus Topology](#bus-topology)

In a bus topology, all devices are connected to a common transmission line (bus). Data is transmitted over this shared line.

#### Advantages:
- Requires less cable, making it cost-effective.
- Easy to install.

#### Disadvantages:
- If the common line fails, the entire network goes down.
- Performance decreases as the network expands.

![Bus Topology](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFedcE2fVb90zcPcJOrUEoMSHx9FmK-JOaIBkFvRCRQvE8PMrKGOZ7lWux&s=10)

### [Mesh Topology](#mesh-topology)

In a mesh topology, each device is directly connected to every other device. This provides a high level of redundancy.

#### Advantages:
- High reliability and fault tolerance.
- Efficient data transmission and load balancing.

#### Disadvantages:
- High installation cost.
- Complex structure and management.

![Mesh Topology](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR1SO3rx0TW4BOi11xPVXojLOy0MTmpHBQlzQ&usqp=CAU)

### [Tree Topology](#tree-topology)

A tree topology combines star topologies in a hierarchical structure. This layout is common in large networks.

#### Advantages:
- Easily scalable.
- Hierarchical structure simplifies management.

#### Disadvantages:
- If the main line fails, the entire network is affected.
- High cable cost and complex structure.

![Tree Topology](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSwII8eBsB4hLnS47V7CrumrhW_0TqHeSFBXLO0bl5XSCvBDZmr-fDYNNM&s=10)

<a name="advantages-disadvantages"></a>
## 3. Advantages and Disadvantages of Network Topologies

Each network topology has its unique advantages and disadvantages. Below is a summary table of these features:

| Topology       | Advantages                                       | Disadvantages                                   |
| -------------- | ------------------------------------------------ | ----------------------------------------------- |
| Star           | Easy to install, one failure doesn't affect others | Central node failure takes down the entire network |
| Ring           | Reduces data collision, simple data transmission | One device failure affects the entire network   |
| Bus            | Cost-effective, easy to install                  | Common line failure takes down the entire network, performance decreases |
| Mesh           | High reliability, efficient data transmission    | High installation cost, complex structure       |
| Tree           | Easily scalable, hierarchical management         | Main line failure affects the entire network, high cable cost |

---

In this lesson, you have learned the basic principles of network topologies, their advantages, and disadvantages. For more information and practice, check out our other lessons.
