# Quantitative Reasoning with Data

This project was an academic group project under the GEA1000: Quantitative Reasoning with Data module


---

## Part A: Journal Article Evaluation

### **Study Overview**
- **Aim**: Investigate association between cognitive function and traumatic upper-limb injuries.  
- **Variables**:  
  - **Independent**: Traumatic upper-limb injury (measured via pain level, hand function, etc.).  
  - **Dependent**: Cognitive function (measured via RAVLT and SCWT tests).  
- **Key Finding**:  
  > "Individuals with traumatic upper-limb injury had greater cognitive deficits in short-term memory than uninjured individuals."  

### **Methodology**
- **Subjects**:  
  - **Observational Group**: 104 patients from Guangdong Work Injury Rehabilitation Hospital.  
  - **Control Group**: 104 uninjured individuals from the local community.  
- **Target Population**: Individuals with traumatic upper-limb injuries.  

### **Critical Analysis**
- **Confounders Controlled**: Age, sensory damage, medical history, mental status.  
- **Uncontrolled Confounder**: Sleep quality before testing.  
- **Hypothesis Testing**:  
  - **Null (H₀)**: No association between injury and cognitive function.  
  - **Alternate (H₁)**: Association exists.  
  - **Conclusion**: Insufficient evidence to reject H₀ (no significant difference in executive function).  

### **Strengths & Limitations**
| **Strengths**                          | **Limitations**                                  |
|----------------------------------------|--------------------------------------------------|
| Rigorous exclusion criteria.           | Limited cognitive assessment methods (RAVLT/SCWT only). |
| Acknowledged potential confounders.    | No pre-injury cognitive function data.           |

### **Generalizability**
- Findings apply only to patients from Guangdong due to geographic and sampling constraints.

---

## Part B: Spotify Data Analysis

### **Dataset Overview**
- **Size**: 1,343 songs (2000–2020).  
- **Variables**:  
  - **Categorical**: `Genre`, `Explicit`, `Key`.  
  - **Numerical**: `Danceability`, `Energy`, `Tempo`, `Popularity`.  

### **Key Analyses**
1. **Tempo Categorization**  
   - **Fast** (120–168 BPM) was most common (42%).  
   - **Mode**: Correctly identified as the category with highest proportion.  

2. **Valence Classification**  
   - **Happy** (valence ≥ 0.5): 51.6% of songs.  
   - **Basic Rule**: `rate(Happy)` varied by mode (e.g., 49.4% for minor vs. 52.6% for major).  

3. **Danceability vs. Tempo**  
   - **Moderate tempo** (76–108 BPM) showed highest danceability.  
   - **Outliers**: Extremely slow/fast tempos had limited data.  

4. **Explicit Content & Happiness**  
   - **Association**: `Not Happy` songs had slightly higher explicit content (51.1% vs. 48.9%).  

5. **Acousticness vs. Energy**  
   - **Overall**: Strong negative correlation (r = -0.713).  
   - **Genre Variations**:  
     - Strongest in Metal (r = -0.915).  
     - Weakest in Reggae (r = -0.307).  

6. **Hypothesis Test: Rock Song Length**  
   - **Claim**: Average length = 255,000 ms (4m15s).  
   - **Result**: Rejected H₀ (p < 0.001); actual mean = 228,678 ms.  

### **Additional Analysis**
- **Confounder Check**: `Mode` (major/minor) confounds `Danceability` vs. `Tempo` association.  

### **Limitations**
1. **Sampling Bias**: First 1,000 songs per sub-genre may not represent all music.  
2. **Non-Probability Sampling**: Songs beyond the first 1,000 had no chance of selection.  

---

## Visualizations
- **Boxplot**: Danceability across tempo categories.  
- **Scatterplot**: Acousticness vs. energy (with genre stratification).  

---

## 🔍 Key Insights
- **Ecological Fallacy Example**: Overall negative `Acousticness-Energy` correlation masked weak associations in specific genres (e.g., Regional Mexican Music).  
- **Data Constraints**: Small sample sizes for extreme tempo categories reduced reliability.  

---

## Project Timeline
| Week       | Task                          |
|------------|-------------------------------|
| 4          | Data released.                |
| 5–10       | Analysis period.              |
| 10/11      | Report submission.            |
| 11/12      | Presentations.                |
| Reading Week | Peer evaluations.          |
