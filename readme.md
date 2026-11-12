# 🏫 Distribuïdor d'Aula de Primària

Una aplicació web interactiva, ràpida i intuïtiva dissenyada per a mestres i docents d'Educació Primària i Infantil per organitzar la distribució de les taules i l'alumnat a l'aula de manera visual i eficient.

---

## ✨ Funcionalitats Principals

* **📋 Gestió Fàcil de l'Alumnat:** Enganxa o escriu directament el llistat d'alumnes (separats per salts de línia o comes) amb recompte automàtic i dades d'exemple integrades.
* **🪑 Múltiples Plantilles de Distribució:**
  * **Grups de 4:** Ideal per a treball cooperatiu en equips base.
  * **Grups de 3 (en línia):** Taules alineades de tres alumnes.
  * **Grups de 6:** Taules grans per a projectes grupals.
  * **Parelles:** Disposició per a tutoria entre iguals (*peer learning*).
  * **Forma de U:** Perfecta per a assemblees, debats i posades en comú.
  * **Fileres Individuals:** Per a proves d'avaluació o treball individual.
* **🚫 Sistema Intel·ligent de Restriccions (Adjacència):**
  * Permet definir incompatibilitats entre alumnes (ex. *"Maria no pot anar al costat de Berta"*).
  * Detecta automàticament si dos alumnes incompatibles queden asseguts en **posicions adjacents** (tant en horitzontal com en vertical dins del mateix equip o filera) i els marca amb una alerta visual en vermell.
* **🔀 Barreja Automàtica amb Regles:** Algorisme de barreja que realitza múltiples iteracions per trobar una distribució aleatòria que respecti totes les restriccions definides.
* **🖱️ Arrossegar i Deixar Anar (Drag & Drop):** Intercanvia la posició de dos alumnes simplement arrossegant un nom sobre un altre (compatible tant amb **ratolí** com amb **pantalles tàctils / tauletes**).
* **🖨️ A punt per Imprimir / Exportar a PDF:** Estils optimitzats per a impressió que oculten el panell de control lateral i generen un plànol net de l'aula.

---

## 🚀 Com utilitzar l'aplicació

Aquesta aplicació funciona completament al navegador sense necessitat d'instal·lar res ni de connexió a bases de dades externes:
(https://bmarquil.github.io/DistribuidorAula/)

1. Descarrega el fitxer `index.html` d'aquest repositori.
2. Obre'l amb qualsevol navegador web modern (Chrome, Firefox, Safari, Edge).
3. Enganxa els noms de la teva classe al panell esquerre i fes clic a **Actualitzar Llista**.
4. Configura les restriccions, tria el format de taules i fes clic a **Barrejar** o mou els alumnes manualment.
5. Prem **Imprimir / Desar PDF** per obtenir el plànol llest per penjar a l'aula.

---

## 🛠️ Tecnologies Utilitzades

* **HTML5** semàntic
* **Tailwind CSS** (via CDN) per al disseny responsiu i estils d'impressió
* **JavaScript (Vanilla ES6+)** per a la lògica d'adjacència, barreja i interacció tàctil/ratolí
* **FontAwesome** per a la iconografia

---

## 👨‍💻 Autor

App creada per **Bernat Marquilles** ([@bmarquil](https://github.com/bmarquil) a GitHub).

---

## 📄 Llicència

Aquest projecte és de codi obert i es pot utilitzar, modificar i compartir lliurement per a finalitats educatives.
