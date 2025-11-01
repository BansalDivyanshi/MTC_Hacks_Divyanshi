# MTC_Hacks_Divyanshi

Upload or enter multiple Study IDs for one patient.

For each study: call HOPPR VLM (cxr-vlm-experimental) + 3 classifiers (pneumothorax, pleural effusion, cardiomegaly).

Build timeline (newest → oldest).

Compute changes over time (improved / worsened / stable) using score deltas + threshold crossings.

Show Automated Report (VLM narrative), Scores, Explainability (keyword badges per sentence).

Generate plain-language patient handout (shareable route).

WebSocket push for stepwise progress (no queues; per-job in memory).

Pretty Streamlit UI (cards, badges, subtle animations).
