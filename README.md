A script processing script takes a set of word embeddings and performs principal component removal to improve the quality of word embeddings based on the work in [this paper](https://arxiv.org/pdf/1702.01417.pdf). It has been configured to work on several types of word embeddings, including [LexVec](https://github.com/alexandres/lexvec), and [Word2Vec](http://vectors.nlpl.eu/repository/).

## postprocess.py

Post process has one flag, -file, that is the path to the file that contains the word embeddings to be processed. It will write the new embeddings to postprocessed_embeddings.txt in the postprocessing directory. 

To run: $python [postprocess.py](http://postprocess.py) <file_path>
