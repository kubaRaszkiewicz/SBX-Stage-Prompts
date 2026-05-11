# SBX-Stage-Prompts

**Prompts IA optimisés pour l'extraction de données orbitales binaires spectroscopiques du catalogue SBX.**

## 📋 **Contexte**
Ensemble de prompts structurés développés lors de mon stage de Master 1 (ULB, 2025-2026) sous la supervision de Thibault Merle pour compléter les vitesses radiales manquantes du catalogue SBX (successeur de SB9).

## 🎯 **Objectif**
- Extraction  de **paramètres orbitaux** et **vitesses radiales** (SB1/SB2)
- Traitement hybride littérature **ancienne** (scans OCR) et **moderne** (VizieR)
- Formatage CSV prêt pour soumission SBX (`Submit a New Orbit`)

## 📂 **Structure**
SBX-Stage-Prompts/

├── prompt-orbite.md              # Paramètres orbitaux SB1

├── prompt-velocities.md          # vitesse radial SB1

├── propmt-orbite-sb2.md          # Paramètres orbitaux SB2 

├── prompt-velocities-sb2.md      # Vitesses radiales SB2

└── README.md                       

## 🚀 **Utilisation simplifier**
1. **Capture d'écran** du tableau de données (littérature ancienne)
2. **Copier le prompt** correspondant (SB1/SB2, orbite/vitesses)
3. **Coller dans Perplexity/ChatGPT-5** avec tes captures
4. **Exécuter le code Python** généré dans Jupyter
5. **CSV prêt** pour SBX !

## 📊 **Résultats stage**
- **81 systèmes** traités (45 corrections + 19 nouvelles orbites + 15 nouveaux systèmes)
- **3 bibcodes** : `1987ApJS...64..487L`, `2007A&A...473..829M`, `1976ApJS...30..273A`

## 🔗 **Liens**
- [SBX Database](https://astro.ulb.ac.be/sbx)
