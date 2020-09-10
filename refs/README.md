Seq 2 Seq Models
================

# Learning to generate one-sentence biographies from Wikidata.
Chisolm. A., Radford. W., Hackey. B., (2017)
[arXiv](https://arxiv.org/pdf/1702.06235.pdf)

## Summary
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


# Sequence to Sequence Learning with Neural Networks
Ilya Sutskever, Oriol Vinyals, Quoc V. Le. (2014). Neural Information Processing Systems.
[NIPS Paper](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf)
[arXiv](https://arxiv.org/abs/1409.3215)
[Google Research](https://ai.google/research/pubs/pub43155)

@inproceedings{43155,
title	= {Sequence to Sequence Learning with Neural Networks},
author	= {Ilya Sutskever and Oriol Vinyals and Quoc V. Le},
year	= {2014},
URL	= {http://arxiv.org/abs/1409.3215},
booktitle	= {Proc. NIPS},
address	= {Montreal, CA}
}

## Summary

 
# Massive Exploration of Neural Machine Translation Architectures
Britz, Denny and Goldie, Anna and Luong, Thang and Le, Quoc. (2017).

@ARTICLE{Britz:2017,
  author          = {{Britz}, Denny and {Goldie}, Anna and {Luong}, Thang and {Le}, Quoc},
  title           = "{Massive Exploration of Neural Machine Translation Architectures}",
  journal         = {ArXiv e-prints},
  archivePrefix   = "arXiv",
  eprinttype      = {arxiv},
  eprint          = {1703.03906},
  primaryClass    = "cs.CL",
  keywords        = {Computer Science - Computation and Language},
  year            = 2017,
  month           = mar,
}

[Github](https://github.com/google/seq2seq)
[arXiv](https://arxiv.org/abs/1703.03906)


