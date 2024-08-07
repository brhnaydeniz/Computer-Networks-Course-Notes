**[TR](#tr) | [EN](#en)**

<a name="tr"></a>

# Ağ Cihazları Dersi

**Merhaba ve hoş geldiniz!**

Bu derste, ağ cihazlarını detaylı bir şekilde inceleyeceğiz. Ağ cihazları, ağlar arasındaki veri iletişimini ve bağlantıyı sağlayan donanım bileşenleridir. Her bir cihazın rolü, ağın verimli ve güvenli bir şekilde çalışması için kritik öneme sahiptir. Hangi cihazın hangi katmanda çalıştığını ve hangi protokolleri kullandığını da ele alacağız.

## 1. Tekrarlayıcı (Repeater)

**Repeater**, zayıflayan sinyalleri güçlendirerek daha uzun mesafelere ulaşmasını sağlar. Fiziksel katmanda çalışır ve veriyi yeniden iletmekten başka bir işlevi yoktur. Repeater, herhangi bir adresleme protokolü kullanmaz.

![Repeater](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJ_Bzj-dNYwgqfq3hTwDsVEiWXDH0yHVljHQ&usqp=CAU)

**Katman:** Fiziksel Katman  
**Protokol:** Yok  
**Adresleme:** Yok

## 2. Dağıtıcı (Hub)

**Hub**, ağdaki tüm cihazlara veri paketlerini ileten basit bir cihazdır. Veri paketleri, hub'a bağlı tüm cihazlara gönderilir. Bu, ağdaki trafiği artırabilir ve güvenlik risklerine yol açabilir. Fiziksel katmanda çalışır.

![Hub](https://thestudygenius.com/wp-content/uploads/2020/08/What-is-hub-in-networking.gif)

**Katman:** Fiziksel Katman  
**Protokol:** Yok  
**Adresleme:** Yok

## 3. Köprü (Bridge)

**Bridge**, iki veya daha fazla ağ segmentini birbirine bağlar. Veri paketlerini MAC adreslerine göre yönlendirir ve veri trafiğini filtreler. Veri bağlantı katmanında çalışır.

![Bridge](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTrRApJj2KqR-5i0vjOa7AD02IJjElajy5RzjgKJK1f-371oQv2uxJlhAA&s=10)

**Katman:** Veri Bağlantı Katmanı  
**Protokol:** Ethernet, Wi-Fi  
**Adresleme:** MAC Adresi

## 4. Anahtar (Switch)

**Switch**, ağdaki cihazlar arasında veri paketlerini daha verimli bir şekilde yönlendirir. Switch, MAC adreslerini kullanarak veriyi doğru hedefe gönderir. Veri bağlantı katmanında çalışır ve ağ trafiğini azaltır.

![Switch](https://azizozbek.ch/wp-content/uploads/2018/02/Work-Principl-of-Switch.gif)

**Katman:** Veri Bağlantı Katmanı  
**Protokol:** Ethernet, VLAN, STP  
**Adresleme:** MAC Adresi

## 5. Yönlendirici (Router)

**Router**, farklı ağlar arasında veri paketlerini yönlendirir. IP adreslerine göre çalışır ve veri paketlerinin en verimli yoldan iletilmesini sağlar. Ağ katmanında çalışır.

![Router](https://static.javatpoint.com/tutorial/computer-network/images/switch-vs-router5.png)

**Katman:** Ağ Katmanı  
**Protokol:** IP, ICMP, OSPF, BGP  
**Adresleme:** IP Adresi

## 6. Geçit (Gateway)

**Gateway**, farklı protokoller kullanan ağlar arasında veri iletişimini sağlar. Hem donanım hem de yazılım olarak işlev görebilir ve veriyi bir formattan diğerine çevirir. Ağ katmanında ve üst katmanlarda çalışabilir.

![Gateway](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRookYYYB0muF5IJ6AFjRkaSvPwtLpfvLnvGCTVSE5fnhLtGXcDA8zDf9Y&s=10)

**Katman:** Ağ Katmanı ve Üst Katmanlar  
**Protokol:** Çeşitli protokoller (IP, HTTP, FTP)  
**Adresleme:** IP Adresi, Protokol Bağımlı

## 7. Erişim Noktası (Access Point)

**Access Point**, kablosuz cihazların ağa bağlanmasını sağlar. Kablosuz ağlar için kritik öneme sahiptir ve veriyi kablolu ağlara iletir. Veri bağlantı katmanında çalışır.

![Access Point](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSUjfmU5uuVnp2vn9E4qDPqkm1FOtrdGlSPKLenUUplCBWas67g0Pff-ArI&s=10)

**Katman:** Veri Bağlantı Katmanı  
**Protokol:** Wi-Fi  
**Adresleme:** MAC Adresi

## 8. Ağ Kabloları

**Ağ Kabloları**, cihazlar arasındaki fiziksel bağlantıları sağlar. Temel iki tür kablo vardır:

- **Bakır Kablolar:** Çift bükümlü korumalı (STP) ve korumasız (UTP) kablolar içerir.
  - **Çift Bükümlü Korumalı (STP):** Elektromanyetik paraziti azaltır.
  - **Çift Bükümlü Korumasız (UTP):** Daha yaygın olarak kullanılır ve maliyet olarak daha uygundur.

![Copper Cables](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsXDXu90NCjGcxmri0YcwDeA-dSTnx07yMUJRecoJMIZuGOzvmtmrkSAU&s=10)

- **Fiber Optik Kablolar:** Işık sinyalleri kullanarak veri iletir ve uzun mesafelerde yüksek hızda veri aktarımı sağlar.

![Fiber Optic Cables](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQqKDt3Wxqz_n5jsDYLxTVRtnBIuSv_YzvBuPFWbR8kgQW99aof6w09hicf&s=10)

## 9. Fiziksel Aktarım Birimleri

**Fiziksel Aktarım Birimleri**, ağ cihazlarının ve kablolarının sonlandırılmasını ve bağlanmasını sağlar. Kabloların doğru şekilde sonlandırılması, veri iletiminde kesintisiz ve güvenilir bağlantılar sağlar.

---

Bu cihazlar, ağların verimli ve güvenli bir şekilde çalışmasını sağlar. Her bir cihazın farklı işlevleri ve kullanım alanları vardır. 

<a name="en"></a>

# Network Devices Lesson

**Hello and welcome!**

In this lesson, we will examine network devices in detail. Network devices are hardware components that facilitate data communication and connectivity between networks. Each device plays a critical role in ensuring the efficient and secure operation of the network. We will also cover which layer each device operates on and the protocols they use.

## 1. Repeater

A **Repeater** amplifies weakened signals to extend their reach. It operates at the physical layer and only retransmits data. A repeater does not use any addressing protocol.

![Repeater](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJ_Bzj-dNYwgqfq3hTwDsVEiWXDH0yHVljHQ&usqp=CAU)

**Layer:** Physical Layer  
**Protocol:** None  
**Addressing:** None

## 2. Hub

A **Hub** is a simple device that transmits data packets to all devices connected to it. This can increase traffic on the network and pose security risks. It operates at the physical layer.

![Hub](https://thestudygenius.com/wp-content/uploads/2020/08/What-is-hub-in-networking.gif)

**Layer:** Physical Layer  
**Protocol:** None  
**Addressing:** None

## 3. Bridge

A **Bridge** connects two or more network segments. It filters data traffic and directs data packets based on MAC addresses. It operates at the data link layer.

![Bridge](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTrRApJj2KqR-5i0vjOa7AD02IJjElajy5RzjgKJK1f-371oQv2uxJlhAA&s=10)

**Layer:** Data Link Layer  
**Protocol:** Ethernet, Wi-Fi  
**Addressing:** MAC Address

## 4. Switch

A **Switch** directs data packets more efficiently between devices on the network. It uses MAC addresses to send data to the correct destination. It operates at the data link layer and reduces network traffic.

![Switch](https://azizozbek.ch/wp-content/uploads/2018/02/Work-Principl-of-Switch.gif)

**Layer:** Data Link Layer  
**Protocol:** Ethernet, VLAN, STP  
**Addressing:** MAC Address

## 5. Router

A **Router** directs data packets between different networks. It works based on IP addresses and ensures data packets are transmitted via the most efficient route. It operates at the network layer.

![Router](https://static.javatpoint.com/tutorial/computer-network/images/switch-vs-router5.png)

**Layer:** Network Layer  
**Protocol:** IP, ICMP, OSPF, BGP  
**Addressing:** IP Address

## 6. Gateway

A **Gateway** facilitates data communication between networks using different protocols. It can function as both hardware and software, converting data from one format to another. It can operate at the network layer and above.

![Gateway](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRookYYYB0muF5IJ6AFjRkaSvPwtLpfvLnvGCTVSE5fnhLtGXcDA8zDf9Y&s=10)

**Layer:** Network Layer and Above  
**Protocol:** Various protocols (IP, HTTP, FTP)  
**Addressing:** IP Address, Protocol Dependent

## 7. Access Point

An **Access Point** allows wireless devices to connect to the network. It is crucial for wireless networks and transmits data to wired networks. It operates at the data link layer.

![Access Point](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSUjfmU5uuVnp2vn9E4qDPqkm1FOtrdGlSPKLenUUplCBWas67g0Pff-ArI&s=10)

**Layer:** Data Link Layer  
**Protocol:** Wi-Fi  
**Addressing:** MAC Address

## 8. Network Cables

**Network Cables** provide physical connections between devices. There are two main types of cables:

- **Copper Cables:** Includes Shielded Twisted Pair (STP) and Unshielded Twisted Pair (UTP) cables.
  - **Shielded Twisted Pair (STP):** Reduces electromagnetic interference.
  - **Unshielded Twisted Pair (UTP):** More commonly used and cost-effective.

![Copper Cables](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsXDXu90NCjGcxmri0YcwDeA-dSTnx07yMUJRecoJMIZuGOzvmtmrkSAU&s=10)

- **Fiber Optic Cables:** Transmit data using light signals, allowing high-speed data transfer over long distances.

![Fiber Optic Cables](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQqKDt3Wxqz_n5jsDYLxTVRtnBIuSv_YzvBuPFWbR8kgQW99aof6w09hicf&s=10)

## 9. Physical Transmission Units

**Physical Transmission Units** ensure the termination and connection of network devices and cables. Proper cable termination provides uninterrupted and reliable data transmission.

---

These devices ensure the efficient and secure operation of networks. Each device has different functions and areas of use. 
