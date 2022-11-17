# Tunisian-Parser

TTB  (Tunisian Treebank): We syntactically annotated the Tunisian constitution, which contains 12.378 words, and 1.072 sentences of STAC corpus. It follows the CODA-TUN orthographic convention.
It is also well segmented and tokenized. The preprocessed corpus was analyzed syntactically by the Stanford parser of MSA. The final step in creating TTB is to fix annotation errors made by the MSA Stanford parser and validate it by experts.

The model (model_SMD.gz) was trained using 8.000 sentences and 79.604 tokens. The best evaluation result reached an F-measure of 80.12%. It can be used by integrating it into the Stanford parser (Link: https://nlp.stanford.edu/software/lex-parser.shtml).

Reference: Asma Mekki, Inès Zribi, Mariem Ellouze et Lamia Hadrich Belguith, « Treebank creation and parser generation for Tunisian Social Media text », The 17th ACS/IEEE International Conference on Computer Systems and Applications (AICCSA 2020), Antalya, Turkey, 2020.

DOI: 10.1109/AICCSA50499.2020.9316462
