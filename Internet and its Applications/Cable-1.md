Here is the markdown version of the document based on the provided screenshots.

# Network Cables

**Learning Objectives**
By the end of this lesson, students should be able to:

*   Describe the basic structure of twisted-pair, coaxial and fibre-optic cables.
*   Compare their speed, maximum distance, cost and resistance to interference.
*   Suggest a suitable cable type for common networking scenarios (e.g. school LAN, building-to-building links).

**1. Introduction to Network Cables**
Computer networks use cables (transmission media) to carry data signals between devices.

Common wired network cables:

*   Twisted-pair cable (most common for Ethernet LANs)
*   Coaxial cable
*   Fibre-optic cable

When choosing a cable, we usually consider:

*   Data rate (maximum speed)
*   Maximum distance per segment
*   Resistance to electrical interference
*   Cost
*   Typical applications

---

**2. Overview of Common Cable Types**

**Table 1 Overview of Twisted-pair, Coaxial and Fibre-optic Cables**

| Cable type | Main transmission medium | Typical speed (for school level) | Typical max distance per segment | Interference resistance | Cost (relative) | Typical uses |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Twisted-pair** (UTP/STP) | Copper wires (4 twisted pairs) | 100 Mbps – 1 Gbps (Cat5e), up to 10 Gbps (Cat6/Cat6a) | About 100 m | Medium (higher with STP) | Low – medium | LAN connections: PC $\leftrightarrow$ switch, switch $\leftrightarrow$ router |
| **Coaxial** | Single copper core with shielding | Tens to hundreds of Mbps | A few hundred metres | Better than UTP | Medium | Cable TV, CCTV, some broadband links |
| **Fibre-optic** | Glass or plastic core (light) | 1 Gbps – 100+ Gbps | Up to many kilometres (single-mode) | Very high | High | Network backbone, building-to-building, ISP links |

*Figure 1: Cross-section diagram of twisted-pair Ethernet cable showing 4 twisted pairs inside an outer jacket.*

---

**3. Twisted-pair Cables (Ethernet)**

**3.1 Structure of Twisted-pair Cable**
*   Contains 4 pairs of insulated copper wires (8 wires in total).
*   Each pair is twisted to reduce electrical noise and crosstalk.
*   All pairs are covered by an outer plastic jacket.

Two main types:

**UTP (Unshielded Twisted Pair)**
- No extra metallic shielding
- Cheaper and widely used in offices and schools

**STP / FTP (Shielded / Foiled Twisted Pair)**
- Additional metal foil or braid used as shielding
- Better protection in environments with strong interference (e.g. factories)

*Figure 2: Photo or diagram comparing UTP and STP cables, showing extra shielding in STP.*

**3.2 Categories of Twisted-pair Cable**
Twisted-pair Ethernet cables are grouped into categories (Cat) according to performance.

**Table 2 Common Categories of Twisted-pair Cables**

| Category | Typical maximum data rate | Approx. maximum distance (at rated speed) | Typical use today |
| :--- | :--- | :--- | :--- |
| **Cat5e** | 1 Gbps | 100 m | Older but still common in homes/schools |
| **Cat6** | 1–10 Gbps | 100 m (1 Gbps), up to 55 m (10 Gbps) | Modern LANs, classroom networks |
| **Cat6a** | 10 Gbps | 100 m | High-speed links in server rooms |

---

**3.3 Advantages and Disadvantages of Twisted-pair**
*   **Advantages:**
    *   Relatively cheap and easy to install.
    *   Cables are flexible and easy to terminate with RJ-45 plugs.
    *   Sufficient speed for most office and school environments.
*   **Disadvantages:**
    *   Maximum segment length is typically 100 m.
    *   Copper cables are affected by electromagnetic interference, especially UTP with no shield.
    *   Performance decreases over very long distances.

**4. Coaxial Cable**

**4.1 Structure of Coaxial Cable**
*   Inner conductor – solid copper core wire carrying the signal.
*   Insulator (dielectric) – plastic or foam around the inner conductor.
*   Outer conductor (shield) – braided metal or foil acting as a shield and return path.
*   Outer jacket – protective plastic covering.

*Figure 3: Cross-section diagram of a coaxial cable with labels: inner conductor, insulator, outer conductor (braid), outer jacket.*

**4.2 Typical Uses of Coaxial Cable**
*   Cable TV and satellite television.
*   CCTV (security camera) systems.
*   Some broadband Internet connections (cable modem).

**4.3 Advantages and Disadvantages of Coaxial Cable**
*   **Advantages:**
    *   Better shielding and noise immunity than UTP.
    *   Can carry signals over longer distances than a single twisted-pair run.
*   **Disadvantages:**
    *   Thicker and less flexible than twisted-pair cables.
    *   Connectors (e.g. BNC, F-type) are more bulky.
    *   No longer common for new Ethernet LAN installations (mostly replaced by twisted-pair).

---

**5. Fibre-optic Cables**

**5.1 Basic Principle**
Fibre-optic cables transmit data as pulses of light instead of electrical signals.

Main parts:
*   Core – very thin glass or plastic strand where light travels.
*   Cladding – material surrounding the core with a lower refractive index.
*   Jacket – protective outer coating.

*Figure 4: Diagram of fibre-optic cable cross-section showing core, cladding and jacket.*

Light is kept inside the core by total internal reflection at the boundary between core and cladding.

**5.2 Single-mode vs Multimode Fibre**
There are two main types of fibre-optic cable used in networking:

**Single-mode fibre (SMF):**
*   Very small core (about 8–10 $\mu$m).
*   Light travels in one straight path.
*   Supports very long distances (tens of kilometres).
*   Often used for Internet backbone and long-distance links.

**Multimode fibre (MMF):**
*   Larger core (about 50 or 62.5 $\mu$m).
*   Light can travel in many paths, bouncing inside the core.
*   Suitable for shorter distances (up to a few kilometres).
*   Used inside buildings, campuses and data centres.

*Figure 5: Diagram comparing single-mode and multimode fibre. Single-mode: one straight light ray. Multimode: several zig-zag light paths inside the core.*

**5.3 Advantages and Disadvantages of Fibre-optic Cable**
*   **Advantages:**
    *   Extremely high bandwidth (very high data rates).
    *   Very long distance without significant signal loss (especially single-mode).
    *   Immune to electromagnetic interference (no copper).
    *   More secure against tapping compared with copper cables.

---

*   **Disadvantages:**
    *   Higher cost for both cable and fibre-optic networking equipment.
    *   More difficult to install and terminate (requires specialised tools and skills).
    *   Cables are more fragile than thick copper cables if handled roughly.

**6. Copper vs Fibre – Summary**

**Table 3 Comparison Between Copper and Fibre-optic Cables**

| Feature | Twisted-pair (UTP/STP) | Coaxial | Fibre-optic | Maximum data rate (typ.) | Typical max segment length | Typical use |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Transmission medium** | Electrical signals in copper wires | Electric signals in copper core | Light in glass/plastic | Up to 10 Gbps (Cat6a) | ~100 m | Office and school LANs |
| **Interference immunity** | Medium (better with shielding) | Better than UTP | Very high – not affected by EMI | Moderate | A few hundred metres | TV, CCTV, some broadband links |
| **Cost** | Low to medium | Medium | High | Very high (tens to hundreds of Gbps) | Many kilometres (single-mode) | Backbone, WAN, data centre, ISP |
