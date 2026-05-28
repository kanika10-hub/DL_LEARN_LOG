LLM_FOUNDATION(1)
~ understanding tokens and embeddings 
~ Building BPE (Byte Pair Encoding)-
~ Why BPE exists:

Character-level tokenization:
1) tiny vocab
2) long sequences

Word-level tokenization:
1) huge vocab
2) unknown words problem

BPE balances both:
1) common words become single tokens
2) rare words split into chunks
