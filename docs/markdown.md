# Markdown segédlet

Egy rövid bemutató a Markdown fájlok megjelenéséről és képességeiről. 
Javasolt közben nézni a forrásfájlt, hogy lásd a szintaktikát: `docs/markdown.md`.

---

# H1
## H2
### H3
#### H4
##### H5

--- 

**félkövér!** __én is!__

*dőlt!* _olasz?_

***sok lesz a jóból...***

~~áthúzva~~

~a~lsó index

^f^első index

<u>aláhúzott</u>

[link](https://knowyourmeme.com/memes/trollface)

> idézet blokk
>
> My brain was granted a vision, my hand merely a vessel for a higher power's will.

---

# Listák 

Sorszámozatlan lista:

- mindig
    - van
        - lejjebb

Sorszámozott lista:

1. csak várj amíg
    1. codeblockot vagy képet szeretnél
        1. felsorolásba tenni (clueless)

Jelölőnégyzetek:

- [ ] feladat
    - [ ] a
    - [x] b
    - [ ] c

---

## Emotikonok

:skull: :fox: :raised_hand_with_part_between_middle_and_ring_fingers: :fire: :heart: :sparkles: :nail_care:

---

## Képek:

Sima: 

![base](impi_icon_kek.png)

Átméretezett: 

![sized](impi_icon_kek.png){height=32}

Inline: ![sized](impi_icon_kek.png){height=32}

Webről: 

![web based](https://hu.wikipedia.org/static/images/icons/wikipedia.png){height=32}

Sehonnan: 

![alt text]()

---

## [Admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/)

!!! note 
    Default title

!!! note ""
    No title

!!! quote "Idézet"
    Az kizárt dolog, mer' én nem tudom.

??? failure "Csukott"
    :fox:

???+ success "Nyitott"
    :fox:

---

## Billentyűkombinációk

++ctrl+shift+alt+super+l++

https://facelessuser.github.io/pymdown-extensions/extensions/keys/#extendingmodifying-key-map-index

---

## Code

Inline: `look mom im monotype`

Code block: 
```py
def main() -> str:
    return "Hello world!"
```

---

## Táblázatok

| a | b |
| - | - |
| 1 | 2 |
| 3 | 4 |

---

## Katex

> mert hát végülis miért ne xd

Inline: $e = m \cdot c^2$

Multiline:

\[
I =
\begin{bmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1 \\
\end{bmatrix}    
\]

$$
\displaystyle \sin \left(\alpha + \frac{\pi}{2} \right) = \cos(\alpha) 
$$
