# Deck of Cards
> A minimal example of using nbdev to create a python library.


{% include important.html content='This file was automatically generated from a Jupyter Notebook using [nbdev](https://nbdev.fast.ai/). to change it you must edit [index.ipynb](https://github.com/fastai/deck_of_cards/blob/master/index.ipynb).' %}

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
