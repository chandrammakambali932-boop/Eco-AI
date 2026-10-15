# EcoTwin AI — Premium Animated Sustainable Campus Login System

A modern, responsive, animated login experience engineered for **EcoTwin AI**, an AI-powered university sustainability and campus decarbonization platform. Built with **React 19**, **Vite 8**, and **modular CSS animations**.

---

## 🌿 Key Features & Design Highlights

### 1. Split-Screen Layout (55% Hero / 45% Form)
- **Left Panel (55% width)**:
  - Atmospheric college campus background featuring modern collegiate architecture, solar arrays, lush green foliage, and natural morning sunlight.
  - Multi-layer forest green and emerald gradients with slow ambient breathing motion.
  - Interactive **CampusVisualEffects** canvas rendering floating green energy particles, intelligent digital-twin network connection lines, and a subtle AI scanning beam.
  - Animated **"AI-POWERED CAMPUS DECARBONIZATION"** badge with a pulsing status node.
  - Impactful headline: **“Empowering Universities Towards a Net-Zero Future.”** with a **staggered word-by-word reveal**.
  - Supporting description fading in with a smooth upward slide.
  - Three glassmorphic statistic cards with **live count-up animations**:
    - **42.8%** — Solar Powered Today
    - **−18.4 t** — CO₂ Campus Reduction
    - **28 Halls** — Climate Optimized
  - Endorsement quote from Dr. Elena Vance, Director of Campus Sustainability.

- **Right Panel (45% width)**:
  - Clean, warm off-white surface (`#fcfdfd`) with generous spacing and modern SaaS typography.
  - Animated **EcoTwin AI** brand logo at the top.
  - Heading: **“Welcome Back!”** and Subtitle: **“Building a smarter, greener campus together.”**
  - **PROTOTYPE DEMO MODE** information card with an animated sparkle icon and one-click quick-fill chips for **Student Account** and **Sustainability Director**.
  - Accessible input fields with floating focus rings and real-time inline validation.
  - Password visibility toggle with smooth icon transitions.
  - **“Remember Me”** custom checkbox and **“Forgot Password?”** dialog link.
  - Premium full-width emerald gradient **“Sign In”** button with reflection sweep, hover elevation, pressed state, and loading spinner.
  - Refined footer: **“Powered by EcoTwin AI”** with an animated pulsing leaf icon.

### 2. Standout Animated "EcoTwin AI" Brand Logo
- **Letter-by-Letter Entrance**: Each character reveals sequentially on page load with a subtle upward spring.
- **Continuous Gradient Shimmer**: Flowing emerald, mint, and white/dark-green highlights traveling infinitely across the wordmark.
- **Dedicated "AI" Accent**: Glowing emerald aura with gentle continuous pulse.
- **Floating Eco-Energy Icon**: Stylized leaf and campus facade with subtle 3D floating oscillation, slow sway, and radial glow.
- **Animated Light Trail**: A glowing photon beam gliding across the baseline under the logo.
- **Hover Micro-Interaction**: Soft expansion and intensified aura on cursor interaction.

---

## 🚀 How to Run and Test

The Vite development server is running at:
```
http://127.0.0.1:5173/
```

### Manual Commands:
```powershell
# Navigate to the project folder
cd "C:\Users\Skill-Lync\.gemini\antigravity\scratch\ecotwin-ai"

# Start the dev server
npm run dev

# Or build for production
npm run build
```

---

## 📁 Component Directory

```
src/
├── components/
│   ├── EcoTwinLogo.jsx          # Animated logo with letter reveal, shimmer & light trail
│   ├── CampusShowcase.jsx       # 55% hero panel with word reveal & count-up stats
│   ├── CampusVisualEffects.jsx  # Canvas energy particles, network grid & AI scan beam
│   ├── LoginForm.jsx            # 45% form panel with demo chips, validation & emerald button
│   ├── ForgotPasswordModal.jsx  # Password recovery simulation modal
│   ├── CreateAccountModal.jsx   # Campus account registration modal
│   └── DashboardPreview.jsx     # Authenticated Campus Command Center view
├── hooks/
│   └── useCountUp.js            # Quintic ease-out count-up animation hook
├── styles/
│   ├── variables.css            # Environmental tech design tokens & color palette
│   └── login.css                # Split-screen styling, keyframe animations & responsive queries
├── App.jsx                      # Root container managing authentication & modals
├── index.css                    # Base reset
└── main.jsx                     # Entry point
```
