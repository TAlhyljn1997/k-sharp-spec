# K# v2.3 — Technical Specification (Zero‑Shimmer)

## 1. Overview
K# is a deterministic Vietnamese encoding protocol using ASCII‑only characters.  
It eliminates diacritic ambiguity and ensures 100% lossless reconstruction.

---

## 2. Encoding Pipeline

### 2.1 Onset Law
đ → y  
tr → j  
ch → f  
nh → z  
kh → q  
ng/ngh → w  
ph → p  
d = d  
th = th  
gi = gi  
qu = qu  

---

### 2.2 Rime Law
iêu → el  
yêu → yu  
ươi/uôi → ol  
uyên → yln  

---

### 2.3 Coda Law
ng → w  
nh → f  
ch → j  

---

### 2.4 CAP Matrix (Tone + Variant)
(… bảng 18 CAP giống README …)

---

## 3. Zero‑Shimmer Rules
- No inference  
- No normalization  
- No auto‑correction  
- Every syllable must end with exactly one CAP  

---

## 4. Lossless Decoding
Decoding reconstructs:
- Onset  
- Nucleus  
- Coda  
- Tone  
- Variant  

---

## 5. Examples
(… danh sách ví dụ encode/decode …)

