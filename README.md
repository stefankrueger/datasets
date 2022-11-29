# datasets

* ## Fine-grained Named Entity Recognition in Legal Documents
    * Description: German court decisions from 2017 and 2018 were selected for the dataset, published online by the Federal Ministry of Justice and Consumer Protection. The documents originate from seven federal courts: Federal Labour Court (BAG), Federal Fiscal Court (BFH), Federal Court of Justice (BGH), Federal Patent Court (BPatG), Federal Social Court (BSG), Federal Constitutional Court (BVerfG) and Federal Administrative Court (BVerwG).
    * Project: https://github.com/elenanereiss/Legal-Entity-Recognition
    * Annotation Guidelines: https://raw.githubusercontent.com/elenanereiss/Legal-Entity-Recognition/master/docs/Annotationsrichtlinien.pdf
    * existing Bachelor thesis: https://raw.githubusercontent.com/elenanereiss/Legal-Entity-Recognition/master/docs/Leitner_LER_BA.pdf
    * data: https://huggingface.co/datasets/elenanereiss/german-ler
    * pros: human annotated
    * cons: named entities are anonymized eg. "Herr M. wurde am ..." anstelle von "Herr Mustermann wurde am ..."
    * ![size](pic/Size.png)
    * ![distribution](pic/Distribution.png)

* ## Annotated Corpus from Named Entity Recognition
    * Description: Annotated Corpus for Named Entity Recognition using GMB(Groningen Meaning Bank) corpus for entity classification with enhanced and popular features by Natural Language Processing applied to the data set.
    * Source: https://www.kaggle.com/datasets/abhinavwalia95/entity-annotated-corpus
    * original data from GMB: https://gmb.let.rug.nl/data.php
    * entities:
        * geo = Geographical Entity
        * org = Organization
        * per = Person
        * gpe = Geopolitical Entity
        * tim = Time indicator
        * art = Artifact
        * eve = Event
        * nat = Natural Phenomenon
    * Total Words Count = 1354149
    * ![data](pic/kaggleGMB.png)

* ## Tipp von V. (ehemals GMB Mitwirkender)
    * einige Datensätze enden in 404 (lange her), einige hinter Paywall, andere nicht immer rechtlich klar
    * Sammlung NER: https://github.com/juand-r/entity-recognition-datasets
        * vllt hiervon: https://www.clips.uantwerpen.be/conll2003/ner/

* # NER und RE  (Relation)
    * ## SpERT: Span-based Entity and Relation Transformer 
        * original paper: https://arxiv.org/abs/1909.07755
        * code: https://github.com/lavis-nlp/spert
        * dataset : ade and conll04 (downloaded)

    * ## JointER: Joint Extraction of Entities and Relations Based on a Novel Decomposition Strategy
        * original paper: https://arxiv.org/abs/1909.04273
        * code: https://github.com/yubowen-ph/JointER
        * dataset: NYT-multi (downloaded)

    * ## JEREX: "Joint Entity-Level Relation Extractor"
        * original paper: https://arxiv.org/abs/2102.05980
        * code: https://github.com/lavis-nlp/jerex
        * dataset: docred and docred_joint (downloaded)
