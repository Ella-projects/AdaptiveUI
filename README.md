**Interactional Guardianship: A State-Aware AUI Framework**
Sensing Cognitive Stutter and Fatigue to Mitigate Implicit Bias in Clinical Decision-Making

**1. The Problem: The "State-Blind" Interface**
Current Electronic Health Records (EHRs) treat every clinician interaction as a static, rational event. However, clinical data confirms that Implicit Bias leads to catastrophic outcomes:

Cardiology: Women are 2.5× less likely to be referred to a specialist despite equal symptom prevalence.

Maternal Health: Black women face a 212% higher mortality risk than white women.

The Catalyst: These disparities are amplified by Fatigue, which collapses "System 2" (Analytical) thinking and triggers a reversion to "System 1" (Heuristic/Biased) shortcuts.

**2. The Sensing Engine: The "Cognitive Stutter"**
The framework identifies bias not as an opinion, but as Kinetic Friction. When a clinician encounters a patient profile that contradicts a subconscious prototype, a "Cognitive Stutter" occurs.

**Mathematical Modeling**

ΔRT (Reaction Time Gap): The millisecond-level delay incurred during counter-stereotypical processing:

ΔRT=RT incongruent −RT congruent
​	
Mouse Path Tortuosity (τ): A kinematic biomarker of uncertainty. The system measures "Path Curvature" as a proxy for neuromuscular jitter caused by cognitive conflict.

The Fatigue Multiplier (W fatigue): Implicit bias (S bias) is a latent threat; fatigue is the trigger. We model the Probability of Error (P) as:

P=(W fatigue ×S bias) 
As fatigue increases, the threshold for intervention (α) dynamically lowers.

**3. The Architecture: Three-Way Decision (3WD) Framework**
The system analyzes telemetry in 5-second sliding windows to determine the intervention state:

Negative Region (P≤β): Transparency. No intervention; flow parity maintained.

Boundary Region (β<P<α): Guidance (Soft Nudges). * Saliency Shifts: Highlighting diverse symptoms.

Randomized Option-Ordering: Breaking first-order bias.

Positive Region (P≥α): Guardianship (Hard Nudges). * 3000ms Speed-Bump: Temporary functional lock of "Submit" CTA.

Synchronous Modal Alerts: Forcing a metacognitive reset.

**4. Privacy & Ethical Guardrails**
Local Edge Processing: Raw (x,y) telemetry is processed locally; only derived feature windows are stored to protect the clinician's "Kinematic Fingerprint."

Anonymization: SHA-256 session hashing and Temporal Noise Injection (±500ms) prevent re-identification through shift rosters.

Non-Evaluative: The AUI is a real-time safety net, not a performance auditing tool.

**5. Key Research & Background Reading**
Foundational Theory

: The original framework for measuring ΔRT and subconscious pairing (Greenwald et al.).

: Daniel Kahneman’s Dual Process Theory (System 1 vs. System 2).

: Croskerry (2013) on how clinical heuristics lead to diagnostic error.

Clinical Disparity Evidence

: Analysis of treatment intensity gaps in NSTEMI patients.

: Study on how false beliefs about biological differences impact Black patients.

: Obermeyer et al. (2019) on how resource-allocation algorithms under-predict need for Black patients.

HCI & Kinematic Sensing

: Research into how kinematic jitter correlates with mental effort and conflict.

: Privacy considerations in biometric and behavioral sensing.

extensive reaserch here : https://docs.google.com/document/d/11s_qC638h5ygrDBq3pjDmrdRENJvbJ1BeZ_Zl_DBWTc/edit?tab=t.0

By Emmanuella Daramola 
