# Spacy

## Implementation

**1. Tokenization**
- Spacy models -> https://spacy.io/models 

```python
nlp = spacy.load('en_core_web_sm')
text = "Hello KGP Talkie! Let's learn NLP together. I am 24."
doc = nlp(text)
```
**Output:**
```sh
Hello KGP Talkie! Let's learn NLP together. I am 24.
```