ESVBibleWorkflow V 0.3
=======================

This workflow can do three things at the moment:
1) Search the ESV with verse reference
2) Search the ESV for all verses containing Keyword
3) Search the NASB with verse reference

1) To use the verse lookup utility, type in 'ESV' at the Alfred Prompt, with arguments: 

--- Book Chapter:Verse ---

Ex: ESV James

EX: ESV James 1:1

EX: ESV James 1:1-10

This should lead to a notification stating the verse, and also the verse copied to the clipboard should look like:
****
James 1:1 
James, a servant of God and of the Lord Jesus Christ, To the twelve tribes in the Dispersion: Greetings.
****

2) To use the keyword lookup utility, type in 'ESVS' at the Alfred Prompt, with any number of word arguments:

--- Word Word Word... ---

Ex: ESVS Before the Foundation

This should lead to a dropdown menu of verses that contain this keyword phrase. At the moment, words inside words will trigger a verse as well. 

Ex: 'wept' will trigger 'swept'

Please email me if you have any feedback/questions/suggestions!

*********
BUG LIST
*********

---Not a bug but...--- 
Verses with nice formatting, like the Psalms, will not show up formatted when copied to the clipboard because the ESV Online Bible does not return the verses as formatted in the first place
