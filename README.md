# Random Words from dictionary

Script to print a list of random words from a dictionary, for example "*people tiger dancing*".

It's useful, for example, to generate password made of more words. Simple to remember but hard to find with a *brute force attack*.



## Instructions

```bash
./random_words [ options ]
```

#### Options:

- -d  Dictionary full path (default: ./dictionary/dictionary_it.txt). If you need, in Linux there are other dictionary files in `/usr/share/dict/`
- -s  Separator (default: blank)
- -w  Number of words (default: 3)



## Examples

Easiest way:

```bash
./random_words
```

result: *dominai ritenersi cureresti*

With another dictionary:

```bash
./random_words -d /usr/share/dict/american-english
```

result: *furiously answer chilies*

Using and *underscore* like separator:

```bash
./random_words -d /usr/share/dict/american-english -s _
```

result: *buckle_gravelling_cupcake*

Generating more than 3 words, for example 6:

```bash
./random_words -d /usr/share/dict/american-english -s _ -w 6
```

result: *fertilize_foreordaining_Sufism_breathes_birthmark_impartiality*



