<!-- STREAMING_CHUNK:Documenting project overview and mission statement -->
# 🏙️ Urban Mitra — All-in-One Civic Solutions & Community Engagement OS

> **Next-Generation Smart City Operating System uniting municipal accountability, hyperlocal utility telemetry, community action circles, civic gamification, and AI-powered governance advisory.**

**Urban Mitra** (*Mitra* = Friend / Ally) is an open-source, full-stack, single-file civic technology platform built to bridge the gap between urban citizens and municipal administrations (such as Municipal Corporations, Councils, and Ward Committees). By coupling real-time telemetry, interactive geospatial mapping, crowd-verified grievance pipelines with strict SLA timers, community-organized micro-drives, and Google Gemini AI, Urban Mitra transforms passive city residents into proactive civic stakeholders.

---

<!-- STREAMING_CHUNK:Detailing core problems and urban solutions table -->
## 🚨 The Civic Bottlenecks & Urban Mitra Solutions

| Traditional Municipal Bottleneck | Real-World Impact on Cities | Urban Mitra Systematic Solution |
| :--- | :--- | :--- |
| **Unaccountable Grievance Redressal** | Potholes, broken streetlights, and pipeline leaks languish for months without engineer accountability. | **Public SLA Countdown Timers**: Every filed ticket has a mandatory 48-hour resolution clock with crowd-upvoting to escalate high-risk hazards. |
| **Fragmented Public Utility Data** | Citizens cannot find nearby clean water kiosks, e-waste sheds, or functioning EV charging bays. | **Interactive Urban Utility Grid**: Real-time Leaflet.js geospatial overlay with live status telemetry and one-touch map navigation. |
| **Lack of Citizen Assembly / Forum** | Hyperlocal issues (pedestrian crossings, stray animal care, tree trimming) rarely make official council agendas. | **Mohalla Citizen Assembly**: Transparent voting forum where community proposals crossing verified vote thresholds trigger municipal review. |
| **Complex Government Scheme Jargon** | Subsidies for solar rooftops, rainwater pits, and trade permits remain unclaimed due to bureaucratic complexity. | **Mitra AI Civic Concierge**: Instant plain-language guidance powered by Gemini 3 Flash, breaking down schemes like PM Surya Ghar into clear steps. |
| **Absence of Civic Incentives** | Citizens lack positive reinforcement for cleaning parks, reporting hazards, or sorting recyclables. | **Civic Karma Ledger**: Gamified proof-of-action rewarding citizens with redeemable vouchers for free metro transit, libraries, and parking. |

---

<!-- STREAMING_CHUNK:Detailing key functional modules -->
## 🌟 Core System Pillars

### 1. 📋 Public Grievance Pipeline & SLA Accountability
- **Category-Specific Issue Logging**: Report issues across **Roads & Potholes**, **Waste & Sanitation**, **Streetlights & Electrical Grid**, and **Water & Sewage Breaches**.
- **Transparent Ticket ID & SLA Timers**: Every issue receives a unique tracking ticket (e.g. `#GR-2026-4412`) with an active countdown clock indicating remaining hours within the guaranteed municipal service window.
- **Crowd Upvoting Prioritization**: Neighbors can upvote existing hazard tickets, algorithmically increasing dispatch urgency for Junior Engineers and Ward Corporators without filing duplicate complaints.
- **Direct Municipal Escalation**: Verified contact directory linking citizens directly to control rooms (1913 / 112) and ward corporator office personnel.

### 2. 🗺️ Hyperlocal Municipal Utility & Sensor Overlay (Leaflet.js)
- **Real-Time Public Amenity Markers**: Interactive geospatial pins for:
  - ⚡ **EV Fast Charging Bays**: Live port availability (DC 60kW/150kW) and tariffs.
  - 💧 **RO Purified Water Kiosks**: 20L municipal water dispense points.
  - ♻️ **Dry Waste & E-Waste Centers**: Operating hours and electronic drop-off centers.
  - 💊 **24/7 Jan Aushadhi Pharmacies**: Affordable generic medicine access points.
- **Geographic Filtering & Fly-To Navigation**: Instant search by amenity name with smooth animated map panning and coordinate telemetry.
- **Grievance Hazard Pins**: Visible warning overlays alerting commuters to reported potholes and dark street segments.

### 3. 🗣️ Mohalla Assembly Forum & Weekend Civic Drives
- **Grassroots Proposal Incubator**: Publish neighborhood improvement ideas (e.g. speed bumps near schools, pedestrian refuge islands) with upvoting thresholds that qualify ideas for Ward Committee meetings.
- **Weekend Community Action Drives**: Join volunteer initiatives such as native tree sapling plantations, lake perimeter cleanups, and residential battery roundups.
- **Diverted Waste & Environmental Metrics**: Tracks tangible monthly impact (e.g., tons of dry recyclables diverted from city landfills).

### 4. 🧠 Mitra AI — Municipal Advisor & Scheme Concierge
- **Powered by Gemini 3 Flash**: Natural language AI advisor specialized in Indian municipal bylaws, property tax calculation rebates, rainwater harvesting guidelines, and welfare schemes.
- **One-Touch Prompt Chips**:
  - ☀️ *PM Surya Ghar Free Rooftop Solar Subsidy Guide*
  - ♻️ *Solid Waste Management 3-Way Source Segregation Rules & Penalties*
  - 📄 *Trade License & Birth/Death Certificate Documentation*
- **Offline Heuristic Resiliency**: Built-in statutory fallback rules ensure citizens receive accurate regulatory guidance even without an active internet or API connection.

### 5. 🏅 Civic Karma Rewards Ledger & Digital Vouchers
- **Transparent Karma Accounting**:
  - `+20 Pts` for logging a verified civic issue.
  - `+50 Pts` upon municipal engineer fix confirmation.
  - `+60 Pts` for attending community cleanups and e-waste drives.
