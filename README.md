# TEXT2MIDI-INFERALIGN: IMPROVING SYMBOLIC MUSIC GENERATION WITH INFERENCE-TIME ALIGNMENT

We present Text2midi-InferAlign, a novel tech-
nique for improving symbolic music generation at infer-
ence time. Our method leverages text-to-audio alignment
and music-structural alignment rewards during inference
to encourage the generated music to be consistent with the
input caption. Specifically, we introduce two objectives: a
text-audio consistency score that measures rhythmic align-
ment between the generated music and the original text
caption, and a harmonic-consistency score that penalizes
generated music containing notes inconsistent with the key.
By optimizing these alignment-based objectives during the
generation process, our model produces symbolic music
that is more closely tied to the input captions, thereby im-
proving the overall quality and coherence of the generated
compositions. Our approach can extend any existing au-
toregressive model without requiring further training or
fine-tuning. We evaluate our work on top of Text2midi -
an existing text-to-midi generation model, demonstrating
significant improvements in both objective and subjective
evaluation metrics.


