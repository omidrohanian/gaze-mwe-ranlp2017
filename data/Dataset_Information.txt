== Introduction ==

The dataset contains annotations of the GECO corpus with Verb + Noun and Verb + Particle constructions

Two annotators with linguistic background labelled the GECO corpus for Verb + Noun and Verb + Particle constructions. The procedure was as
follows. 

Both annotators read the entire corpus and marked both types of MWEs by considering cases where the components of an MWE can occur with at most three words in between. 

We followed the markup instructions provided by Schneider et al. (2015) to join the componnets of a MWE by the special character underscore (_).

All Verb + Noun and Verb + Particle expressions (withor without gaps) irregardless of whether they were annotated as MWE or not are considered for evaluating the agreement between the annotators. The Kappa  inter-annotator  agreement  is  k=0.7864. Furthermore, we have resolved the annotation differences by employing a third annotator to decide in cases of disagreement.

In order to prepare sequences to be trained by the  CRF  model,  we  

extract  from  the  corpus  all patterns of Verb + Noun and Verb + Prepositions(and  Verb  +  a  list  of  other  particles  such  asup,down,  over,  etc)  with  at  most  three  words  be-tween the components.   MWEs are tagged
