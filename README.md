# Amir Abdur-Rahim

I'm finishing an MS in Management Information Systems at the University of Illinois Chicago (December 2026, Healthcare Information Systems concentration). Before the master's I spent two years as a medical scribe at Advocate Christ Medical Center, writing notes in Epic. I work in Python, SQL, and R.

Case studies: [amirabdurrahim.com/work](https://amirabdurrahim.com/work)

## Selected projects

**[Dataset distillation for vehicle damage classification](https://github.com/aabdur1/dataset-distillation-vehicle-damage).** My capstone this fall, sponsored by CCC Intelligent Solutions, on a 3-person team. I designed the experiments and ran the reported PyTorch runs. On held-out test data, a distilled set at 9.7% of the CarDD training data recovers 84% of full-data macro-F1 and beats herding-selected real images on a ConvNet in 5 of 5 seeds. The code is private, so that repo is a write-up of the method, the test protocol, and the results.

**[parkinsons-voice-screening](https://github.com/aabdur1/parkinsons-voice-screening).** Classifies Parkinson's disease from 165 acoustic features of sustained vowels (81 speakers), comparing four model families with stratified 10-fold cross-validation. Age alone reached an AUC of 0.864, so I report the voice-only AUC of 0.775 instead of the age-inflated 0.912. Python, scikit-learn, XGBoost.

**[docdefend-mvp](https://github.com/aabdur1/docdefend-mvp).** A web app that uses the Claude API to check whether E/M documentation supports the billing code before a claim goes out. The `agent/` folder rebuilds it as a Google ADK and Gemini agent that checks each cited code against live NLM data. It passed all 16 of its eval cases in the recorded run.

**[healthcare-terminology-mcp](https://github.com/aabdur1/healthcare-terminology-mcp).** An MCP server for ICD-10-CM, LOINC, RxNorm, HCPCS, and NPI lookups through public NLM and CMS APIs. The DocDefend agent uses it.

**[spotify-listening-dashboard](https://github.com/aabdur1/spotify-listening-dashboard).** My own Spotify history, 61,230 plays from 2021 to 2026, cleaned in Python notebooks and published as a [Tableau Public dashboard](https://public.tableau.com/app/profile/amir.abdur.rahim/viz/MySpotifyListening2021-2026/MySpotifyListening20212026).
