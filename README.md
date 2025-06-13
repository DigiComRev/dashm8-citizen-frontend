# dashm8-citizen-frontend
---

## 3. `dashm8-citizen-frontend`

```markdown
# Dashm8 - Citizen Dashboard

**Status:** `Active Development` | **Version:** 1.0.0 | **License:** MIT

This repository contains the source code for the user-facing **Dashm8** dashboard. This is the "Command Center" for the citizen, where they manage their myGENE Digital Twin, control permissions, view their data vault, and interact with the platform's advanced features.

### Core Technologies
* **Framework:** React (Vite)
* **Styling:** Tailwind CSS
* **State Management:** Zustand
* **Data Fetching:** React Query to interact with the `mygene-v2-platform` API.
* **Security:** All cryptographic operations for the user's data vault happen client-side before data is transmitted.

### Key Features
* **File Vault:** Secure, client-side encrypted file storage and management.
* **Identity & Permissions Hub:** Control which apps and extensions can use your Digizen ID.
* **Activity Log:** A transparent, human-readable log of all actions your Digital Twin has taken.
* **AI Twin Control Center:** Fine-tune the autonomy and preferences of your myGENE.
* Manages premium subscription tiers (5GB, 250GB, 500GB, 1TB).

### Setup & Installation
```bash
# Clone the repository
git clone [https://github.com/mygene-project/dashm8-citizen-frontend.git](https://github.com/mygene-project/dashm8-citizen-frontend.git)
cd dashm8-citizen-frontend

# Install dependencies
npm install

# Run the development server
npm run dev
