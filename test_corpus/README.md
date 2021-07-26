# Test corpus for Pite Sámi syntactic analysers

The test set contains 150 sentences from 4 recordings (used with permission):
pit080708b, pit080924, pit100404, sje20150329b

Source of recordings:

Wilbur, Joshua. 2009. Pite Saami: documenting the language and culture. Endangered Languages Archive. Handle: http://hdl.handle.net/2196/00-0000-0000-0003-1170-E. Accessed on 2021-07-24.

Multiple utterances in the recording which form one syntactic sentence are joined to form one sentence in the test; 
punctuation and capitalisation are standardised; 
spelling errors in the transcription are corrected.


Input for the test is morphologically analysed and disambiguated text in CG-3 format (IN.cg3).
The gold standard for the GiellaLT annotation scheme is GOLD_GT.cg3, the Universal Dependencies gold standard is GOLD_UD.cg3.

Results are obtained by running the input through _functions.cg3_, _dependency.cg3_ (= RES_GT.cg3) and the conversion grammar _GT_UD_conv.cg3_ (= RES_UD.cg3).

For better readability, morphological features are not converted to UD (e.g. PrsPrc would become Tense=Pres VerbForm=Part).
AFTER-SECTIONS feature_substitution (lines 833 to 909) from GT_UD_conv.cg3 is therefore excluded.

RES_UD.conll is the test corpus in Universal Dependencies CoNLL-U format.
