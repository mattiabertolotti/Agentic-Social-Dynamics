# Agentic-Social-Dynamics
A NetLogo agent-based simulation of a social event, enhanced with LLM-driven behaviors and psychological personality traits for realistic social dynamics.

---

**Agentic-Social-Dynamics** è una simulazione basata su agenti (ABM) sviluppata in NetLogo che modella le dinamiche di un evento sociale. Il progetto integra **Large Language Models (LLMs)** e tratti di **personalità psicologica** per superare i limiti dei modelli tradizionali, creando interazioni umane più realistiche ed emergenti.

## 📖 Descrizione del Progetto
Questa simulazione esplora come le personalità individuali e le capacità cognitive (fornite dagli LLM) influenzino il comportamento collettivo durante un evento sociale. 

A differenza dei modelli ABM classici dove gli agenti seguono regole "if-then" fisse, in questa tesi gli agenti:
1. Possiedono un profilo psicologico (basato sul modello **Big Five**).
2. Elaborano il contesto sociale tramite un LLM.
3. Decidono come interagire, con chi parlare e come reagire agli stimoli ambientali in modo dinamico.

## ✨ Caratteristiche Principali
- **Integrazione LLM:** Gli agenti utilizzano l'AI per generare decisioni e dialoghi.
- **Modellazione della Personalità:** Implementazione di tratti come Estroversione/Introversione che influenzano la frequenza e la qualità delle interazioni.
- **Memoria Sociale:** Gli agenti ricordano le interazioni passate, influenzando le relazioni future.
- **Visualizzazione Real-Time:** Interfaccia NetLogo per osservare spazialmente l'andamento delle dinamiche sociali.

## 🏗 Architettura Tecnica
Il progetto utilizza un approccio ibrido:
- **Frontend/Simulazione:** NetLogo gestisce il movimento, la vicinanza spaziale e il loop della simulazione.
- **Backend Cognitivo:** Uno script Python gestisce le chiamate API verso l'LLM e l'elaborazione dei tratti di personalità.
