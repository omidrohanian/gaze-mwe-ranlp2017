### Dataset Information 

The dataset contains annotations of the GECO corpus with Verb + Noun and Verb + Particle constructions

Two annotators with linguistic background labelled the GECO corpus for Verb + Noun and Verb + Particle constructions. 
Both annotators read the entire corpus and marked both types of MWEs by considering cases where the components of an MWE can occur with at most three words in between. 

We followed the markup instructions provided by Schneider et al. (2015) to join the components of a MWE by the special character underscore (_).

All Verb + Noun and Verb + Particle expressions (with or without gaps and irregardless of whether they were annotated as MWE or not) are considered for evaluating the agreement between the annotators. The Kappa  inter-annotator agreement is 0.7864. Furthermore, we have resolved the annotation differences by employing a third annotator to decide in cases of disagreement.

In order to prepare sequences to be trained by the CRF model, we changed all the markup to numbers as follows:

0: for the tokens that do not match the pattern of Verb + Noun or Verb + Particle
1: for the tokens that match the pattern of Verb + Noun or Verb + Particle, but are not tagged as MWEs
2: for the tokens that match the pattern of Verb + Noun or Verb + Particle, and are tagged as the beginning of MWEs
3: for the tokens that match the pattern of Verb + Noun or Verb + Particle, and are tagged as the middle of MWEs 
4: for the tokens that match the pattern of Verb + Noun or Verb + Particle, and are tagged as the end of MWEs
