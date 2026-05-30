LEARNT:

RNN-RECURRENT NEUTRAL NETWORK
1)deep learning neural network designed to process sequential data like time series , text by retaining memory 

2)common application- NLP, speech recog , time series forecasting 

CNN → understands spatial patterns in images

RNN → understands sequence and context over time

3)The Big RNN Idea-

At every time step:
RNN-
input current word

combine with previous memory

produce new memory/state

continue

Mathematically:
<img width="418" height="217" alt="image" src="https://github.com/user-attachments/assets/4711508f-8913-4042-9484-5e0d0d8f39c0" />

hidden state- memory
4)WHY ANN FAILS FOR LANGUAGE -

1. Fixed Input Size

ANN needs fixed neurons.

But sentences vary:

“hello”

“how are you today”

long paragraph

RNN handles variable length naturally.

2.No Sequence Understanding

ANN treats features independently.
But language order matters.
Example:
“dog bites man”
“man bites dog”
Same words.
Different meaning.
RNN preserves order.

3. No Shared Understanding Across Positions

If “Sunday” appears at beginning or end:
“On Sunday I ate”
“I ate on Sunday”
ANN learns separately.
RNN reuses same weights at every time step.
That is extremely important.


4.The “Time Travel” Confusion

Very important concept.
When diagrams show:
multiple repeated cells
they are NOT different layers.
It is the SAME network reused repeatedly over time.
Like:

same brain
different moments

This is called unrolling through time.

5.Named Entity Recognition (NER)

Example:
“Rudolph Smith works at Tesla”
Goal:
Rudolph Smith → Person

Tesla → Company

Output labels:

Rudolph -> Person

Smith -> Person

works -> Other

at -> Other

Tesla -> Company

RNN works well because surrounding words help determine meaning.

Example:
“Apple released phone” → company

“I ate apple” → fruit

Context matters.

5)RNN translation usually works in 2 parts:

Encoder-

Reads whole sentence.

Decoder-

Uses that hidden state to generate translated sentence.





