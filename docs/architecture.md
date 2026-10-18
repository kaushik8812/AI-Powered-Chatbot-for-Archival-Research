# System Architecture

```mermaid
flowchart TD
    A[Researcher] --> B[Drupal Chat Interface]
    B --> C[Python RAG Service]
    C --> D[Embedding Service]
    D --> E[Qdrant Vector Database]
    E --> C
    C --> F[HAWKI LLM API]
    F --> C
    C --> B
