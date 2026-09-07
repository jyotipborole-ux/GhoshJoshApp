# GhoshJoshApp
Instrument Learning Platform
GHOSH JOSH (घोष जोश) — Design Specifications & Application Suite
The complete design specifications, screen designs, and interactive functional application for GHOSH JOSH for both Website Admin and Mobile Learner App.

Core System Architecture & Screen Designs-

A. Website Admin Portal (Curator & Content Operations)
Dashboard (AdminDashboard):
Real-Time Key Metrics: Active verified learners, pending approval requests, Vanshi flute compositions, and Aanak drum cadences.
Instrument-Wise Library Matrix: Visual breakdown for Vanshi (वंशी), Aanak (आनक), Shring (शृङ्ग), and Shankh (शङ्ख) with composition counts, sample Bols, and direct navigation.
Pending Approval Queue: Quick-review cards displaying learner name, Shakha affiliation, email, requested instrument, and one-tap Approve / Reject buttons.
Published Repository Table: Searchable catalog with Tala, Matras, BPM, notation summary, and live status.


Content Upload Studio (AdminContentUpload):
Instrument Selection: Dedicated cards for Vanshi, Aanak, Shring, and Shankh.
Metadata Engine: Title (English & Devanagari), classification (Prathama, Dwitiya, Uchha, Veer, Prabhat), Tala (Kaharwa, Teentaal, Dadra, Roopak), Matras, and default BPM.
Notation & Bol Input: Sargam swara parser (S R G m P D N S') and rhythmic Bol syllables (Dha Tit Dha Tit Ta Tit Dha Tit) with auto-tokenization.
Live Web Audio Synthesizer Preview: Test playback of both Bol Recitation and Instrumental Acoustics at varying speeds (0.5x, 0.75x, 1.0x, 1.25x, 1.5x) before publishing.


User Management & Permissions (AdminUserManagement):
Filter by approval status (All, Pending, Approved, Rejected) and search across name, Shakha, and city.
Learner Progress Inspector Modal: Drill down into any learner's rehearsal hours and 4-tier milestone status per Rachana.
Granular permission control to approve, reject, or revoke instrument access.


Profile & Security (AdminProfile):
Admin credential card with Shakha affiliation and role badges.
Change Password Form: Form with validation, confirmation checking, and security guidelines.



B. Mobile Learner App (End-User Experience)
Onboarding & Permission Verification (MobileAuth):
New learners create a profile specifying name, email, phone, city, Shakha, and requested instrument.
Approval Status Tracker: Real-time screen showing "Awaiting Admin Verification" until approved by Shakha Admin (with an instant sandbox simulation toggle).


Instrument Selector (MobileInstrumentSelect):
High-fidelity selection cards for Vanshi (Bansuri / Bamboo Flute) and Aanak (Ghosh Marching Drums) with acoustic sound preview buttons, descriptions, and enrollment badges.


Rachana Discovery (MobileRachanaList):
Filter compositions by difficulty (Beginner, Intermediate, Advanced) and Tala.
Live progress indicator rings showing the learner's mastery percentage on each card.


Interactive Rachana Player & Learning Studio (MobileRachanaPlayer):
Synchronized Sargam & Bol Reader: Visual grid with live beat and Matra tracking, highlighting Sam (✕), Tali, and Khali (○).
Dual Audio Listening Modes:
Listen to Rachana Bol: Vocal rhythmic recitation with speech synthesis and cadence pulse.
Listen to Rachana Instrumental: Pure acoustic simulation (bamboo flute harmonic series or dual-membrane snare/bass drum acoustic strikes).


Multi-Speed Tempo Controls: Selectable rates at 0.5x (Slow practice), 0.75x, 1.0x (Standard), 1.25x, and 1.5x (Fast parade).
