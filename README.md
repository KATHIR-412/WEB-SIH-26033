## Smart India Hackathon Workshop
# Date: ## 25/11/26
## Reference Number: ## 26011621
## Name: ## KATHIR T

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
## Detailed Explanation:
**AgriDirect AI** is an omnichannel B2B and B2C digital marketplace that directly connects Farmer Producer Organizations (FPOs) and individual farmers with bulk buyers (retailers, HoReCa, processors) and everyday consumers. Beyond simple listing and ordering, the platform integrates a dedicated "Milk-Run" logistics layer and an AI-driven intelligence engine to manage crop aggregation, price discovery, and end-to-end delivery.
## How It Addresses the Problem:
**Eliminates Middlemen**: Replaces 4–5 layers of commission agents and mandi intermediaries with transparent direct-to-buyer bidding and fixed-price storefronts.
Solves Fragmented Transport: Pools small harvests from neighboring farms into consolidated FPO shipments, reducing per-kg freight costs.
Prevents Price Crashes & Gluts: Matches regional harvest schedules with real-time urban demand before crops leave the farm.
## Innovation & Uniqueness:
Dynamic Milk-Run Routing: Uses Vehicle Routing Problem (VRP) algorithms to schedule single trucks that pick up produce across multiple farms and drop off at urban micro-hubs.
Hyperlocal AI Demand & Price Engine: Combines historical mandi rates, weather data, and local festival/seasonal trends to recommend optimal harvest dates and fair floor prices.
Vernacular Voice-First & IVR Interface: Enables low-literacy farmers to list produce, check prices, and accept orders via regional voice commands or basic feature-phone SMS/IVR, alongside a full mobile/web app.


## Technical Approach
## Technologies to be Used:
	 Frontend: React.js (Web Dashboard for Bulk Buyers/FPOs), Flutter / React Native (Cross-platform Mobile App for Farmers & Drivers), Bhashini API (Vernacular voice-to-text & translation).
	 Backend: Node.js with Express / Python (FastAPI) for microservices architecture.
	 AI & Machine Learning: Python, Scikit-learn / XGBoost & Prophet (Demand & price forecasting), Google OR-Tools (Multi-stop route optimization & load pooling).
	 Database & Storage: PostgreSQL with PostGIS (Geospatial farm/hub mapping), Redis (Real-time inventory & bidding cache).
	 Integrations: UPI / Razorpay Route (Instant split-payments directly to farmer bank accounts), OpenWeatherMap API, ONDC (Open Network for Digital Commerce) protocol compatibility.
## Methodology & Implementation Process

<img width="553" height="314" alt="diagram" src="https://github.com/user-attachments/assets/1b36e748-0c30-469a-9da7-473f54d89458" />
 
	 Phase 1 (Data & Core MVP): Build farmer/buyer onboarding, e-KYC (linked with Aadhaar/FPO registration), and basic catalog listing.
	 Phase 2 (AI & Logistics Engine): Train demand-forecasting models on Agmarknet datasets and deploy OR-Tools for pooled pickup routing.
	 Phase 3 (Pilot & Scale): Integrate vernacular voice UI and UPI split-settlements; pilot with 2–3 local FPOs before scaling via ONDC.

## Feasibility and Viability
## Feasibility Analysis:
	 Technical: Relies on proven open-source geospatial and ML frameworks alongside India's existing Digital Public Infrastructure (UPI, Aadhaar, Bhashini), keeping development and cloud hosting costs low.
	 Operational: Partnering with existing FPOs (over 10,000 active across India) solves the "last-mile aggregation" challenge without building expensive new rural warehouses from scratch.
## Potential Challenges & Risks:
	 Low Digital Literacy & Smartphone Penetration: Smallholder farmers may struggle with complex app interfaces.
	 Lack of Trust in Quality Grading: Bulk buyers hesitate to buy produce sight-unseen due to inconsistent quality.
	 Perishability & Cold-Chain Gaps: High spoilage risk for fruits and vegetables during transit.
## Strategies to Overcome Challenges:
	 FPO-Assisted Onboarding & Voice UI: Appoint local "FPO Digital Mitras" to manage group listings and provide a vernacular voice/IVR interface.
	 Standardized AI-Assisted Photo Grading: Use smartphone computer-vision checks at FPO collection centers to tag produce into verified grades (Grade A/B/C) with dispute protection.
	 Time-Windowed Perishable Routing: Prioritize high-perishability crops in the VRP algorithm for early-morning dispatch and partner with third-party reefer transport providers for long-haul routes.
## Impact and Benefits
## Impact on Target Audience:
	 Farmers & FPOs: Gain transparent market access, assured upfront pricing, and faster payment cycles (T+1 day instead of weeks).
	 Consumers & Bulk Buyers: Access fresher, traceable farm produce at 15–25% lower prices than traditional multi-tier retail chains.
## Multi-Dimensional Benefits:
	 Economic: Increases farmer net income by 20–35% by capturing margins previously lost to intermediaries; lowers consumer food inflation.
	 Social: Empowers rural FPOs, reduces farmer distress caused by middleman exploitation, and creates local rural jobs in quality grading and micro-logistics.
	 Environmental: Reduces post-harvest food waste (currently ~15–20% in India) through demand-aligned harvesting and cuts carbon emissions via AI-optimized, consolidated truck routes.

## Research and References
## Government & Agricultural Market Data:
	 Agmarknet Portal (Ministry of Agriculture & Farmers Welfare) — Daily mandi arrivals and wholesale price datasets for training forecasting models.
	 e-NAM (National Agriculture Market) — Reference framework for electronic agricultural trading and quality assaying parameters.
	 SFAC (Small Farmers' Agribusiness Consortium) — FPO directory, aggregation guidelines, and operational models
## Technical & Open-Source Frameworks:
	 Google OR-Tools (Vehicle Routing Problem) — Algorithms for capacitated multi-stop pickup and delivery optimization.
	 BHASHINI (National Language Translation Mission) — Open APIs for Indian regional speech recognition and translation.
	 ONDC (Open Network for Digital Commerce) — Open protocol architecture for interoperable buyer-seller discovery and hyperlocal logistics.
