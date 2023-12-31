# Parsing-Musical-Structure-to-Enable-Meaningful-Variations

**Authors:** Maziar Kanani, Seán O’Leary, James McDermott

The study presents a novel rule-based approach for generating music by varying existing tunes. We parse each tune to find the Pathway Assembly (PA) [1], that is a structure representing all repetitions in the tune. The Sequitur algorithm [2] is used for this. The result is a grammar. We then carry out mutation on the grammar, rather than on a tune directly. There are potentially 19 types of mutations such as adding, removing, swapping or reversing parts of the grammar that can be applied to the grammars. The system employs one of the mutations randomly in this step to automatically manipulate the grammar. Following the mutation, we need to expand the grammar which returns a new tune. The output after 1 or more mutations will be a new tune related to the original tune. Our study examines how tunes change gradually over the course of multiple mutations. Edit distances, structural complexity and length of the tunes are used to show how a tune is changed after multiple mutations. In addition, the size of effect of each mutation type is analyzed. As a final point, we review the musical aspect of the output tunes. It should be noted that the study only focused on generating new pitch sequences. The study is based on an Irish traditional tune dataset and a list of integers has been used to represent each tune’s pitch values.

## Repository Contents

In this repository you can find three more examples. These three examples have three PAI ranges: low, middle and high. To explore how they changed after 35 mutations and 100 mutations, we present the results. A very short PAI occurs when the tune becomes very short, not in lengthy or regular-size tunes. In our outputs, a middle size tune with a middle size PAI was very common. Large PAI happens just in long length tunes. However, it does not mean that long tunes always have a large PAI. You can lis ten to the midi files in 35 and 100 mutations for these three examples. In addition, you can also see their piano rolls, CSV files and graphs.


---------------------------------------------------------------------------------------------------------------------------------
[1] S.M.Marshall,D.Moore,A.R.Murray,S.I.Walker,andL.Cronin,“Quantifyingthepathways to life using assembly spaces,” arXiv preprint arXiv:1907.04649, 2019.

[2] C. G. Nevill-Manning and I. H. Witten, “Identifying hierarchical structure in sequences: A linear-time algorithm,” Journal of Artificial Intelligence Research, vol. 7, pp. 67–82, 1997.
