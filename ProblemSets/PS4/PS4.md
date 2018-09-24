# Problem Set 4

Due: October 2, 11:59 PM.

## Assignment

Answer the following questions related to performing the requested tasks and then
include your answers in an electronic file, save as a single PDF. Upload your PDF file
to the Blackboard Assignment page for Problem Set 4 by 11:59 PM on the due date.

1. Take your primatesAA.fasta from Blackboard and conduct a BLAST search with the Orangutan sequence. Which BLAST algorithm did you use? Why? What scoring matrix did you use? What gap penalty did you use? What is this protein? Show your top 20 results.
  - Now, choose a different scoring matrix. Choose a different gap cost. Take a screen shot of your new model and compare to that in the previous BLAST run. What are your results (show your top 20 again)? Does this adjustment make a difference, why or why not?

2. Redo the analysis and questions in (1), but now for the Orangutan sequence in the primatesNuc.fasta. Which BLAST algorithm did you use?  Why? What match/mismatch scores did you use?  What gap costs did you use?  
  - Now, choose a different match/mismatch score.  Choose a different gap cost.  Take a screen shot of your new model and compare to that in the previous BLAST run.  What are your results (show your top 20 again)?  Does this adjustment make a difference, why or why not?

3. Go to the following website: [http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Needleman-Wunsch](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Needleman-Wunsch) and align this pair of sequences using Needleman-Wunsch:

```
ATCAAGA
ACACA
``` 

- Describe the dynamic programming algorithmic approach.
- How many alternative alignments did you get? (show your results)
- What scores did you use for Match, Mismatch, and Gap?
- Change your scores and redo your analysis.  Show your output and alternative alignments.  How did changing your parameters change your alignment?
