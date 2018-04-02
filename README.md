# Bachelor of Science thesis in Computer Science

> Thesis work: [Persistent Phylogeny](https://github.com/dcasella/persistent-phylogeny)

## Abstract

Recently, studying character-based phylogeny models that allow the loss of characters gained relevancy.
E.g., in tumor phylogeny, the deletion of entire genomic regions often cause loss of (previously acquired) mutations.  
The Persistent Phylogeny model solves this by generalizing the concept of Perfect Phylogeny, allowing for each character to be acquired and lost at most once during the evolutionary events.  
We formalize and contextualize this problem, describing a recently introduced algorithm for reconstructing a Persistent Phylogeny tree starting from a binary matrix, the first solving this problem in polynomial time.  
We then proceed to implement it using the C++ language and Boost libraries, complementing the study with tests on instances that do or don't admit a Persistent Phylogeny, and performance evalutation.
