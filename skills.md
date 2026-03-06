# BiBi Agent: Functional Capabilities 🛠️

BiBi is equipped with specialized skills designed for high-friction event environments:

### 👁️ Vision Intelligence (`vision_ui_analysis`)
* **Provider:** Gemini 2.0 Flash
* **Capability:** Parses user-submitted screenshots to identify UI elements (buttons, forms, error messages).
* **Logic:** Maps raw pixels to actionable instructions for the Binance App.

### 📶 Network Adaptive Delivery (`resilient_cdn`)
* **Provider:** OpenClaw Connectivity Manager
* **Capability:** Monitors local pings. If latency exceeds 1500ms, it triggers a "Lite-Mode" protocol.
* **Output:** Serves direct `.apk` or `lite-links` to bypass congested App Stores.

### 🎯 High-Value Lead Scoring (`lead_priority_engine`)
* **Provider:** Pattern Matching & NLP
* **Capability:** Flags keywords (Merchant, VIP, Institutional) for immediate human intervention.
* **Action:** Triggers a real-time notification to the nearest on-site Binance Angel.
