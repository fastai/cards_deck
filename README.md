# Deck of Cards



## Install

`pip install deck_of_cards`

## How to use

Playing cards in python!

```python
from deck_of_cards.deck import Deck
d = Deck()
```

```python
d = Deck()
print(f'Number of playing cards in the deck: {len(d.cards)}')
```

    Number of playing cards in the deck: 52


```python
card = d.pop_card()
print(card)
```

    King of Spades


See the docs on `Deck` for more info.
