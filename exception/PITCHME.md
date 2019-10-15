## ITI0102 - Programmeerimise algkursus
### Erind
#### _Exception_
##### Ago Luberg

---


## Erind (_exception_)

- Erind on programmi töö käigus tekkiv ootamatu olukord (näiteks viga)

- Programmikood on süntaktiliselt korrektne, aga programmi käivitamisel tekib töö käigus viga

---

## Erind

- Paljud erindid ei ole programmi töö jaoks tingimata fataalsed (_unconditionally fatal_)
- Teatud juhtudel saab programmi tööd jätkata, kui eriolukord suudetakse lahendada
- Paljusid erindeid saab töödelda ja seda tegevust nimetatakse erinditöötluseks (_execption handling_)

---


@snap[west]
## Erind

```python
import math

def calculate_square_root(value):
    return math.sqrt(value)

# ... ask for user input
# user enters -1
user_input = -1

calculate_square_root(user_input)
```
@snapend


---

# Küsimused?

---