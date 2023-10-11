# C2S2-TestTask
This is a test task for the PreCog Lab, IIITH. It has code submission in ipynb file and summary of paper in PaperSummary.pdf file.

Answer to questions from the mail:
> Q. What are the three major strengths of the paper?<br>
A. The paper has major strength as follows:
1. The paper introduces a novel metric, SyMCoM, to quantify syntactic variations in code-mixed text, offering a valuable tool for analyzing code mixing from a syntactic perspective.
2. The study provides quantitative evidence supporting the hypothesized syntactic behavior in code mixing, enhancing our understanding of how specific PoS categories are influenced during language switching.
3. The successful application of SyMCoM in English-Hindi code mixing demonstrates its practical utility and sets the stage for further research in multilingual scenarios and deeper syntactic structures.

> Q. What are the three major weaknesses of the paper? <br>
A. The paper has follwing weaknesses:
1. The study predominantly focuses on English-Hindi code mixing, potentially limiting the generalizability of findings to other language pairs or multilingual contexts. It also limits itself to English-vernacular pairings rather than trying out other vernacular-vernacular pairings which has more interconnectivity between them.
2. The paper assumes the availability of reasonably accurate PoS taggers for the code-mixed language pair, which might not always be readily accessible or may vary in accuracy. Its a huge bottle-neck.
3. While the results affirm the hypothesis, a comparative analysis with existing methods or metrics could provide a more comprehensive evaluation of SyMCoM's effectiveness.

> Q. Suggest three improvements to the paper that would improve the paper? <br>
A. Following improvements can be implemented:<br>
1. To enhance applicability, future research could extend the study to diverse language pairs, considering the unique syntactic characteristics of different languages during code mixing. 
2. Since, Spoken languages usually like 'vernacular' hindi are already code-mixed. They themselves are mixture of different languages.Using a language triplet or more with SyMCoM would involve extending the existing approach to accommodate code mixing involving three languages instead of just two.
3. Assess the robustness of SyMCoM by testing its performance with varying degrees of noise or inaccuracies in language identification and PoS tagging tools.
