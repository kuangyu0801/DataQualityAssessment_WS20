.........................
| 1. Paper Summary |
.........................

The paper by Kuang-Yu Li examines requirements put towards Data Quality assessment methods and then evaluates five different methods based on their
requirement coverage. The goal is to find out which method is ideal in the realm of CI/CD data assessment.

Following the introduction, the paper gives a necessary overview of the domain of data quality assessment. This includes data types, a definition of data quality problems,
different steps and phases taken in data quality assessment, and strategies and techniques used for data improvement. Additionally, different dimensional aspects of data quality and the
cost factors of data quality programs are introduced.

The third section contains the introduction of the five different data quality methods examined in the paper.

The fourth section contains the evaluation, in which the methods are compared based on their implementations of the data quality elements mentioned in section 2.

The final section is the conclusion, in which the paper is briefly summarized and the conclusion is given that the CDQ method is the best overall.
This also holds in the domain of CI/CD data. Finally, two open issues are presented for future work.

.........................
| 2. Positive Aspects |
.........................

The paper gives a detailed and complete overview of the domain of data quality assessment.
Additionally, the evaluation is complete and well structured.
The use of Tables and Figures for all findings is also greatly applauded.

.........................
| 3. General Issues |
.........................

• The paper is very hard to read due to a large amount of grammar and spelling errors. I have included ten of these in the section "Other Issues".
• There are many sentences that are long and have a structure that makes them hard to read.
One Example: "Problems with violations of integrity constraints arise when data values do not adhere to pre-specified
database integrity constraints; we also therefore include unique value violations,
rather than have these as a separate problem, because unique value violations
are one type of database integrity constraint."

.........................
| 4. Specific Issues |
.........................

Abstract :
- Hard to understand, no problem area or problem statement. No solution approach. Very short

Introduction:
- Includes Problem and Problem area, however no solution approach. No methodology of approach. No methodology of the evaluation.
I should already know how you are going to perform the evaluation here, even if the methods are explained later in detail in section 2.
- Structure outline is not nice to read. You say the first section is the fundamentals, however, the first section is the introduction. So you are using the wrong numbers.

Section 2 Opening
- Your explanation of the contents of section 2 is very brief and the reader doesn't know what the subsections will be.
The way you write it makes it seem like there are 2, however, section 2 consists of 6 subsections.

Section 2.3
- It seems strange that you don't give a quick explanation for steps 7,8,9 and 10 of the improvement steps

Section 2.5
- Figure 2 is never used

Section 3
- These subsections seem a bit too verbose. It's also hard to quickly compare and understand the differences between the methods.
You mentioned specific attributes of DQ in section 2. Why arent the DQ methods introduced by showing how they implement the attributes of DQ presented in section 2.

Section 4.3 is too verbose
- Here you are explaining in a lot of detail how certain DQ methods implement the attributes of DQ presented in section 2. This makes the evaluation very long.
You also repeat explanations already made in section 2. This just increases the length too much and hinders readability.
- Consider stating specifically that IQM and DQA are not listed here because they lack improvement steps.

Section 4.5
- If I understood correctly, the "evaluation" part here is the intro, where you say that only two methods consider the cost dimension.
You then spend an entire page explaining how the methods implement the cost dimension. This seems very verbose.

Section 4.6
- You mention Economic methodologies, yet they cannot be found in Figure 11 and also are not explained like the others.

Conclusion
The sudden explanation of CI/CD seems out of place.
Your evaluation of which method is best for CI, and the criteria for choosing, are exclusively in the conclusion. This seems out of place.
You mention ICT without ever explaining this acronym before in the paper.
The explanation of "The characteristics of big data" in the conclusion seems to come out of nowhere

Too much Detail
You give a good overview of the methods to assess data quality, however, the explanations of the methods take up the majority of your work,
not your evaluation of the methods practices.

Application of Assessment methods
This is just based on the goals mentioned in your topic's initial description.
If you have adjusted your goals, disregard this.
Otherwise, I was wondering where your application of the assessment methods to existing data is.



.........................
| 5. Other Issues |
.........................

Spelling mistakes:

• Abstract:
- "fives" -> five
- "[...] techniques, targeted data quality dimensions and cost."
-> "[...] techniques, targeted data quality dimensions, and cost."
• Introduction:
- "With the Machine Learning" -> "With Machine Learning"
- "[...] Deeps Learning and Artificial Intelligence" -> "[...] Deeps Learning, and Artificial Intelligence"
- "[...] demand of data analysis" -> "[...] demand for data analysis"
- "Or, more preciosity, how to defines the quality of a set of data?"
-> I don't know what your goal was with this sentence, I am guessing: "Or, more preciously, how to define the quality of a set of data?
I advise not to start sentences with "Or".
• Section 3
- "fives" -> five

• 4 Evaluation
- "evaluation in terns of process" -> "evaluation in terms of process"

• Table 1:
- "organizationas" -> "organisations"

• Conclusion:
- "followed by the evaluation and analysis over five DQ assessment methods in term of different aspects"
-> "followed by the evaluation and analysis of five DQ assessment methods in term of different aspects"

Broken Citation in Section 1:
"Non-Functional Aspects in Software Engineering. Main references are base on following paper and journal: Cai and Zhu [5],
Pipino and Wang [11] and Batini et al. [3] Wang and Strong [13] ? ] Cinzia Cappiello [6]"