# KrishiSarthi AI — Requirements

## 1. Problem Statement
Farmers in rural India often lack timely, reliable, and localized guidance for crop planning, pest/disease identification, fertilizer usage, irrigation scheduling, and market pricing. This results in reduced yield, higher input costs, and preventable crop loss.

## 2. Proposed Solution
KrishiSarthi AI is a multilingual AI assistant designed for rural farmers that provides:
- Crop planning and seasonal recommendations
- Pest/disease identification using crop images
- Fertilizer and pesticide dosage guidance (non-prescriptive and safety-first)
- Weather-aware irrigation suggestions
- Local mandi price and trend insights
- Voice + chat interface for low-literacy accessibility

## 3. Target Users
- Small and marginal farmers
- Farmer Producer Organizations (FPOs)
- Rural agriculture extension workers
- Agri-input shop owners (as assisted mode)

## 4. Key Features (MVP)
### 4.1 Multilingual Farmer Chat Assistant
- Supports Hindi, Marathi, and English (extendable to other languages)
- Works in text mode (MVP) and voice mode (future)

### 4.2 Crop Guidance Module
- Crop selection suggestions based on season and region
- Basic sowing calendar and farming best practices

### 4.3 Pest/Disease Detection (Image-based)
- User uploads crop/leaf image
- System returns likely disease/pest + confidence
- Provides safe next steps and recommends contacting experts when needed

### 4.4 Weather & Irrigation Suggestions
- Fetches weather forecast
- Provides irrigation timing suggestions

### 4.5 Market Intelligence (Optional in MVP)
- Shows crop mandi prices (by district)
- Provides simple trend summary

## 5. Non-Functional Requirements
- Simple UI optimized for mobile
- Low bandwidth operation (compressed images, lightweight responses)
- Privacy-first: no unnecessary personal data stored
- Responsible AI: disclaimers for medical/agri risk and escalation paths

## 6. Constraints
- MVP must work with limited datasets and public sources
- Must avoid giving unsafe pesticide dosages as “final advice”
- Should be usable without requiring login for first-time usage (optional)

## 7. Success Metrics
- Farmers receive actionable responses within 5 seconds
- 80%+ queries resolved without needing manual support
- Increased adoption via multilingual + voice accessibility

## 8. Out of Scope (for MVP)
- Full government integration
- Payments and marketplace
- Real-time IoT farm sensors
- Offline-first native app (future scope)

