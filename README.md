# Meeting Transcript Summarizer

This summarizer splits the transcript into sentences, turns each sentence into a tf-idf vector that is then used to compute the cosine similarity between each sentence pair. Then each sentence is scored by how connected it is to the rest of the meeting, and finally the top-k sentences are returned in their original order.

We use ROUGE-style evaluation to compare summaries to hand written ones.
