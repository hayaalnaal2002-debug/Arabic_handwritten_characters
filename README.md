# DARBAK – Arabic Language Learning App Dataset

This repository contains the **handwritten numbers and letters dataset** used to train the **DARBAK Arabic Language Learning App for Children**. The app is designed for children aged 5–13, teaching Arabic letters, numbers, colors, and basic vocabulary through an interactive, game-like experience.

---

## App Overview

- **Interactive learning:** Reading and writing exercises with a game-like interface.  
- **AI assessment:** Handwriting and pronunciation evaluation using image and voice recognition.  
- **Data collection:** Voice and handwriting data collected from multiple kindergartens and schools to build a diverse and representative dataset.

---

## Dataset Experiments

The letters dataset was divided into **5 different experiments**, each using a unique grouping strategy to optimize model performance:

1. **Experiment 1 – Grouping Similar Letters**  
   - Similar letters grouped together, dissimilar letters separate.

2. **Experiment 2 – Distributing Dissimilar Letters**  
   - Dissimilar letters distributed into compatible groups.

3. **Experiment 3 – Separating Highly Similar Letters (Final Selected Experiment)**  
   - Highly similar letters grouped (e.g., س & ش, ص & ض).  
   - **Train Accuracy:** 87.39%  
   - **Test Accuracy:** 87.64%  
   - ✅ Selected as the final dataset for the mobile application.

4. **Experiment 4 – Letter Position-Based Groups**  
   - Groups based on letter positions in words (Start, Middle, End, Isolated).

5. **Experiment 5 – Separate Classes for Each Letter Form**  
   - Each letter form treated as a separate class.

---

## Numbers Dataset

- **Total images:** 4,736  
- **Digits:** 0–9  
- Note: Numbers dataset remained unchanged across all experiments.

---

## Notes

- The final dataset from **Experiment 3** was used to train AI models integrated into the DARBAK mobile application.
- This dataset supports AI-based handwriting recognition and interactive learning for Arabic language education.
