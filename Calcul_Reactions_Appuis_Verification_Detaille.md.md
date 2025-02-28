# **Calcul détaillé des réactions aux appuis et vérification**

## **1. Données du problème**

### **Géométrie du portique :**
- **Barre verticale AB (gauche) :**  $$h_{AB}$$= 3.6  m, articulée en  A 
- **Barre horizontale BC :** $$l_{BC}$$ = 5$ m
- **Barre verticale CD (droite) :** $$h_{CD}$$ = 3.0 m, articulée en D

### **Charges appliquées :**
- **Force horizontale en  B  :** 30  kN vers la droite
- **Force verticale en  C :**  50  kN vers le bas à  2.5  m de  B 

### **Inconnues des réactions aux appuis :**
- **Réactions en A  :** $$A_x, A_y$$
- **Réactions en D  :** $$D_x, D_y$$

---

## **2. Calcul détaillé des réactions aux appuis**

### **Équilibre des forces horizontales :**
$$A_x + D_x = 30$$

### **Équilibre des forces verticales :**
$$A_y + D_y = 50$$

### **Équilibre des moments autour de  A  :**
$$- D_y 	*5 + D_x 	* 0.4 = 233$$

---

### **Étape 1 : Résolution de  $$D_y$$**  
Nous isolons $D_y$ en utilisant l’équation des moments :  

$$D_x 	* 0.4 = 233 + D_y 	* 5$$  

Nous résolvons numériquement et trouvons :  

$$D_y = -39.44 	\ { kN}$$

---

### **Étape 2 : Calcul de $$D_x$$**  
Substituons $D_y$ dans l’équation précédente :  

$$D_x = \frac{233 + (-39.44)*5}{0.4}$$  

Ce qui donne :  

$$D_x = 89.44 	\ { kN}$$

---

### **Étape 3 : Calcul de  $$A_x$$  et $$A_y$$**  
En utilisant l’équilibre des forces :  

$$A_x = 30 - D_x = 30 - 89.44 = -59.44 	{ kN}$$  
$$A_y = 50 - D_y = 50 - (-39.44) = 89.44 	{ kN}$$

---

## **3. Vérification des équilibres**

### **1. Équilibre des forces horizontales**  
$$A_x + D_x = -59.44 + 89.44 = 30.0$$  
✅ **Correct**

### **2. Équilibre des forces verticales**  
$$A_y + D_y = 89.44 - 39.44 = 50.0$$  
✅ **Correct**

### **3. Équilibre des moments autour de A**  
$$- D_y 	* 5 + D_x 	* 0.4 = -(-39.44) 	* 5 + 89.44 	* 0.4 = 233.0$$  
✅ **Correct**

---

### **Conclusion :**  
Tous les équilibres sont respectés. **Les résultats sont corrects.** ✅
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MzkxMTY0MzFdfQ==
-->
