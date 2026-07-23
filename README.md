AgriBlock Carbon Protocol (TerraTrust)


Transparent, Blockchain-Powered Carbon Credit & Regenerative Farming Verification Platform



AgriBlock (TerraTrust) empowers smallholder farmers and agricultural enterprises to quantify, verify, and monetize soil organic carbon drawdown and sustainable farming practices on-chain. Built with AI-assisted MRV (Measurement, Reporting, and Verification) and transparent ESP (Environmental & Social Performance) audit standards, AgriBlock connects farmers directly to global carbon credit buyers with 92% direct revenue flow.



🌾 Core Features


Farmer Telemetry & MRV Portal: Easy registration of farm acreage, crop types, tillage practices, and biochar/fertilizer inputs.

AI Agronomist Carbon Assessment Engine: Automated quantification of baseline emissions vs. net carbon sequestration (tCO2e/year) with AI confidence scoring.

3rd-Party ESP Audit & Certification Hub: Independent verification desk checking Verra VM0042 & ESP guidelines (Soil Organic Carbon, Water Conservation, Biodiversity, Social Equity, and Additionality).

Transparent Reward & Carbon Marketplace:
Direct peer-to-peer purchasing of verified carbon credits.
On-chain retirement and token burning mechanism for corporate Net-Zero ESG compliance.
Automated 92% farmer payout smart contract split (5% ecosystem, 3% audit fund).

On-Chain Consortium Explorer: Real-time SHA-256 Merkle root verification, block height tracking, and smart contract inspector for CarbonMintingContract.sol and ESPComplianceManager.sol.



🛠️ Tech Stack


Frontend: React 19, TypeScript, Tailwind CSS v4, Motion, Lucide Icons.

Backend / API: Node.js, Express, tsx server runner.

AI Integration: Google Gemini API (@google/genai SDK) for satellite telemetry simulation & agronomist assessment.

Blockchain Target: Celo Network (EVM compatible, low-carbon footprint, mobile-first Web3 ecosystem).



🚀 Quick Start Guide

Prerequisites


Node.js (v18 or higher)

npm or yarn


Installation


Clone the repository:

git clone https://github.com/your-username/agriblock-terratrust.git
cd agriblock-terratrust

Install dependencies:

npm install

Configure Environment Variables: Copy .env.example to .env and set your optional keys:

cp .env.example .env

Run Development Server:

npm run dev
Open http://localhost:3000 in your browser.




📜 Available Scripts


npm run dev - Starts the development server on port 3000 with Vite middleware.

npm run build - Builds the client bundle and bundles the server into dist/server.cjs.

npm start - Launches the production Node server.

npm run lint - Runs TypeScript type checking.



🛡️ License

MIT License. Designed for open sustainable finance on Celo.

