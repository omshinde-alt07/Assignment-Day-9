# Jaccard Similarity

## What is Jaccard Similarity?

Jaccard similarity is a statistical metric used to measure how similar two sets are.  
It compares the overlap between two sets relative to their total unique elements.

### Mathematical Formula

\[
J(A,B) = \frac{|A \cap B|}{|A \cup B|}
\]

Where:

- **A ∩ B** = elements common to both sets  
- **A ∪ B** = all unique elements from both sets  

### Value Range

| Value | Meaning |
|------|------|
| 0 | No similarity |
| 0–1 | Partial similarity |
| 1 | Identical sets |

---

# Where Jaccard Similarity is Used in Industry

## 1. Recommendation Systems

E-commerce platforms compare user purchase histories or product features using Jaccard similarity to recommend items that similar users interacted with.

## 2. Natural Language Processing (NLP)

It is used to measure similarity between documents by comparing sets of words or tokens.

## 3. Plagiarism Detection

Tools detect copied content by comparing the similarity of word sets between documents.

## 4. Search & Data Deduplication

Search engines and large data pipelines use Jaccard similarity to identify duplicate or highly similar records.
