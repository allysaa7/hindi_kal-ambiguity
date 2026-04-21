# hindi_kal-ambiguity


## Problem

In Hindi, the word "kal" can mean:

* Yesterday (Past)
* Tomorrow (Future)

This creates ambiguity in Natural Language Processing (NLP).

---

## Solution

This project uses a **rule-based NLP approach** to detect the meaning of "kal" using keywords.

---

##  How it Works

* Checks for past tense words (e.g., *gaya, tha, kiya*)
* Checks for future tense words (e.g., *jaunga, hoga*)
* Returns:

  * Past → Yesterday
  * Future → Tomorrow
  * Otherwise → Ambiguous

---

##  Example

Input:
`kal mera presentation hey`

Output:
`Tomorrow (future)`

---

##  How to Run

```bash
hindi_kal_ambiguity.ipynb
```

---

## Files

* hindi_kal_ambiguity.ipynb
* output.txt

---

## Future Improvements

* Use machine learning instead of rules
* Handle more Hindi words
* Add voice input

---

## 🧠 Tech Used

* Python
* Basic NLP (rule-based)
