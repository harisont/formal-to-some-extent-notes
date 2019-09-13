% Formal-to-some-extent notes
% Arianna Masciolini

# Introduction to Formal Linguistics

- FL is only formal to some extent, so not as a binary notion linguistics. This is due to the fact that the object of study is natural language, which is ambiguous -> levels of “formalness”
- Precursors: 

  - Pāṇini (Sanskrit philologist, IV century BCE)
  - various Greek philosophers
  - XIX century: 
    - historical & diachronic perspective
    - Hermann Paul: compositionality (sentences are the sum of their parts, not quite true but useful)
  - XX century: Saussure -> Synchronic (…)
- Pioneer: __Noam Chomsky__ (mid 50s) - principal contributions:
  - Syntactic structures (using mathematical tools in language analysis)
  - Chomsky hierarchy
  

# Overview of linguistics

## Methods

- _corpus_ linguistics (= study of language as expressed in _corpora_ of "real world" text. If collected in natural context (_realia_), effectiveness improves)
- formal analysis
- experimental methods (a wide variety)
- ethno-methodology (= conversation analysis, i.e. just observe language in context, used in anthropology)

## Subfields

Main subfields:

- **Phonetics** (deals with the _production of speech sounds_)
  - articulatory -> IPA chart (phonetic alphabet)
  - acoustic (physics side of things)
- **Phonology** (is about _patterns of sounds conveying a meaning_) -> phonemes, phonological rules
- **Morphology** (= study of the different forms words have, no clear boundary with syntax, cf. compounding in German and Swedish)
  - inflectional: about different forms in a paradigm, singular VS plural, feminine vs masculine…
  - derivational: about how to create new words from existing ones (possibly in another category, e.g. adjectives from nouns)