- **Redeemable Public Vouchers**:
  - 🚇 1-Day Free City Metro Transit Pass (150 Pts)
  - 📚 Annual Municipal Central Library Membership (200 Pts)
  - 🅿️ 3-Hour Free Multi-Level Public Parking Pass (100 Pts)
  - 🌱 Organic Home Compost Starter Kit Voucher (250 Pts)
- **HTML5 Canvas QR Generator**: Generates verifiable digital gate passes for seamless scanning at transit turnstiles and library checkouts.

---

<!-- STREAMING_CHUNK:Detailing technical architecture and design tokens -->
## 🛠️ Technical Architecture

Urban Mitra is developed strictly under the **Single-File Mandate** (`urban_mitra_app.html`), ensuring instantaneous zero-build execution in any modern web browser without dependencies, Node.js runtimes, or compilation steps.

| Architecture Layer | Technology Stack | Purpose & Integration |
| :--- | :--- | :--- |
| **Presentation Tier** | HTML5 / Semantic DOM | Zero-latency 5-tab responsive municipal dashboard |
| **Styling Framework** | Tailwind CSS CDN | Modern design tokens: `mitra` indigo, `ecoGreen`, `civicAmber`, `urbanDark` glassmorphism |
| **Typography** | Google Fonts | `Plus Jakarta Sans` for clean UI legibility, `JetBrains Mono` for coordinates & tickets |
| **Geospatial Engine** | Leaflet.js (v1.9.4) & CartoDB Dark Matter | Interactive hardware-accelerated mapping, custom HTML div-icons, dynamic tooltips |
| **Acoustic Feedback** | Web Audio API | Synthesized sine and triangle wave frequencies for upvotes, submissions, and reward redemptions |
| **Generative Intelligence** | Google Gemini API (`gemini-3-flash-preview`) | Contextual civic advice, scheme eligibility checks, and regulatory synthesis |
| **Digital QR Engine** | HTML5 2D Canvas API | Generates real-time verification matrices for public vouchers without external image CDNs |
| **State Machine** | Vanilla JavaScript (ES6+) | In-memory reactive state tracking grievances, upvotes, utilities, forum threads, and karma balance |

---

<!-- STREAMING_CHUNK:Documenting quick start instructions -->
## 🚀 Quick Start & Installation

Urban Mitra requires **no compilation, no package installations, and no database configurations**.

### Method 1: Direct Browser Launch
1. Download or clone `urban_mitra_app.html`.
2. Double-click the file to open it directly in Google Chrome, Brave, Mozilla Firefox, Microsoft Edge, or Safari.

### Method 2: Lightweight Local HTTP Server (Recommended)
Running via a local HTTP server provides smoother geolocation handling and permission persistence:

```bash
# Using Python 3
python -m http.server 8080

# Or using Node.js (npx)
npx serve .
```

Open your browser and navigate to:
```text
http://localhost:8080/urban_mitra_app.html
```

---

<!-- STREAMING_CHUNK:Documenting API key configuration and user workflow -->
## 🔑 Connecting the Gemini AI API Key

The application includes an integrated heuristic fallback engine that answers common municipal, solar subsidy, and waste segregation queries immediately. To enable live generative AI responses through Google Gemini:

1. Open `urban_mitra_app.html` in any code or text editor.
2. Locate the `submitAiCivicQuery` function (around line 530):
   ```javascript
   const apiKey = "YOUR_GEMINI_API_KEY_HERE";
   ```
3. Generate a free API key from [Google AI Studio](https://aistudio.google.com/).
4. Insert your key into the empty string, save the file, and refresh your browser.

---

## 🗺️ Citizen Interaction Lifecycle

```text
  [Identify Street Issue] ──> [File Grievance + Geotag] ──> [48h SLA Clock Begins]
           │                                                        │
           ▼                                                        ▼
  [Neighbors Upvote Ticket] ─> [Auto-Escalate to Engineer] ─> [Fix Verified (+50 Pts)]
           │                                                        │
           ▼                                                        ▼
  [Attend Weekend Drive] ───> [Earn Civic Karma] ──────────> [Redeem Metro / Library QR]
           │                                                        │
           ▼                                                        ▼
  [Ask Mitra AI] ───────────> [Understand Solar Subsidies] ─> [Lower Energy Costs]
```

1. **Spot & Report**: Open the **Civic Grievances & SLA** tab. Click **"Report Civic Issue"** to enter the location, category, and description.
2. **Track Accountability**: Monitor the 48-hour resolution countdown. Upvote neighboring issues to increase municipal priority.
3. **Explore Public Amenities**: Switch to the **Urban Utility Map** to find nearby fast EV charging bays, municipal water ATMs, and pharmacies.
4. **Engage with Mohalla Circles**: Participate in community discussions, propose pedestrian safety measures, or RSVP for weekend environmental drives.
5. **Redeem Rewards**: Use earned Civic Karma points in the **Civic Karma Rewards** tab to generate free digital transit or parking passes.

---

<!-- STREAMING_CHUNK:Finalizing telemetry details, disclaimers, and license -->
## 📊 Telemetry & Smart City Indicators

- **Ward SLA Resolution Rate**: `Resolved Tickets within 48h / Total Filed Tickets × 100` (Maintained above 89%).
- **AQI & Cleanliness Index**: Integrated environmental sensor readout displaying particulate index and street sweeping schedules.
- **Resource Recovery Metric**: Tracks aggregate dry waste and e-waste diverted from urban landfills through resident action.

---

## 📄 License

This software is released under the [MIT License](LICENSE) — free to use, modify, and adapt for municipal corporations, citizen welfare associations (RWAs), smart city hackathons, and civic governance deployments.
