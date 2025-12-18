# K# v2.3 – Zero‑Shimmer Deterministic Encoding Protocol

K# (K‑Sharp) is a deterministic, lossless Vietnamese encoding protocol designed to eliminate diacritic ambiguity (“shimmer”) and establish Equi‑State between AI and Humans within the RI‑Ecosys architecture.

## 🎯 Purpose
- Remove all ambiguity in Vietnamese diacritics  
- Provide a 1:1 reversible encoding  
- Reduce token cost for AI models  
- Standardize Vietnamese processing across systems  

## 🔒 Zero‑Shimmer Guarantee
Every Vietnamese syllable maps to exactly **one** K# code.  
Every K# code maps back to exactly **one** Vietnamese syllable.

## 🧩 4‑Layer Encoding Pipeline
1. **Onset Law**  
2. **Rime Law**  
3. **Coda Law**  
4. **CAP Matrix (Tone + Variant)**  

## 🔠 CAP Matrix (v2.3)
| Tone | Plain | Hat | Hook |
|------|:-----:|:---:|:----:|
| Ngang | N | Y | M |
| Sắc | S | T | X |
| Huyền | L | D | K |
| Hỏi | Q | B | V |
| Nặng | P | F | H |
| Ngã | Z | G | R |

## 🧪 Examples
- người → wolK  
- mạnh → mafH  
- yếu → yuS  
- trăng → jafwN  

## 📜 License
Distributed under MIT License (see LICENSE).

## 👤 Maintainer
Ba Phúc Trần — RI‑Ecosys  
