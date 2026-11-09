# 🧠 El Quinzet: Càlcul Mental (Problemes Verbals / Càlcul Global)

* **Accés a l'aplicació:** <https://cromer23cat.github.io/calculglobal/>
* **Públic objectiu:** Educació Infantil, Primària (1r a 6è) i Cicle Superior

## 📝 Descripció

Aquesta aplicació web és un entorn digital interactiu basat en les **Sèries Oficials de Problemes Verbals de Càlcul Mental d'El Quinzet**. Està dissenyada per millorar la comprensió lectora/auditiva, l'agilitat en la resolució de problemes matemàtics i l'automatització de conceptes clau sense necessitat de suport de paper.

## 🚀 Característiques i Funcionalitats Principals

* **📚 13 Sèries de Problemes Graduats:**
  * **Sèries 1 a 3:** EI / 1r i 2n de Primària (Iniciació, sumes/restes bàsiques fins al 10, dobles i descomposicions).
  * **Sèries 4 a 6:** 2n i 3r de Primària (Taules de multiplicar, meitats, diners i canvi de monedes).
  * **Sèries 7 a 9:** 3r a 5è de Primària (Diferències, quarts d'hora, mesos/anys, fraccions senzilles, dobles/triples).
  * **Sèries 10 a 13:** 5è, 6è i Cicle Superior (Decimals, percentatges, fraccions de repartiment, operacions horàries avançades, velocitat, escales i equivalències).

* **🎮 Dos Modes de Joc/Treball:**
  * **Mode Entrenament:** Permet llegir el text a la pantalla, escoltar-lo si cal i rebre retroacció immediata per corregir respostes.
  * **Mode Oficial El Quinzet:** Simula les condicions originals de la prova en grup. El text visual es pot ocultar (`hideTextActive`), forçant l'alumnat a treballar la memòria de treball i la comprensió auditiva mitjançant la síntesi de veu (`SpeechSynthesisUtterance`). Les repeticions d'àudio estan restringides.

* **🔊 Integració de Veu i Àudio (Web Speech API):**
  * Dictat automàtic de problemes en català (`ca-ES`).
  * Control de velocitat de lectura configurable (p. ex., 0.85x per a una pronunciació Clara i pausada).
  * Efectes de so generats per codi (`Web Audio API`) per encerts, errors, alertes i fanfàrria final.

* **✏️ Validació de Respostes (Regla d'Or d'El Quinzet):**
  * Sistema de validació intel·ligent per reconèixer nombres (sencers, decimals o fraccions com `3/4`) i paraules clau de la unitat.
  * Control d'oblit de la unitat: si l'estudiant indica el nombre correcte però oblida la unitat (p. ex., escriu *3* en comptes de *3 boles*), el sistema alerta que la resposta és incompleta segons el mètode oficial.

* **📊 Historial i Persistència:**
  * Desa els resultats de les sessions en memòria local (`localStorage`) per consultar la data, sèrie jugada, mode i el percentatge d'encerts assolits.

## 🛠️ Tecnologies Utilitzades

* **Frontend:** React 18 (utilitzat via CDN/Babel standalone en format single-file HTML).
* **Estils:** Tailwind CSS per a una interfície moderna, neta i adaptativa (*responsive*).
* **Àudio:** Web Speech API (síntesi de veu en català) i Web Audio API (efectes sonors de síntesi).

## 🎯 Objectiu Educatiu

Oferir una eina dinàmica que permeti treballar tant el càlcul mental verbal com la comprensió d'enunciats matemàtics a l'aula o a casa, adaptant-se als ritmes d'aprenentatge des dels primers cursos de primària fins al Cicle Superior.
