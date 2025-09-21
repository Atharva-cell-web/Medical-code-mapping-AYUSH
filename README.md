Smart Dual-Coding Assistant (AYUSH ↔ ICD-11)

A lightweight software service that bridges Traditional Medicine (AYUSH/NAMASTE) and Modern Medicine (ICD-11) by enabling dual coding, aligned with India’s EHR standards (FHIR R4) and ABDM consent framework.

✨ Features
🔍 Autocomplete Search – Google-like suggestions for AYUSH terms
📖 WHO Ayurveda Definitions & Synonyms – Instant reference for practitioners
🌐 Dual Coding – Map NAMASTE codes with ICD-11 (TM2 + Biomedicine)
📶 Offline Cache – Useful in rural/low-connectivity clinics
🛡️ Consent & Audit Logging – ABHA-ready with secure record-keeping
💾 EMR Integration – Saves patient data with both codes (traditional + biomedicine)

📌 Example Flow
👩‍🦰 Patient reports stomach issues → 👨‍⚕️ Doctor types “Agnimandya”

Suggests:
NAMASTE: Agnimandya (Impaired digestion)
ICD-11 TM2: Spleen Qi Deficiency
ICD-11 Biomedicine: Functional Dyspepsia
👨‍⚕️ Doctor selects → 📖 WHO definition displayed → 🛡️ Consent logged → 💾 Dual codes saved in EMR

⚙️ Tech Stack
FHIR R4 – Indian EHR standards compliance
WHO ICD-11 API – Code mapping (TM2 + Biomedicine)
NAMASTE Portal APIs – AYUSH terminology integration
ABDM Consent Framework – For secure patient data handling
Database – For caching, mapping & offline use

🚧 Challenges
Ensuring accuracy of code mappings (AYUSH ↔ ICD-11)
Adoption by EMR vendors & practitioners
Navigating evolving healthcare regulations

🛠️ Future Enhancements
🔄 Regular updates in collaboration with AYUSH experts
📊 Analytics dashboard for usage & adoption metrics
🌍 Multi-language support for wider accessibility

📚 References
EHR Standards for India (2016)
ABDM (Ayushman Bharat Digital Mission)
NAMASTE Portal
WHO ICD-11 Browser
WHO ICD-11 API

👥 Team

Tech Titans – Smart India Hackathon 2025
