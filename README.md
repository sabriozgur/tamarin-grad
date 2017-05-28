#tamarin-grad

Implementation of different protocols in Tamarin Prover to get used to the tool and finally implementation of a version of TLS in Tamarin Prover.


IMPORTANT NOTES

* Lemma cannot detect the objects generated at the second step  [1] --[2]-> [3] of a rule
while iterating back from an object at Lemma
So we must not put them at step 2, if we are not using them directly at the lemma.

* DO NOT put information to the facts that will not be used. If that fact will be needed at different rules with different ones used,
separate the facts.
