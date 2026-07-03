<div align="center">
  <img src="./assets/logo.png" alt="RAKEEZ Logo" width="250"/>
  <h1>RAKEEZ (رَكِيزْ)</h1>
  <p><strong>An Augmented Reality-Based Math Learning System for ADHD Students</strong></p>
</div>

## Project Overview:
**RAKEEZ** is an interactive AR-based educational system designed to support first-grade students with ADHD in learning foundational mathematics. The system creates a dynamic learning environment within the child's physical space, adapting task difficulty in real-time based on engagement, response accuracy, and movement stability.

## Key Objectives & Features:
1 - **Distraction-Free AR:** A safe and immersive learning environment tailored for first-grade math.
2 - **Sensory-Optimized Audio:** Utilizes a custom human voice clone (via ElevenLabs) for comforting, non-robotic guidance, combined with carefully curated, low-frequency auditory rewards (via Pixabay) to prevent sensory overload.
3 - **RakeezBrain (Adaptive AI):** The core logic engine that dynamically adjusts difficulty and deploys real-time intervention strategies if the child exhibits signs of frustration or tantrums.
4 - **RakeezAvatar Monitoring:** Acts as an active digital supervisor throughout the entire session.
5 - **Tiered Alert System:** Implements critical automated pauses during panic or severe hyperactive episodes (High Priority), alongside standard notifications for task completion (Normal Priority).
6 - **Real-to-Digital Reward Bridge:** Parents can review session results and manually trigger additional digital bonus points, effectively linking physical reinforcement with digital achievements.

## Tech Stack & Architecture:
1 - **Game Engine & Logic:** Unity 3D, C#
2 - **AR Framework:** AR Foundation, ARCore
3 - **Backend & Database:** Supabase (PostgreSQL for real-time sync)
4 - **Tracking:** MediaPipe
5 - **Authentication:** Authentica (WhatsApp 2FA for secure parent verification)
6 - **Audio Engineering:** ElevenLabs (Voice Cloning), Pixabay (Curated Acoustic Assets)

### System Architecture:
The system adopts a role-based architecture bridging students, parents, and teachers, ensuring secure data flow and adaptive learning.
<p align="center">
  <img src="./assets/system_architecture.png" alt="System Architecture and Diagrams" width="800"/>
</p>

## Rakeez Characters:
To ensure a calming and engaging experience, Rakeez features carefully designed companions:
<p align="center">
  <img src="./assets/badr.png" alt="Badr Character" width="200"/>
  <img src="./assets/batlah.png" alt="Batlah Character" width="200"/>
</p>

## System Interfaces:

### AR Gameplay Experience:
An intuitive AR interface that safely maps math challenges into the physical room.
<p align="center">
  <img src="./assets/ar_gameplay_1.jpeg" alt="AR Gameplay" width="250"/>
  <img src="./assets/ar_gameplay_2.png" alt="AR Gameplay Challenge" width="250"/>
</p>

### Parent & Teacher Dashboards:
Comprehensive reporting on academic progress and behavioral metrics (Focus & Calmness tracking).
<p align="center">
  <img src="./assets/parent_dashboard.png" alt="Parent Dashboard" width="250"/>
  <img src="./assets/behavioral_report.png" alt="Behavioral Report" width="250"/>
</p>

## Results & Evaluation:
Controlled evaluations demonstrated an overall comparative performance index of **90.0%** for the Rakeez method versus **64.9%** for traditional instruction, alongside significantly higher engagement and focus levels among students.
