Seq 2 Seq Models
================

Chisolm. A., Radford. W., Hackey. B., (2017(
Learning to generate one-sentence biographies from Wikidata.
[ArchivX](https://arxiv.org/pdf/1702.06235.pdf)

Chisolm, Radford and Hackey outline a neural network architecture for
taking a string representation of structured facts from Wikidata and 
learning to generate natural language biographies using the first sentences
from Wikipedia articles as the targets. There training, validation and test
data was extracted from Wikidata and Wikipedia as of  (2015/07/13) and
(2015/10/02) respectively, and they extract only entires pertaining to people.
Their final model achieve a BLEU score of 41.0 compared to 33.0 for the template
baseline model. In addition they evaluate the model using crowd sourced human
judgments. Their final model is preferred over the real Wikipedia entries 40% of
the time.


https://ai.google/research/pubs/pub43155

https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf

https://github.com/google/seq2seq


