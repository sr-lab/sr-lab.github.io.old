---
layout: default
show_home: true
---

# Password Quality
A number of utilities we use for research into password quality/strength are listed below.

## Pwned Passwords API Wrapper
A library that can be used to query [Troy Hunt's](https://troyhunt.com/) [Pwned Passwords API](https://haveibeenpwned.com/API/v2) or a local copy of its database. The database file is >30GB in size so a library/utility like this is necessary in many cases to meaningfully interact with it, (opening it in most text editors will just cause an error or crash the program). [Check it out on GitHub...](https://github.com/sr-lab/pwned-api-wrapper).

## Ampasamp
Ampasamp (**a** **m**inimal **pa**ssword **samp**ler) is a software utility designed to sample passwords from large breached password datasets that comply with a set of password policies. [Check it out on GitHub...](https://github.com/sr-lab/ampasamp)

## Capitalizer
Capitalizer is a capital letter (and symbol) heat-mapper and password capitalisation utility. This repo is a bit of a mix, and contains several projects. [Check it out on GitHub...](https://github.com/sr-lab/capitalizer)

## Entropy Calculator
Extensible batch password entropy calculator. This utility will take a text files as input and calculate some score for each string contained in it, one per line. [Check it out on GitHub...](https://github.com/sr-lab/entropy-calculator)

## Guesser
Sometimes you just need a super-simple list-based password guesser that will take a plaintext list of guesses, a plaintext list of attacks and tell you how many guesses you got right. Takes two lists, one of guesses and one to be guessed, and tells you how many matches turn up. Does some other small stuff like deduplicating guesses. [Check it out on GitHub...](https://github.com/sr-lab/guesser)

## Count Expander
A utility that re-hydrates password lists that contain counts. Also contains a utility that will do the opposite and dehydrate a raw password dump into a file of counts (frequencies) against passwords. [Check it out on GitHub...](https://github.com/sr-lab/count-expander)
