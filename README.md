# Deck of Cards
> This README was also made from a Jupyter Notebook!


This file will become your README and also the index of your documentation.

## Install

`pip install deck_of_cards`

## How to use

Playing cards in python!

```
from deck_of_cards.deck import Deck
d = Deck()
```

```
d = Deck()
print(f'Number of playing cards in the deck: {len(d.cards)}')
```

    Number of playing cards in the deck: 52


```
card = d.pop_card()
print(card)
```

    King of Spades


See the docs on `Deck` for more info.
