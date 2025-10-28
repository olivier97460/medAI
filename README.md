# MedAI / VetAI / SantAI
© 2025 Olivier Bénard — medai.re  
Open-source AI-powered clinical assistant for human and veterinary medicine.
MedAI  / VetAI is an intelligent clinical assistant designed to support practitioners in real-time decision-making, documentation, and case analysis.
It combines **audio transcription, natural language processing, and medical reasoning to provide a complete workflow for patient consultations.

This is the FIRST clinical assistant with:

    - EXPLICIT medical REASONING (thinking mode)
    - DYNAMIC knowledge base (up-to-date RAG)
    - GEOGRAPHIC CONTEXT (tropical medicine)
    - END-TO-END WORKFLOW (audio → diagnosis → prescription)
    - ONE HEALTH approach (human + veterinary)
    - GDPR-compliant (EU data protection)

MedAI  / VetAI is built around the One Health concept — connecting human, animal, and environmental health.
We are free, not chaotic.
No forks. No woke agendas. No corporate hijacks.
Decisions are scientific.
Mission To build tools that help practitioners — human and veterinary — make better, faster, and scientifically grounded decisions.

## English Version

### How It Works
1. **Real-time consultation transcription**
   - Records the consultation audio between the practitioner and the patient (or owner in veterinary cases).  
   - Produces a complete, editable transcription for review.

2. **Clinical analysis and synthesis**
   - Extracts key information: symptoms, medical history, ongoing treatments.  
   - Generates a comprehensive **anamnesis**.  
   - Suggests a **differential diagnosis** based on clinical data and curated scientific knowledge.

3. **Therapeutic proposal**
   - Recommends **treatment plans and prescriptions** tailored to the patient/species.  
   - Automatically calculates **dosages and treatment durations**.  
   - Checks **drug interactions** and flags potential risks.

4. **Documentation support**
   - Assists in writing **clinical reports, transmission reports**, and official documents.  
   - Prepares and structures **clinical case presentations** for teaching or review.  

5. **Integrated clinical workflow**
   - From audio consultation to documented treatment plan, the practitioner maintains **full control** over all decisions.  
   - AI suggestions are **supportive only** and never replace professional judgment.

6. **Additional clinical features**
   - Integration of complementary exams: lab results, imaging, biometrics.  
   - Longitudinal patient follow-up: history of consultations, treatments, and progress.  
   - Connection with validated medical and veterinary databases for updated recommendations.  
   - Support for **teleconsultations** or hybrid consultations (audio + patient data).

### Technical Features for Developers
- Open-source under **AI GPL v1 (based on AGPLv3)**.  
- Modular architecture: SantAI (core), MedAI (human medicine), VetAI (veterinary medicine).  
- Key modules:  
  - Audio-to-text transcription (multi-language support)  
  - NLP-based clinical reasoning  (claude by Anthropic / gpt-oss / modular choice)
  - Retrieval-Augmented Generation (RAG) datasets for knowledge verification  
  - Prescription and dosage engine  
  - Interaction check system for drugs and treatments  
- Designed for Python, FastAPI, and optional web interface.  
- Pull requests must be submitted to the **official medAI GitHub repository** to maintain scientific integrity.

---

## Version Française

### Comment ça marche
1. **Transcription en temps réel**
   - Enregistre l’audio de la consultation entre le praticien et le patient (ou le propriétaire en médecine vétérinaire).  
   - Génère une transcription complète et modifiable pour relecture.

2. **Analyse et synthèse clinique**
   - Extraction des informations clés : symptômes, antécédents, traitements en cours.  
   - Génération d’une **anamnèse complète**.  
   - Proposition d’un **diagnostic différentiel** basé sur les données cliniques et le corpus scientifique validé.

3. **Proposition thérapeutique**
   - Suggestions d’**ordonnances et prescriptions** adaptées à l’espèce et au patient.  
   - Calcul automatique des **posologies et durées de traitement**.  
   - Vérification des **interactions médicamenteuses** et alertes en cas de risques.

4. **Support documentaire**
   - Aide à la rédaction de **comptes rendus, rapports de transmission** et documents officiels.  
   - Préparation et organisation de **cas cliniques** pour enseignement ou revue.

5. **Workflow clinique intégré**
   - Depuis la consultation audio jusqu’au plan thérapeutique documenté, le praticien conserve **un contrôle total** sur les décisions.  
   - Les suggestions générées par l’IA sont **une aide à la décision**, et ne remplacent jamais le jugement professionnel.

6. **Fonctions supplémentaires**
   - Intégration des examens complémentaires : résultats de laboratoire, imagerie, biométrie.  
   - Suivi longitudinal des patients : historique des consultations, traitements et évolutions.  
   - Connexion avec des bases de données fiables pour mise à jour des recommandations.  
   - Support pour **téléconsultation** ou consultation hybride (audio + données patient).

### Fonctionnalités techniques pour les développeurs
- Open-source sous **AI GPL v1 (basée sur AGPLv3)**.  
- Architecture modulaire : MedAI (médecine humaine), VetAI (médecine vétérinaire), SaintAI (noyau technique).  
- Modules principaux :  
  - Transcription audio multi-langues  (whisper from openAI)
  - Raisonnement clinique basé sur NLP  (claude by Anthropic / choix modulaire)
  - Datasets RAG (Retrieval-Augmented Generation) pour vérification des connaissances  
  - Moteur de prescription et calcul de posologies  
  - Vérification des interactions médicamenteuses et alertes  
- Développé en **Python**, avec **FastAPI** et interface web optionnelle.  
- Les contributions doivent passer par le **GitHub officiel de MedAI** pour préserver l’intégrité scientifique.

---

## License

[AI GPL v1](LICENSE) — derived from AGPLv3.  
© 2025 Olivier Bénard — SantAI.re
