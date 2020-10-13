# Read before you kern!
A text string to test fitting and kern Basic Latin.

The Text file includes strings that try to produce the most common - and important - kerning pairs in context for the Basic Latin character set (+ some Western/Eastern letters and diacritics). Provided that you choose your kerning classes wisely it aspires to give you a small in lenght but quite comprehensive set of words and examples which will help you kern:

- Uppercase to Uppercase
- Uppercase to punctuation
- lowercase to lowercase
- lowercase to punctuation 
- lowercase to Uppercase to lowercase
- numerals to numerals (limited set)
- numerals to punctuation (limited set)
- numerals to letters (limited set)

There are assumptions for the design (i.e. bdpq are presumed to belong to the same kerning class as o, however, it includes a and g in case the design features double story versions.) In case your bdpq vary significantly from the o then you should use search/replace in the kern strings and just create the required ones. 

Remember: You should be done with your fitting before kerning. The fact that you might see letter combinations does not mean you need to kern everything. Depending on the design, the intended use, and your own personal preference you should make the decision to kern all of the punctuation to letters, some, or none of it. The same applies for the numerals. A design that features tabular numerals shouldn't have any kerning - but hey, you know all this, why am I even telling you!

In some cases (pun intended) you might have case sensitive forms, so do check how these dashes look when you switch your case feature on.

This is a work in progress and I might come back to update it at some point. It is a cleaned up version of a text string that I use to test fitting and kern fonts. It is best suited for sans designs (texts and display) but with alterations and depending on the design it can work with serifs as well. The next update will include Vietnamese. Greek version is also on the works. 
