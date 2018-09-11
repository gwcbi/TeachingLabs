# Lab 1: Suspicious Sushi

## Background
You and some friends have just had a dinner at a local sushi bar. Being the inquisitive biologist, you wonder if your group really ate what was listed on the menu (i.e., was the sashimi really what it claimed to be). So you set out to test this hypothesis by saving a bit of tissue from your sashimi. The menu lists the following possibilities: “Hirame” (flounder), “Sake” (salmon), “Hamachi” (yellowtail), and “Maguro” (tuna) sashimi plates. You ordered the Maguro. Given the following sequence from your dinner, design PCR primers to amplify the following exact sequence of DNA (for the sake of simplicity) from your samples. Assume you collected the following sequence using your PCR primers. Compare this sequence to potential candidate species (for example, what is the relative percent identity of your query sequence to the different target sequences?). Tell me your findings. Write up your approach following the guidelines below, **save it as a PDF document**, and submit it to Blackboard by 11:59 pm on the due date.

### Your Sequencing Result
This sequence is also provided to you in a file called `sushi.fasta` for your convenience.
```
GCCTTAAGCCTACTCATCCGAGCTGAGCTTAGCCAACCTGGGGCGCTCTTAGGAGACGACCAGATT
TACAATGTTATTGTTACAGCACATGCCTTTGTAATAATTTTCTTTATAGTAATACCAATTATGATC
GGTGGTTTTGGGAACTGACTTGTTCCCTTAATGATTGGAGCTCCTGATATAGCATTTCCTCGAATA
AATAATATGAGCTTTTGACTCCTCCCCCCTTCATTCCTTCTCCTCCTTTCCTCCTCCGGAGTTGAA
GCAGGGGCCGGAACAGGATGAACAGTTTACCCGCCCCTCGCAGGAAACCTCGCCCACGCAGGGGCC
TCCGTAGACCTAACCATCTTCTCCTTACATCTGGCAGGTGTTTCCTCAATTCTGGGGGCCATTAAC
TTCATTACAACCATTATTAATATGAAGCCTCCAGCCATTTCCCAGTATCAAACCCCCCTCTTCGTA
TGATCCGTTTTAATTACAGCAGTCCTCCTCCTTCTATCCCTCCCCGTCCTTGCAGCCGGCATCACC
ATGCTCCTTACAGACCGAAACCTAAATACAACCTTCTTTGACCCCGCAGGAGGAGGAGACCCCATT
TTATACCAACACCTGTTCTGATTCTTTGGCCACCCC
````

## Guidelines
Begin the paper with an original title, followed by your name, the course name, and the date. All write-ups should be single-spaced and in 12 pt font. Your paper should have all of the following sections.

### Sections
0. **Title:** A concise, but informative quick summary or description of the report.
1. **Introduction:** Introduce the general problem or issue you are addressing. Provide the background context for the reader. You should prepare the reader for the following sections of the report as well as convince the reader that you are tackling a problem worth addressing in your work.
2. **Materials and Methods:** Describe the methods used to obtained the data, analyze the data, and test hypotheses associated with the data. You should explicitly mention and cite any bioinformatic tools used. You may wish to provide the parameters (settings) of any software that you used, if relevant or important.
3. **Results:** Provide and describe the results of the data analysis and hypothesis testing. This may include presenting charts, tables, pictures, and other figures when appropriate for effectively communicating your results. This section is primarily for *only* presenting the results. The following section is for discussing them.
4. **Discussion:**  Interpret your results and discuss their implications with the reader. This section should include a synthesis of ideas.
5. **Conclusion:** Wrap up and summarize the paper. You may also wish to discuss the future direction of similar research here, if relevant. The conclusion does not need to be its own section—you may choose to put a concluding section at the end of discussion. Your paper, however, should include some piece of writing the neatly wraps up your report.
6. **References:** List the relevant literature you have read and used to support your arguments/analyze your data. The literature cited should be in the format of the journal *Bioinformatics*. If you are unfamiliar with this citation style, look up the guidelines for it in the journal's "Instructions to Authors" guide. Failure to cite work used may be considered plagiarism, if the offense is serious.

## Frequently Asked Questions

- How do I need to design primers that work for all possible fish species?
	- No, for this basic exercise, assume that you only need to design primers that would amplify the exact sequence provided above.

- How detailed do I need to be in the Methods section about the DNA extraction and PCR process?
	- Only minimally detailed. You will need to provide the sequences for your primers, however, this is a bioinformatics course, so focus on the bioinformatic details. For the extraction/PCR, you can just say something along the lines of, "We extract DNA from the sample collected from... and conducted a PCR reaction with the following primers..."