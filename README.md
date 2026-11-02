# Truth-Lens - AI-Powered Fake Content Detector

A web app that checks fake news (text/URL), AI-generated images and deepfake videos in one place, with confidence scores and explanations.

Final Year Project, BS Artificial Intelligence, University of Central Punjab (UCP), Lahore.

## Team
- Ali Zaman (L1F23BSAI0042): Fake news module,Flask API UI,PDF report
- M Mustafa (L1F23BSAI0103): Deepfake video module, UI
- Zainab (L1F23BSAI0084): Scrum Master,image module, PDF report, history log

Supervisor: Mam Iqra Tariq

## Folders
- text-model, image-model, video-model: the three detectors
- backend, frontend: Flask API and Streamlit app
- data_processing: cleaning, frame extraction, splitting
- tests: PyTest unit tests
- notebooks: Colab/Kaggle notebooks
- docs: data sheet and documentation

## Datasets
Not stored in this repo. Sources are listed in docs/data_sheet.md.

## Workflow
One branch per user story (feature/US-05-text-cleaning), commit messages start with the story ID, Pull Request reviewed by a teammate, then merge to main.