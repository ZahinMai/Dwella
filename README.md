# Dwella — House-Share Matching App

Dwella helps users find properties and compatible flatmates quickly and easily.  
The platform uses intelligent matching based on lifestyle preferences and verified profiles to make relocation less stressful and avoid mismatched housemates.

---

## Features

- **Property Browsing** — Explore available rooms without needing to sign up first.  
- **Flatmate Matching** — Match with people based on gender, smoking status, location, course, and lifestyle.  
- **Smart Recommendations** — Behind-the-scenes matching algorithm connects students and young professionals with similar habits.  
- **Optional ID Verification** — Build trust through verified profiles.  
- **Integrated Messaging** — Communicate directly with potential flatmates or landlords.  
- **Optimized Onboarding** — Simple, low-friction signup flow.

---

## Technology Stack

- **Backend:** Spring Boot (MVC, modular monolith)  
- **Frontend:** Angular + Tailwind CSS  
- **Database:** PostgreSQL (production), H2 in-memory (development)  
- **Authentication:** JWT (stateless, Angular-friendly)  
- **Caching:** Ehcache + Hibernate 2nd-level cache  
- **Build Tools:** Maven + npm  

---

## Getting Started

### Prerequisites
- Java 17+  
- Node.js 18+  
- npm or yarn  
- PostgreSQL (for local or production database)

### Setup

```bash
# Clone repository
git clone https://github.com/<your-username>/dwella.git
cd dwella

# Install frontend dependencies
npm install

# Run backend (Spring Boot)
./mvnw

# Run frontend (Angular)
npm start
```
