# SemanticDatasets


Scripts for generating datasets aimed at enhancing nuanced natural
language understanding, focusing on meaning-matching tasks, logical
reasoning, natural language inference, sentiment analysis, and key
message alignment

------------------------------------------------------------------------

This project focuses on creating resources for fine-tuning language
models on tasks such as synonym and antonym identification, basic
logical reasoning, natural language inference, interpretative reasoning,
and the alignment of key messages.

## What is Interpretative Inference

Interpretative inference (see e.g. McCarthy and Goldman 2017) involves
drawing conclusions based on qualitative assessments and contextual
understanding, rather than relying solely on formal logic, as
illustrated by the classic example: “Socrates is a human. All humans are
mortal” → “Socrates is mortal.” This form of reasoning enables nuanced
interpretations that reflect opinions, implications, and broader
meanings behind statements. For instance, the observation “The
restaurant was empty on a Saturday night” might lead to the
interpretative conclusion that “The restaurant may not be popular.”
Similarly, the phrase “The new smartphone has impressive features” could
be interpreted as “The new smartphone is likely to attract attention,”
highlighting its market appeal. Additionally, a sentiment such as “I
enjoy hiking in the mountains” can be interpreted as “Mountains are
enjoyable,” reflecting a positive view of mountainous landscapes. By
focusing on interpretative inference, our project aims to create
datasets that enhance language models’ ability to understand and discern
nuanced evaluations and implications in natural language.

## TODO

1.  Associations dictionary
    ([kartaslov](https://github.com/dkulagin/kartaslov)) for Russian and
    [Meaning-Matching](https://github.com/MJ-Jang/beyond-distributional)
    (IM<sup>2</sup>) data (Jang, Mtumbuka, and Lukasiewicz 2022) for
    English.
2.  Simple logic tests (Войнаровский 2005).
3.  Natural language inference datasets (TERRa).
4.  Interpretative Inference:
    1)  sentiment and evaluation
    2)  semantic differential
    3)  key message alignment

## Potential Gaps

1.  What specific methods will be used to create datasets that enhance
    language models’ interpretative reasoning?

2.  How will the effectiveness of these datasets be measured in
    improving understanding of nuanced evaluations?

3.  Are there any limitations or challenges associated with
    interpretative inference in natural language processing?

## References

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0">

<div id="ref-jang-etal-2022-beyond" class="csl-entry">

Jang, Myeongjun, Frank Mtumbuka, and Thomas Lukasiewicz. 2022. “Beyond
Distributional Hypothesis: Let Language Models Learn Meaning-Text
Correspondence.” In *Findings of the Association for Computational
Linguistics: NAACL 2022*, edited by Marine Carpuat, Marie-Catherine de
Marneffe, and Ivan Vladimir Meza Ruiz, 2030–42. Seattle, United States:
Association for Computational Linguistics.
<https://doi.org/10.18653/v1/2022.findings-naacl.156>.

</div>

<div id="ref-McCarthy-Goldman-2017" class="csl-entry">

McCarthy, Kathryn, and Susan Goldman. 2017. “Constructing Interpretive
Inferences about Literary Text: The Role of Domain-Specific Knowledge.”
*Learning and Instruction* 60 (December).
<https://doi.org/10.1016/j.learninstruc.2017.12.004>.

</div>

<div id="ref-Voinarovsky2005" class="csl-entry">

Войнаровский, М. Ю. 2005. “Тест На Логическое Мышление.” In
*Психологика*. <https://voinarovsky.ru/test/test.htm>.

</div>

</div>
