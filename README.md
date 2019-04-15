# Event-Detection-on-Microposts
This is the repository for data related to our submission to TKDE titled "Event Detection on Microposts: a Comparison of Four Approaches".

# Section 4.4: Semantic Approach: Armatweet

Link to the data: https://drive.google.com/file/d/1HzyBJUowgTt7hJ6A-bcx1v3OrppJCCbi/view?usp=sharing. This folder contains the following information:

- The "events" directory contains the Excel files used to categorise
  the detected tweets into classes reported in the paper.

- The "dlog" directory contains the Datalog program for the RDFox
  system that was used to analyse the tweets. The semantic queries
  are encoded as rules in the program.

- The "facts" directory contains the RDF triples in the Turtle format
  that were extracted from raw Twitter data, the version of DBpedia
  (called BMpedia.ttl) used, and the version of WordNet.

- The "scripts" directory contains the RDFox scripts used to analyse
  the data.
