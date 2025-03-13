# PetalHamr
An app to hammer pediatric vitals into your brain 🧠🔨

_Last Updated: 13MAR2025_

# About
## Overview

The Pediatric Vitals Drill App is a lightweight, interactive game designed to help reinforce pediatric clinical skills. The app presents a one-line clinical scenario—including weight and 1 to 4 vital signs (heart rate, blood pressure, temperature, respiratory rate, or 24‑hr urine output). Users quickly input a free-text answer (e.g., “fever, hypotens”) which is then evaluated by an AI using the GPT-4o model. Based on the evaluation, the user’s score is adjusted (+1 for correct, –1 for incorrect or timeout).

## Features

- **Rapid Drilling:** Learn to quickly assess pediatric vitals with one-line clinical scenarios.
- **Customizable Timer:** Adjustable answer time (1 to 10 seconds) via a slider. If the timer runs out, a –1 penalty is applied.
- **Immediate Feedback:** Visual feedback with a red screen flash for every incorrect answer.
- **AI Integration:** Uses the GPT-4o model via an API to evaluate free-text responses.
- **Lightweight & Accessible:** Simple design and hosted on GitHub for easy access and contribution.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, etc.)
- Basic knowledge of HTML, CSS, and JavaScript if you plan to customize or contribute
- **Note:** For production use, ensure you secure your API key (do not expose it in client-side code).

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/pediatric-vitals-drill-app.git
   cd pediatric-vitals-drill-app

