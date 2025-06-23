# Petpal-AI

Petpal-AI is an AI-powered project designed to build, store, and utilize a knowledge base for pet health. The project is organized into three main phases:

## Project Structure

```
requirements.txt
phase_1_knowledge_base/
    1_build_kb.ipynb
    phase_1_knowledge_base.json
    knowledge_base/
        final_pet_health_kb.json
        pet_health_data.json
        universal_pet_health_data.json
phase_2_the_brain/
    2_build_vector_db.ipynb
    chroma_db/
        chroma.sqlite3
        ...
phase_3_the_mouth/
    phase_3.ipynb
```

## Phases Overview

### Phase 1: Knowledge Base Construction
- **Location:** `phase_1_knowledge_base/`
- **Purpose:** Collect and process pet health data to build a comprehensive knowledge base.
- **Key Files:**
  - `1_build_kb.ipynb`: Jupyter notebook for building the knowledge base.
  - `knowledge_base/`: Contains JSON files with processed pet health data.

### Phase 2: Vector Database Creation
- **Location:** `phase_2_the_brain/`
- **Purpose:** Convert the knowledge base into a vector database for efficient semantic search and retrieval.
- **Key Files:**
  - `2_build_vector_db.ipynb`: Jupyter notebook for building the vector database.
  - `chroma_db/`: Stores the vector database files (e.g., `chroma.sqlite3`).

### Phase 3: Query Interface (The Mouth)
- **Location:** `phase_3_the_mouth/`
- **Purpose:** Provide an interface to query the knowledge base using AI models.
- **Key Files:**
  - `phase_3.ipynb`: Jupyter notebook for querying and interacting with the knowledge base.

## Setup Instructions

1. **Install Dependencies**
   - Run `pip install -r requirements.txt` to install required Python packages.

2. **Run Each Phase**
   - Open and execute the notebooks in order:
     1. `phase_1_knowledge_base/1_build_kb.ipynb`
     2. `phase_2_the_brain/2_build_vector_db.ipynb`
     3. `phase_3_the_mouth/phase_3.ipynb`

## Notes
- Ensure you have Python and Jupyter Notebook installed.
- Each phase builds upon the previous one, so follow the order for best results.

## License
This project is for educational and research purposes.
