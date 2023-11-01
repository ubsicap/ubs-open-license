# Paratext Parallel Passages Database 

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

(UBS Parallel Passage Database, © 2023 United Bible Societies.)

This is a database with parallel passages in the Old and New Testament including OT quotes in the NT. The passages have been analyzed in detail and include numberings marking the words that have a more or less exact match in the other passage(s), including those that have a partial match. This database is the main underlying resource for the Parallel Passages tool in Paratext.

This is an example of a single parallel passage. This passage represents two parallel verses in the Old Testament (BHS) that are quoted in the New Testament (UBSGNT5).

<Passage>
    <Verse HEB="0000003000052222">GEN 1:27</Verse>
    <Verse HEB="222223003000003000">GEN 5:2</Verse>
    <Verse GRK="0000300012252222">MAT 19:4</Verse>
    <Verse GRK="202152222">MRK 10:6</Verse>
</Passage>

Every number represents a Hebrew or Greek word. In this database words are defined as units separated by a space or hard return. For Hebrew this means that two words that are written together, like in בְּרֵאשִׁית are considered a single word. Words that are separated by way of a maqqef are considered a single unit as well.

This what the numbers symbolize:

-	0: this word has no match in the other text
-	1: this word has a partial match in the other text
-	2: this word has a full match in the other text

The numbers 3-5 are equivalent to 0-3 but suggest the insertion of a new line. This is purely for presentation purposes and is not in any intentional way based on the published source texts.

The numbers 6-8 are equivalent to 0-3 but suggest the insertion of two new lines. This is purely for presentation purposes and is not in any intentional way based on the published source texts.

