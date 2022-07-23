# tgram

- Installing:   
`pip install tgram`

- Requirements:   
`requests`

# Sample Usage

```python
from tgram import detector

sentence = "This is a sample sentence."
word, detected = detector(sentence)

if detected:
    print(f"Profanity detected.\nWord: {word}")
```   

Made with 💕 by [@TeamUltroid](https://t.me/TeamUltroid).
