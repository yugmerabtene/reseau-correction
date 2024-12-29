### **Question-01 :**  
**Réponse :** c) Couche session  
**Explication :** La couche session est responsable de la gestion des connexions et du contrôle du dialogue entre les applications.

---

### **Question-02 :**  
**Réponse :** b) IEEE 802.11  
**Explication :** IEEE 802.11 est la norme correspondant au Wi-Fi.

---

### **Question-03 :**  
**Réponse :** b) Couverture de grandes distances  
**Explication :** Les réseaux WAN (Wide Area Network) couvrent de grandes distances.

---

### **Question-04 :**  
**Réponses détaillées :**  

a) **Masque de sous-réseau en base binaire :**  
- **Notion binaire :** 11111111.11111111.11111111.11000000  
- **Explication :** Le suffixe /26 signifie que 26 bits sont réservés pour le réseau, soit un masque de 255.255.255.192 en décimal.  

b) **Nombre d’adresses IP utilisables :**  
- **Calcul :** \(2^{(32-26)} - 2 = 64 - 2 = 62\)  
- **Explication :** Deux adresses sont réservées (adresse réseau et broadcast).

c) **Adresse de diffusion (broadcast) :**  
- **Adresse :** 192.168.10.63  
- **Explication :** Tous les bits de la partie hôte sont à 1.  

d) **Première adresse utilisable :**  
- **Adresse :** 192.168.10.1  
- **Explication :** On ajoute 1 à l’adresse réseau.

---

### **Question-05 :**  
**Réponse :** a) Résolution des adresses IP en adresses MAC  
**Explication :** ARP associe une adresse IP à une adresse MAC.

---

### **Question-06 :**  
**Réponse :** b) Résoudre les noms de domaine en adresses IP  
**Explication :** Un serveur DNS traduit les noms de domaine en adresses IP.

---

### **Question-07 :**  
**Réponse :** c) Tout le réseau est affecté  
**Explication :** Dans une topologie en bus, une panne du câble principal impacte tout le réseau.

---

### **Question-08 :**  
**Réponse :** b) Fibre optique  
**Explication :** La fibre optique offre des connexions longue distance avec des débits élevés.

---

### **Question-09 :**  
**Réponses détaillées :**  

#### **Configuration du réseau :**  
- **Sous-réseau 1 :**  
  - Adresse : 192.168.1.0/24  
  - Gateway : 192.168.1.254  
  - Appareils :  
    - Serveur : 192.168.1.1  
    - Ordinateur 1 : 192.168.1.2  
    - Ordinateur 2 : 192.168.1.3  

- **Sous-réseau 2 :**  
  - Adresse : 192.168.2.0/24  
  - Gateway : 192.168.2.254  
  - Appareils :  
    - Ordinateur 1 : 192.168.2.1  
    - Ordinateur 2 : 192.168.2.2  

#### **Connexion des deux réseaux :**  
- Les deux sous-réseaux peuvent être interconnectés via un routeur ou un switch de niveau 3.  
- Les interfaces du routeur doivent être configurées comme suit :  
  - Interface 1 : 192.168.1.254 (pour 192.168.1.0/24).  
  - Interface 2 : 192.168.2.254 (pour 192.168.2.0/24).  
- Un routage statique ou dynamique doit être activé pour permettre la communication entre les deux sous-réseaux tout en les maintenant isolés.

---

### **Question-10 :**  
**Réponse :** c) Présentation  
**Explication :** La couche présentation traduit les données en un format compréhensible pour les applications.

---

### **Question-11 :**  
**Réponse :** c) Couche réseau  
**Explication :** Le protocole IP fonctionne au niveau de la couche réseau.

---

### **Question-12 :**  
**Réponse :** c) ICMP  
**Explication :** ICMP est utilisé pour envoyer des messages d’erreur et de diagnostic.

---

### **Question-13 :**  
**Réponse :** a) DHCP  
**Explication :** Le protocole DHCP attribue dynamiquement des adresses IP.

---

### **Question-14 :**  
**Réponses détaillées :**  
- **Switch :**  
  - Connecte plusieurs périphériques dans un réseau local (LAN) en utilisant des adresses MAC.  
  - Utilisé dans des bureaux pour connecter des ordinateurs, imprimantes, etc.  
- **Router :**  
  - Connecte différents réseaux (par ex. un LAN à Internet) en utilisant des adresses IP.  
  - Utilisé pour assurer l’accès à Internet.  

---

### **Question-15 :**  
**Réponses détaillées :**  

**Problèmes probables :**  
1. Trop d’appareils connectés au même réseau.  
2. Routeur inadapté à un usage professionnel.  
3. Mauvais positionnement du routeur, limitant la portée.  

**Solutions :**  
1. Configurer un réseau Wi-Fi invité pour limiter les périphériques personnels.  
2. Installer un routeur ou des points d’accès adaptés à un usage professionnel.  
3. Déployer des points d’accès supplémentaires pour étendre la couverture.
4. nstaller l’infrastructure principale (routeur ou point d’accès) dans un endroit bien ventilé et sans interférences (éviter les pièces qui agissent comme une cage de Faraday, par exemple celles avec des murs métalliques ou des grilles).
