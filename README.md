# C-LDA
A generative model for topic segmentation in documents based on Latent Dirichlet Allocation. The main difference from conventional models is that the topic of each word is generated by both topic distribution and a set of word pairs in its context.

# Usage:
The file tdt2_em_v4_0_100.npy keeps first 100 documents of TDT2 dataset.

The main program is in the "C_LDA.py" file.

After the training, the topic distribution, word distribution and word pair co-occurrence topic distribution will be returned and saved under the current folder.

The test program is in the file "python test. py".

Run "python test.py" and test the perplexities for C-LDA and traditional LDA.
