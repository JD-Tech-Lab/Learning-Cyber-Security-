# 🌐 Network Topologies – Types and Explanation

## 📌 1️⃣ Bus Topology

### 📖 Description

Bus topology connects all devices to a single central cable called a backbone.

### 🖥️ Diagram

```
PC1 ---- PC2 ---- PC3 ---- PC4
          |
       Backbone Cable
```

### ⚙️ Working

* Data travels in both directions.
* Only one device can transmit at a time.
* Terminators are used at both ends.

### ✅ Advantages

* Low cost
* Easy to install
* Requires less cable

### ❌ Disadvantages

* If backbone fails → entire network fails
* Difficult troubleshooting
* Performance decreases with more devices

---

## 📌 2️⃣ Star Topology

### 📖 Description

All devices connect to a central switch or hub.

### 🖥️ Diagram

```
        PC1
         |
PC2 --- Switch --- PC3
         |
        PC4
         |
       Router
```

### ⚙️ Working

* Switch forwards data only to destination device.
* Most commonly used LAN topology.

### ✅ Advantages

* Easy troubleshooting
* Scalable
* Better performance

### ❌ Disadvantages

* Switch failure → entire network down
* More cable required

---

## 📌 3️⃣ Ring Topology

### 📖 Description

Each device connects to two other devices forming a circular structure.

### 🖥️ Diagram

```
PC1 ---- PC2
 |          |
PC4 ---- PC3
```

### ⚙️ Working

* Data travels in one direction (Token Passing).
* Each device acts as repeater.

### ✅ Advantages

* Equal access to network
* No data collision

### ❌ Disadvantages

* If one device fails → network affected
* Hard to reconfigure

---

## 📌 4️⃣ Mesh Topology

### 📖 Description

Every device connects to every other device.

### 🖥️ Diagram (Full Mesh Example)

```
PC1 ------ PC2
 |  \      /  |
 |    \    /   |
 |      \  /    |
PC3 ------ PC4
```

### ⚙️ Working

* Multiple paths between devices.
* High redundancy.

### ✅ Advantages

* Highly reliable
* No single point of failure
* Secure

### ❌ Disadvantages

* Very expensive
* Complex wiring

---

## 📌 5️⃣ Hybrid Topology

### 📖 Description

Combination of two or more topologies (Star + Bus, Star + Ring, etc.)

### 🖥️ Diagram (Star-Bus Example)

```
      PC1   PC2
        \   /
        Switch1
            |
      ------------- Backbone -------------
            |
        Switch2
        /     \
      PC3     PC4
```

### ⚙️ Working

* Combines advantages of multiple topologies.
* Used in large organizations.

### ✅ Advantages

* Flexible
* Scalable
* Reliable

### ❌ Disadvantages

* Complex design
* Expensive

---

# 🔐 Topology Comparison Table

| Topology | Cost   | Reliability | Scalability | Security |
| -------- | ------ | ----------- | ----------- | -------- |
| Bus      | Low    | Low         | Low         | Low      |
| Star     | Medium | High        | High        | Medium   |
| Ring     | Medium | Medium      | Low         | Medium   |
| Mesh     | High   | Very High   | Medium      | High     |
| Hybrid   | High   | High        | Very High   | High     |

---



