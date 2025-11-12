# 🧡 SAFIR — Gestió Familiar (versió superior)

Aquesta és la versió superior del projecte **SAFIR**, pensada per a la gestió familiar amb tres usuaris principals: **Mama (Iz)**, **Papa** i **Mirka**.  
Inclou rutines personalitzades, punts, validació i comunicació dins la família. 🌿

---

## 🌟 Objectiu
Crear una aplicació web (i futura app) per ajudar la família a organitzar les rutines, visualitzar els progressos i fomentar l’autonomia i la motivació.

---

## 👥 Perfils d’usuari
| Usuari | Funció principal | Accés |
|:--|:--|:--|
| 👩 **Mama (Iz)** | Configura les rutines, revisa punts, envia missatges i veu els informes | Panell complet |
| 👨 **Papa** | Supervisa i valida rutines | Panell simplificat |
| 👧 **Mirka** | Compleix rutines i veu punts i reptes visuals | Interfície adaptada i gamificada |

---

## ⚙️ Funcionalitats previstes
- Sistema de login local o familiar (3 usuaris)
- Rutines personalitzades per cada perfil
- Punts automàtics per cada tasca completada
- Missatges o frases de motivació
- Panell familiar amb estadístiques
- Possibilitat d’impressió i exportació
- Mode offline (PWA) i sincronització amb servidor local (Jarvis)

---

## 🧩 Etapes de desenvolupament
### 🔹 Etapa 1 — SAFIR Base
- HTML + CSS + JavaScript local amb `localStorage`
- Comptador de punts i pestanyes per moments del dia

### 🔹 Etapa 2 — SAFIR Família
- Afegir sistema d’usuaris i rols
- Dades separades per perfil
- Configurador de rutines per a Mama i Papa

### 🔹 Etapa 3 — SAFIR Connectat
- Servidor local o remot (Flask / FastAPI / Nextcloud)
- Sincronització de dades i accés multi-dispositiu
- Integració amb Jarvis i sistema de veu

---

## 🧠 Estructura del projecte
```
safir-familia/
│
├── index.html          # Interfície principal
├── style.css           # Estils generals (tema carbassa)
├── script.js           # Lògica principal i punts
├── data/               # Configuracions i dades locals
│   └── rutines.json
└── README.md           # Aquest fitxer d’instruccions
```

---

## 💡 Recomanacions
- Comença amb la versió HTML bàsica fins que funcioni estable.
- Desa còpies regulars de les configuracions.
- Si tens accés a un ordinador potent (servidor), podem desplegar-hi la versió connectada.

---

Fet amb 💛 per Iz i Mirka.  
**Projecte SAFIR – Família Conscient i Connectada.**
