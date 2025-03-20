# **Ubuntu Szerver Vizsgafeladat**

**Tantárgy:** Szerverek és hálózatok  
**Vizsgázó neve:**  _______________________________  
**Dátum:**  _______________________________  

**Instrukciók:**
- A vizsga teljes időtartama: **korlátlan az órák végéig**.


---

## **Feladatok és követelmények:**

### **1. Rendszerindítás és GRUB konfiguráció (2 pont)**
- Tekintse meg és szerkessze a GRUB konfigurációt úgy, hogy az időzítés 5 másodpercre legyen állítva. (1p)
- Frissítse a GRUB beállításokat. (1p)


---

### **2. Futási szintek és systemd konfiguráció (2 pont)**
- Ellenőrizze az aktuális futási szintet és jegyezze fel. (1p)
- Állítsa be a szervert úgy, hogy mindig multi-user.target állapotban induljon. (1p)


---

### **3. Statikus IP-cím beállítása (3 pont)**
- Nyissa meg és szerkessze a Netplan konfigurációt. (1p)
- Állítsa be az IP-címet 192.168.1.69/24-re. (1p)
- Alkalmazza a beállításokat és ellenőrizze az új IP-címet. (1p)


---

### **4. Fájlrendszer és particionálás (3 pont)**
- Listázza ki a csatlakoztatott meghajtókat. (1p)
- Hozzon létre egy új partíciót a `/dev/sdb` meghajtón. (1p)
- Formázza azt **ext4** fájlrendszerre. (1p)



---

### **5. Linkek kezelése Linux fájlrendszerben (2 pont)**
- Hozzon létre egy **hard linket** egy meglévő fájlhoz. (1p)
- Hozzon létre egy **szimbolikus linket** egy másik fájlhoz. (1p)

---

### **6. Fájlhozzáférések és jogosultságok (3 pont)**
- Módosítsa egy fájl engedélyeit 755-re. (1p)
- Állítsa be a tulajdonosát egy másik felhasználóra. (1p)
- Adjon egy felhasználónak teljes ACL jogosultságot egy fájlra. (1p)

---

### **7. DHCP szerver beállítása (4 pont)**
- Telepítse és konfigurálja az **ISC DHCP szervert**. (1p)
- Állítsa be a DHCP hatókört **192.168.1.100-192.168.1.200** tartományban. (1p)
- Állítsa be az alapértelmezett átjárót 192.168.1.69-re. (1p)
- Engedélyezze és indítsa el a DHCP szolgáltatást. (1p)

---

### **8. Apache webkiszolgáló telepítése (2 pont)**
- Telepítse az **Apache** webkiszolgálót. (1p)
- Indítsa el és ellenőrizze a működését. (1p)

---

### **9. MySQL szerver telepítése és konfigurálása (3 pont)**
- Telepítse a MySQL szervert. (1p)
- Futtassa a biztonsági konfigurációs varázslót. (1p)
- Hozzon létre egy új adatbázist **vizsgadb** néven. (1p)

---

### **10. Tűzfal és biztonsági beállítások (3 pont)**
- Engedélyezze az UFW tűzfalat. (1p)
- Nyisson meg egy portot az Apache számára. (1p)
- Engedélyezze a távoli SSH hozzáférést. (1p)

---

## **Értékelés**

| Feladat                  | Max. Pont | Elért Pont |
| ------------------------ | --------- | ---------- |
| Rendszerindítás és GRUB  | 2         |            |
| Futási szintek beállítása | 2         |            |
| Statikus IP beállítása    | 3         |            |
| Particionálás és fájlrendszer | 3   |            |
| Linkek kezelése          | 2         |            |
| Fájlhozzáférések         | 3         |            |
| DHCP szerver konfigurálás | 4        |            |
| Apache webkiszolgáló     | 2         |            |
| MySQL szerver beállítása | 3         |            |
| Tűzfal beállítások       | 3         |            |
| **Összesen**             | **27**    | **/**      |

---

**Vizsgáztató aláírása:** _______________________________

A vizsga befejezése után kérjük, hogy adja le a dokumentációt és az ellenőrzési jegyzőkönyvet a vizsgáztatónak.
