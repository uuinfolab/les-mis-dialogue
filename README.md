# Les Misérables Dialogue

This repository contains the **Les Misérables Dialogue (LMD)** dataset, a network representation of social communication in the 1998 film adaptation of *Les Misérables*.

The dataset contains **1,686 utterances** annotated with speaker, addressee(s), recipient(s), dialogue text, temporal information, and scores for ten social dimensions.

The network representation follows the **Temporal Text Network (TTN)** model introduced by Vega and Magnani [1]. The released networks can be analysed using the **multinet** library [2]. Social-dimension scores are computed using the ten-dimensional framework and classifier introduced by Deri et al. and Choi et al. [3,4].

## Network representations

The repository provides:

* **LMD$_a$** — TTN using speakers and intended addressees.
* **LMD$_r$** — TTN using speakers and all recipients.
* **LMD-flat$_a$** — flattened speaker--addressee network.
* **LMD-flat$_r$** — flattened speaker--recipient network.
* **LMD-ML$_a^{0.5}$** and **LMD-ML$_r^{0.5}$** — ten-layer multiplex networks with threshold 0.5.
* **LMD-ML$_a^{0.8}$** and **LMD-ML$_r^{0.8}$** — ten-layer multiplex networks with threshold 0.8.

The ten multiplex layers correspond to **Knowledge, Power, Status, Trust, Support, Romance, Similarity, Identity, Fun, and Conflict**.

## Annotated utterances

The complete utterance-level annotations are not distributed directly in this repository, but can be requested for research purposes.

For access or questions about the dataset, feel free to contact us: [Theodora Moldovan](mailto:theodora.moldovan@it.uu.se), [Georgios Panayiotou](mailto:georgios.panayiotou@it.uu.se), [Davide Vega](mailto:davide.vega@it.uu.se)

## Paper

The full methodology, validation procedure, and analysis are described in the accompanying paper:

> Theodora Moldovan, Georgios Panayiotou, and Davide Vega.
> *Les Misérables Dialogue: A film-based network representation of social communication.*

## References

1. Vega, D., and Magnani, M. *Foundations of Temporal Text Networks.*
2. Magnani, M. et al. *multinet: Analysis and Mining of Multilayer Social Networks.*
3. Deri, S. et al. *Coloring in the Links: Capturing Social Ties as They Are Perceived.*
4. Choi, M. et al. Ten-dimensional social relationship classification from conversational text.

## Citation

If you use this dataset, please cite the accompanying paper.

A complete BibTeX citation will be added upon publication.