- **Syntax/Grammar** (= set of [formally expressed, assuming that natural language is context free] structural rules governing the composition of clauses, phrases and words)
- **Semantics** (= study of the meaning) (uses propositional & first order logic, model theory (somehow closely related to set theory) and inference (formal & pragmatic, i.e. common sense inference)
- **Pragmatics** (= study of language _in use_): difference between what we say & what we communicate, dynamic meaning
- **Lexicon** (= inventories of words [+ idioms])

Secondary subfields:

- historical linguistics
- comparative linguistics & typology
- (…)

# The origins of language

There is a lot of speculation on the origin of language (but not a definitive explanation) - possible sources:

- __divine__ (cf. Genesis & Hindu traditions) -> numerous vain attempts to rediscover the (only) original divine language (before Babel)
- __natural sounds__:
  - “bow-wow” theory (based on onomatopoeia): does not explain words for silent objects or abstract concepts, assumes that language is only a list of names for things
  - “pooh-pooh” theory (based on instinctive sounds people make in emotional circumstances): these sounds are emitted in a way which differs significantly from speech (when we inhale, not when we exhale)
- __social interaction__ -> “yo-he-ho” (= “oh issa!”) theory (sounds used to coordinate a physical effort) (good idea, but still, what is the source of these sounds?)
- __physical adaptation__ (evolution of teeth, lips, tongue, larynx, pharynx and so on)
- __tool making__ (based on the fact that the areas of the brain and brain activity involved in complex vocalisation and tool making are remarkably similar)
- __genetic__ (__innateness hypothesis__)

# Miscellaneous & my own thoughts

- > noun, verb, adjective… : types = sentence, syntagm… : composition type (similar to types & function types?)

- language differ only to some extent -> **real & statistical _language universals_**

- not so easy to define what a native speaker is

---

# Morphology

> __Morphology__ = the study of words: what they are how they are formed and their different forms

In language technology, it is involved in:

- analysis: parsing, speech recognition, machine translation
- generation: language generation, machine translation

## Leading figures

1.  Pāṇini (India, IV century BCE), Greek and Arabic authors
2.  De Saussure (Switzerland, late XIX and early XX century)
3.  Bloomfield (USA, early XX century)
4.  Roman Jakobsson (Prague school, Czech Republic, first half of the XX century)

## Essential vocabulary

- _Lexeme_ = abstract lexical entity consisting of __form + meaning__. It represents a
  set of forms (note: this is according to the slides. I actually think that a better definition would be: “__basic unit of a language with *lexical meaning*__ consisting of one or several words, the elements of which do not separately convey the (lexical) meaning of the whole”)
- _Root_ = basic part of a lexeme not further analysable either in terms of inflectional or derivational morphology, always present in every form (note: compounds have two roots)
- _Stem_
- _Lemma_ = basic form that represents the word e.g. in a dictionary
- _Word form_ or _orthographic word_ = a certain form of a certain lemma (e.g. the feminine form of an adjective in Italian, the bestämd form of a Swedish word or the past simple of an English verb)
- _String_ = sequence of characters
- _Morpheme_ = smallest meaningful unit (of a word). By _meaningful_, we refer both to lexical and grammatical (see below), e.g. the word “unfair” is composed of two morphemes (“un” + “fair”). They are divided into:
  - _free_ (standalone) morphemes
  - _bound_ morphemes: prefixes, suffixes, infixes, circumfixes. The _base_ of a word is the part to which bound morphemes are attached.
- _Morph_ = A phonetic (and sometimes orthographic) representation of a morpheme. Different morphemes associated with the same meaning are called _allomorphs_. Examples:
  - the plural of the Swedish word “**fågel**” is “**fågl**ar”. “Fågel” and “fågl” are then allomorphs
  - “-s” and “-es” are allomorphs of the English plural morpheme

## Content vs function words

- _Content words_: __words with a clear *lexical meaning*__ (nouns, verbs, adjectives. Note that these classes of words all are _open classes_, i.e. it is possible to add them new words)
- _Function words_ : __words__ with no clear lexical meaning, __which__ instead __specify grammatical functions and relationships__ (conjunctions, prepositions, articles, pronouns)

The brain treats content and functions words differently! In fact:

- Some aphasics are unable to read function words like “in” or “which”, but can read the lexical words “inn” and “witch”
- In early stages of development children often omit function words

## Word formation processes

- _Coining_ (= making up new terms)
- _Loan_ (from other languages): andante, oxymoron, balonvolea…
- _Calque_ or _loan translation_: e-post, skyskrapa, scannerizzare…
- _Acronym_: ISA (Instruction Set Architecture), FLOSS (Free, Libre and Open Source)…
- _Clipping_ (word shortening): math, fax, phone…
- _Blending_ of the first part of the word with the ending part of another: brunch, smog, bankomat
- _Compounding_: putting together 2+ lexemes that could function as independent words
- _Derivation_: process that __turns a word into another word__, often happens via _derivational affixes_ such as “-ism”. 
- _Inflection_: process that __creates a new word *form*__

### Derivation vs inflection

|                                                | __Inflection__                           | __Derivation__ |
| ---------------------------------------------- | ---------------------------------------- | -------------- |
| creates a new part of speech (change of class) | rarely                                   | often          |
| creates a new lexeme                           | yes                                      | no             |
| changes in meaning (?)                         | significant                              | modification   |
| semantic effect                                | sometimes hard to predict: odjur, oväder | predictable    |

## Morpheme analysis

1. Structure the word forms
2. compare two forms which are as similar as possible and identify their common-and-not features (morphs/morphemes)
3. check what role the morphs that have been isolated have in other forms
4. check that the isolated morphs are in fact morphs in that they are “minimum”  

## Typology (based on morphology)

Languages are grouped into categories based on morphology:

- **analytic**: one word, one morpheme, one meaning component (Chinese, English to a certain extent)

- **agglutinating**: one meaning per morpheme, words composed of several morphemes: (Turkish)
- **synthetic**
  - **inflectional**: several meanings per morpheme (Latin, Greek, English)	
  - **poly-synthetic**: a single word is possibly a sentence (Icelandic)
  - **non-concatenative**: base made of consonants, vowels infixed (Arabic, Hebrew)

## Morphology “problems”

- Where to split words? (“hoppa-r” or “hopp-ar”)
- what if there are multiple stems? (“vado”, “andare”)
- function or content? (“stor-het” vs “stor-lek”)
- what if identical morphs of the same lexeme indicate different morphemes? (e.g. Swedish adjectives terminate in “”-a” both in singular bestämd form and in plural obestämd form)

---

