# medAI /VetAI / SantAI Roadmap / Feuille de route

## Phase A – Prototype minimal - On Premise ONLY
- Curated RAG structure
- Core modules integration (SantAI = common technical core to VetAI and MedAI)
      Transcription: Whisper (local)
      LLM: Llama 3.1 70B via Ollama local
      RAG: LlamaIndex ✅ Vous maîtrisez déjà
      Framework: Python + FastAPI ✅ Parfait
      Base vectorielle: Qdrant ou ChromaDB (local)
      Interface: Streamlit (rapide) ou Gradio
        
santAI/
├── transcription/
│   ├── whisper_local.py           # Whisper base model
│   └── audio_processor.py         # Preprocessing audio
│
├── rag/
│   ├── vectorstore/
│   │   ├── chroma_db/             # Base ChromaDB locale
│   │   └── index_manager.py       # Gestion index LlamaIndex
│   │
│   ├── medical_corpus/
│   │   ├── guidelines/            # Vos JSONs guidelines
│   │   ├── pharmAI/               # Données Pharmacopéé
│   │   ├── protocols/             # Protocoles thérapeutiques
│   │   └── tropical_diseases/     # Spécifique Réunion
│   │
│   ├── retriever.py               # ⭐ LLAMAINDEX
│   ├── embeddings.py              # Modèles embedding (sentence-transformers)
│   └── corpus_loader.py           # Chargement JSONs → LlamaIndex
│
├── llm/
│   ├── qwen3_interface.py         # Interface principale Qwen3
│   ├── qwen3_thinking.py          #  ⭐ Mode thinking médical
│   └── config.py                  # Configuration modèle
│
├── prescription/
│   ├── dosage_engine.py           # Calculs posologies
│   ├── interaction_checker.py     # Vérification interactions
│   ├── molecule_visual.py         # Active molecule visual
│   │   https://molecule-icon-generator.streamlit.app/
│   └── vidal_interface.py         # Interface base Vidal
│
├── api/
│   ├── main.py                    # FastAPI principal
│   ├── routes/
│   │   ├── consultation.py        # Endpoints consultation
│   │   ├── diagnostic.py          # Endpoints diagnostic
│   │   └── prescription.py        # Endpoints prescription
│   └── models.py                  # Pydantic models
│
├── interface/
│   ├── app.py                     # Streamlit principal
│   └── components/
│       ├── transcription_ui.py    # UI transcription
│       ├── diagnostic_ui.py       # UI diagnostic différentiel
│       └── prescription_ui.py     # UI prescription
│
├── requirements.txt               # Dépendances
├── config.yaml                    # Configuration globale
└── README.md                      # Documentation


- First local LLM test
- Proof Of Concept


## Phase B – Academic pilot
- Clinical and veterinary validation
- User feedback loop
- Improved testing and CI

## Phase C – LTS (Long-Term Support)
- Stable release
- Debian packaging & integration
- Documentation & multilingual support
- Governance & funding model operational

## Future
- International regional deployments under SaintAI core
- Integration with public health datasets and partners
