# Logic-Resolution
First Order Logic Resolution Engine

I developed an agent using the resolution algorithm that, given a Knowledge Base and a query, determines whether the Knowledge base entails the query.
* Involved lexical parsing of logical statement and converting each statement into CNF form. This was done with just the native libraries.
* Apply unification algorithm to among clauses of the Knowledge base to resolve the clauses to determine entailment
