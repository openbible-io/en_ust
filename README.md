<img src="https://cdn.door43.org/assets/uw-icons/logo-ust-256.png" alt="drawing" width="100"/>

# unfoldingWord® Simplified Text - English

*an unrestricted simplified version of the Bible intended for translation into any language as a tool for use by Bible translators*

## Overview

The unfoldingWord® Simplified Text (UST) is an open-licensed adaptation of *A Translation For Translators* by Ellis W. Deibler, Jr., which is licensed CC BY-SA 4.0 (https://git.door43.org/Door43/T4T). The UST is intended to provide a simple, clear presentation of the meaning of the Bible without using any figures of speech, idioms, or other grammatical features that can be difficult to translate.

## Viewing

To read or print the UST, see the [UST project on Door43](https://door43.org/u/unfoldingWord/en_ust/).

## Contributors

If you are a contributor to this project please add your name to the `contributor`
field in the [manifest.yaml](https://git.door43.org/unfoldingWord/en_ust/src/master/manifest.yaml)
file.

## Introducing the UST

The unfoldingWord® Simplified Text (UST) is a meaning-centric version of the Bible in English. It is intended to be used alongside the unfoldingWord® Literal Text and other translation resources to give English-speaking mother-tongue translators (MTTs) a more complete understanding of the messages communicated in the Bible. For MTTs who do not have reading knowledge of the original biblical languages, the UST provides a sense of *what* these messages intended to communicate to the original readers. It is anticipated that the UST and other resources will be translated from English into the world’s Gateway Languages (GLs) so that MTTs worldwide can use them as a set of resources for making accurate translations of the Bible into their own languages.

### Avoid Translation Difficulties

The UST is designed to be used as a tool for Bible translation in conjunction with the [unfoldingWord® Literal Text (ULT)](https://git.door43.org/unfoldingWord/en_ult), the [unfoldingWord® Translation Words (UTW)](https://git.door43.org/unfoldingWord/en_tw), and the [unfoldingWord® Translation Notes (UTN)](https://git.door43.org/unfoldingWord/en_tn). It is not an end-user Bible, which seeks to transform all of the structures of the original biblical languages into those that are natural and idiomatic in the target language. Instead, unlike the ULT and unlike an end-user Bible, the UST does not use figures of speech, idioms, abstract nouns, or grammatical features that are difficult to translate into many languages.

The purpose of the UST is to show the plain meaning of all of those things wherever they occur in the ULT. By using both the UST and the ULT together as resources for translating the Bible into a target language (called an Other Language [OL] in this brief), the OL translator will be able to see the figures of speech, idioms, and other forms of the original Bible in the ULT and also see what their meaning is in the UST. Then he can use the figures of speech or other forms from the ULT that are clear and natural in his language. When the forms in the ULT are not clear or natural in his language, then he can choose other forms in his language that have the same meaning as expressed in the UST translation (or in the Translation Notes).

The primary goal of the UST is to express the meaning of the Bible as clearly as possible. In order to do this, it follows these guidelines.

The UST must avoid:

* Idioms
* Figures of speech
* Events out of order
* Complex sentences
* Passive voice
* Abstract and/or verbal nouns

Furthermore, the UST must explicitly include:

* Participants where these are unclear
* Implied information that is necessary for understanding

Therefore, when you (an editor or translator of the UST) edit or translate the UST, you must not use these grammatical features that the UST must avoid in the GL translation. The purpose of the UST is to change all of those problematic grammatical features into more universal ones to make them easier to translate. Also, you must be sure to include all of the named participants and the information that has been made explicit so that the meaning can be as clear as possible.

### Examples


For examples see the [Examples](https://gl-manual.readthedocs.io/en/latest/gl_translation.html?highlight=examples#id3) portion of the Gateway Language Manual.


## Editing the UST


See [Specific Editing Guidelines for the UST](https://gl-manual.readthedocs.io/en/latest/gl_guidelines.html#specific-editing-guidelines-for-the-ust) in the Gateway Language Manual.


## Translating the UST from the Original Language (OrigL)

### Translation of Terms Regarding Gender

Both Biblical Hebrew and Koiné Greek utilize different word forms to indicate grammatical gender, which may or may not correspond to the actual gender of a person or object. For example, the Hebrew phrase *beney yisrael* (“sons of Israel”) sometimes literally means “male children of the man named Israel” (Gen 42:5). However, most of the time in the Old Testament this phrase refers figuratively to the entire Israelite nation as a whole, both men and women. In a similar way, the Greek term *adelphoi* (“brothers”) can sometimes literally mean “a male person who has the same father and/or mother” (Mark 3:32), but most of the time in the New Testament refers figuratively to Christian believers, both men and women. In both Hebrew and Greek, the meaning of “engendered language” is not always clear. This linguistic feature of “engendered language” poses significant problems for translation; the meaning of the original Hebrew or Greek text is not always clear; also, some languages do not use engendered language, which makes the translation of gender very difficult.

The UST should reflect as accurately as possible the actual intended referent(s) for Hebrew/Aramaic/Greek terms, as determined from the context. As a general rule, the UST should select gender-neutral language except in cases where the context implies a specific gender is in view. However, sometimes the UST may need to deviate from this general rule; in those cases, the meaning should be explained in a Translation Note.

### Translation Glossary for the UST

See the [Combined ULT-UST Translation Glossary](https://gl-manual.readthedocs.io/en/latest/gl_guidelines.html#combined-ult-ust-translation-glossary) in the Gateway Language Manual.

## Aligning the UST

In the tC (translationCore) Word Alignment tool, the GL (Gateway Language) chapters and verses are listed down the left side. When you click on a verse to open it, the words of that verse appear in a vertical list, ordered from top to bottom, just to the right of the list of chapters and verses. Each word is in a separate box.

The words of the OrigL (Greek, Hebrew, or Aramaic) text for that verse are also in separate boxes in a field to the right of the English word list. There is a space under each of the source word boxes outlined with a dotted line.

### Alignment Process for the UST

To align the English text:

* Click and drag each word box of the English text into the space under the word box of the OrigL text that the English word corresponds to.
* Drop the English word by releasing the mouse button.

When the English word is over a word box of the original, the dotted outline will turn blue to let you know that the word will drop there. If you make a mistake or decide that the GL word belongs somewhere else, simply drag it again to where it belongs. GL words can also be dragged back to the list.

When the same GL word occurs more than once in a verse, each instance of the word will have a small superscript number after it. This number will help you to align each repeated GL word to the correct original word in the correct order. **When aligning, check to ensure that these numbered words are in their proper places, since it is easy to miss the numbers and align repeated words incorrectly.**

#### Process to Merge and Unmerge Original Language Words

tC (translationCore) supports one-to-one, one-to-many, many-to-one, and many-to-many alignments. That means that one or more English words can be aligned to one or more OrigL words, as necessary to get the most accurate alignment of the **meaning** conveyed by the two languages.

* To align multiple GL words to a single OrigL word, simply drag and drop the GL words onto the box below the desired OrigL word.
* When it is desired to align English word(s) to a combination of OrigL words, first drag one of the combination OrigL words into the same box as the other OrigL word. Multiple OrigL words can be merged together in this fashion.
* To unmerge previously merged OrigL words, drag the rightmost original language word slightly to the right. A small new alignment box will appear, and the unmerged word can be dropped into that box.
* The leftmost OrigL word can also be unmerged by dragging and dropping it into the OrigL word box immediately to its left.
* Any English words that were aligned with that OrigL word return to the word list.
* The OrigL words should remain in the proper order. If the merge contains 3 or more OrigL words, unmerge the rightmost OrigL word first. Un-merging the center word(s) first may result in the OrigL words becoming out of order. When that happens, unmerge the remaining words in that box to properly return the OrigL words to their original order.

### Alignment Philosophy for the UST

Because each GL has different requirements for sentence structure and the amount of explicit information that must be provided, there is often not a one-to-one correspondence between an OrigL word and an English word. In these cases, the English words that are provided should be aligned with the OrigL word that implies them.

The main objective and goal of text alignment for the UST is the same as for the ULT. However, the process by which to decide which UST words should be aligned with which OrigL words is significantly more complex than for the ULT. The process is not systematic but must be done by weighing a core group of principles together as a whole and then deciding what is best in each instance. Sometimes these principles might disagree or even contradict. In those cases, the aligner must decide which principle takes priority in a given instance and align the UST text accordingly. **For all these reasons, the UST aligner should expect that it will take multiple attempts at aligning a UST text before it is aligned properly.** The general principles which should govern the alignment of a UST text are as follows:

* The overarching purpose of the UST alignment is to show the user from which OrigL words (or groups of words) the GL words (or phrases) take their meaning. Sometimes these units of meaning are larger, and sometimes they are smaller.
* Smaller units of alignment are more desirable than larger units of alignment. In other words, only merge OrigL words together when necessary for the sake of alignment of meaning between the two languages.
* If the meaning of an OrigL word(s) is nowhere represented in the English text, leave that word unaligned rather than merging it with another OrigL word. If necessary, consult with the translator who prepared the UST to determine if the UST is missing elements of meaning that need to be included and then aligned to the OrigL word(s) in view.
* As much as possible, English words should be aligned with OrigL words within that same phrase or clause rather than being moved into a different phrase or clause.
* Words in English that express implied information can be aligned with earlier OrigL words but not with later OrigL words. This is because it is impossible for information to be implied from a place later in the text.
* In some cases, such as for a rhetorical question, the basic unit of meaning for alignment consists of an entire phrase or clause. In these cases, the entire unit of meaning must be merged in the OrigL and then aligned with the entire unit of meaning in the GL text.

**NOTE: Sometimes words in the UST will need to be aligned with OrigL words which appear much earlier or much later in the text. This is often necessary because of the specific rules that the UST must follow (use short sentences, present events in chronological order, etc.). The aligner should be aware that a properly aligned GST text may appear to have words drastically out of place at first glance.**

When aligning the UST, you must remember that its first priority is to be a clear rendering of the meaning of the OrigL text. Therefore, it adds words and phrases to explain the meaning of the original for the reader. These words and phrases should be aligned with the word or words that they are explaining. For example, in Titus 1:1, the phrase, “I am a servant” must be aligned with the single word, *doulos*.

Sometimes, for the sake of clarity, the UST will repeat things that are only mentioned once in the original. This often happens with subjects or objects of sentences. For example, in Titus 2:9 the English UST refers to “their masters” twice, although the original language only has *idiois despotais* once. In these cases, you should align each occurrence of the repeated reference with the same original language words, so that the highlighting will show that each of these represents the meaning conveyed by those same words of the original.

Some of the words and sentences of the UST do not directly represent the meaning of the original words. This is information that is only implied by the original words, but included in the UST because it is necessary for understanding the meaning of the original. For example, in Titus 1:1, the sentence, “I, Paul, write this letter to you, Titus” includes information that is not there in the original words, such as the fact that what the reader is about to read is a letter, and that it is written to someone named Titus. This information, however, makes the text more clear and understandable. For the aligning, then, all of this explanation must be aligned with the single word that it is explaining, *Paulos*.

If you notice places where the UST is wrong or potentially wrong, create an issue for it at https://git.door43.org/unfoldingWord/en_ust/issues so we can address it in the next release. In the meantime, align the text as well as possible.

For English, we follow these principles, but your GL may need a different list to support full alignment.

* Align indefinite articles to their “head word.” For example, both “a” and “servant” should align to *doulos* in Titus 1:1.
* Definite articles that English supplies should also be aligned to their “head word.” For example, both “the” and “faith” should align to *pistin* in Titus 1:1.
* Original language definite articles that English does not use need to be combined with their OrigL head word. For example, *ton* and *logon* need to be combined, then “word” aligned with that combination in Titus 1:3.
* Implicit verbs in the OrigL that are translated explicitly in the target language should be aligned with the predicate. For example, “he should be” that is supplied in English should be aligned to *philoxenon* along with “hospitable” in Titus 1:8.
* Words with apostrophes will be split and show up as two words in the word panel. This allows for proper alignment of the two parts of meaning. In most cases in English these are used to represent possession and will be aligned to a single original language word in the genitive case. For example, both “God” and “s” will align to *theou* in Titus 1:1.
* Often the OrigL and English part of speech won’t match. That is inevitable. Often an OrigL word will be translated as an English phrase. For example, the three words “does not lie” in English all align with the single word *apseudes* in Titus 1:2.
* Sometimes particles in the OrigL are not translated in English. These should be aligned to make the alignment between the OrigL and English as precise as possible. For example, in most cases the Hebrew direct object marker should be merged with the Hebrew direct object and aligned with that translated word in English. However, in cases where the direct object marker has a conjunction prefix that must be translated in English, then the Hebrew word containing the conjunction and direct object marker should be aligned with the translated conjunction in English.
* When aligning verbal negations, align any English helping verbs with the OrigL verb. Only align the English term(s) of negation with the negative particle in the OrigL.

Other alignment issues pertinent to Biblical Hebrew include the following:

* When an infinitive absolute is paired with a finite verb, the infinitive absolute should be aligned separately, if possible. Usually, the infinitive absolute will be translated as an adverb, and it should be aligned with the adverb.
* As a general rule, the ULT should translate the conjunction in Hebrew verbal forms. The translated conjunction should then be aligned with that Hebrew verb.
* When aligning construct phrases in Hebrew, the English word “of” should be aligned with the construct noun, and any English definite article should be aligned with the English term that they modify. If the meaning of the English rendering of the Hebrew construct phrase can be divided in the same way as the division of terms in Hebrew, then Hebrew terms should not be merged together in the alignment. However, if the meaning of the English rendering cannot be divided in the same place as the Hebrew phrase, or if the entire Hebrew phrase constitutes a single unit of meaning, then the applicable Hebrew terms must be merged together in the alignment.
* When aligning a verbless clause in Hebrew, the supplied “to be” verb should usually be aligned with the predicate instead of the subject. An exception to this rule occurs when the subject is a demonstrative pronoun (or carries some sort of deictic function). In those cases, the supplied “to be” verb should be aligned with the subject of the verbless clause.
* Sometimes a verb in Hebrew requires an accompanying preposition that is not required in English, or vice versa. In these cases, align with whichever part of speech fits best on a case-by-case basis. For example, take the phrase “...to pay on our fields...” in Nehemiah 14:4 (UST). The English preposition “on” fits better semantically with the noun (“on our fields”) rather than with the infinitive (“to pay on”). However, the reverse is true in v.15 in the phrase “...even their servants oppressed the people...” (Heb. שׁלטוּ על־העמ). In this case, the Hebrew שׁלט requires an accompanying preposition, and the concept is already incorporated into the English translation of the verb itself, “oppressed.” So in this case, it is best to merge the Hebrew verb and preposition together, then align both with the English “oppressed.”

### Words Not Found in the Original Language

In the process of alignment according to the instructions above, you may find that the English text has words or phrases that do not represent any meaning in the OrigL text and are not there because the English sentence needs them to make sense. If this occurs, follow these recommendations:

* If possible, consider editing the English text to match the OrigL text.
* You may consult other Greek or Hebrew manuscripts to see if there is textual support for your translation (see the `Biblical Humanities Dashboard <http://biblicalhumanities.org/dashboard/>` for other manuscripts).
* If you find support for your translation, make sure to include a comment or note about where you found it and why the translation should include it.
* You should consider placing these English words in brackets or in a footnote.
