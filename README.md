# Summary

UD_Alemannic-DIVITAL is a manually corrected treebank of Alemannic Alsatian consisting of sentences from several genres.

# Introduction

The corpus consists mostly of Low Alemannic Alsatian sentences. The sentences have been automatically annotated and manually verified.

The `MISC` column includes a gloss in French (`Gloss[fr]`) and a lemma in German (`Lemma[de]`).

Document metadata is included at the beginning of each new document (`#newdoc`): author, source, genre, audience, discourse_type, domain, factuality, form, origin, channel, language_variety.

For details on the pre-annotation and manual correction process see:

* Barbara Hoff, Nathanaël Beiner, and Delphine Bernhard. 2025. [Universal Dependencies for the Alemannic Alsatian Dialects](https://aclanthology.org/2025.tlt-1.2/). In _Proceedings of the 23rd International Workshop on Treebanks and Linguistic Theories (TLT, SyntaxFest 2025)_, pages 10–22, Ljubljana, Slovenia. Association for Computational Linguistics_.
* Delphine Bernhard, Nathanaël Beiner, and Barbara Hoff. 2025. [Pre-annotation Matters: A Comparative Study on POS and Dependency Annotation for an Alsatian Dialect](https://aclanthology.org/2025.law-1.14/). In _Proceedings of the 19th Linguistic Annotation Workshop (LAW-XIX-2025)_, pages 173–186, Vienna, Austria. Association for Computational Linguistics.

The annotation guidelines are detailed in:

* Nathanaël Beiner, Barbara Hoff, Carole Werner, and Delphine Bernhard. 2025. [Syntactic annotation guidelines for Alsatian – DIVITAL project (Version 1)](https://doi.org/10.34847/NKL.5B6CS6WU). NAKALA - https://nakala.fr (Huma-Num - CNRS). https://doi.org/10.34847/NKL.5B6CS6WU


Information on metadata can be found in:

* Marianne Vergez-Couret, Delphine Bernhard, Michael Nauge, Myriam Bras, Pablo Ruiz Fabo, and Carole Werner. 2024. [Managing Fine-grained Metadata for Text Bases in Extremely Low Resource Languages: The Cases of Two Regional Languages of France](https://aclanthology.org/2024.sigul-1.25/). In Proceedings of the 3rd Annual Meeting of the Special Interest Group on Under-resourced Languages @ LREC-COLING 2024, pages 212–221, Torino, Italia. ELRA and ICCL.


# Acknowledgments

The following people were involved in the creation of this dataset:

* Nathanaël Beiner (data annotation, guidelines)
* Barbara Hoff (data annotation, guidelines)
* Delphine Bernhard (advice on annotations, data collection, selection and pre-processing)

The work was supported by the French National Research Agency (project ANR-21-CE27-0004 DIVITAL).

## References

If you use this treebank, please cite this paper:

```
@inproceedings{hoff-etal-2025-universal,
    title = "{U}niversal {D}ependencies for the {A}lemannic {A}lsatian {D}ialects",
    author = {Hoff, Barbara  and
      Beiner, Nathana{\"e}l  and
      Bernhard, Delphine},
    editor = {Jablotschkin, Sarah  and
      K{\"u}bler, Sandra  and
      Zinsmeister, Heike},
    booktitle = "Proceedings of the 23rd International Workshop on Treebanks and Linguistic Theories (TLT, SyntaxFest 2025)",
    month = aug,
    year = "2025",
    address = "Ljubljana, Slovenia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.tlt-1.2/",
    pages = "10--22",
    ISBN = "979-8-89176-291-6",
}
```


# Changelog

* 2025-11-15 v2.17
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.17
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: fiction nonfiction legal spoken wiki bible
Lemmas: not available
UPOS: manual native
XPOS: not available
Features: not available
Relations: manual native
Contributors: Beiner, Nathanaël; Hoff, Barbara; Bernhard, Delphine
Contributing: here
Contact: dbernhard@unistra.fr
===============================================================================
</pre>
