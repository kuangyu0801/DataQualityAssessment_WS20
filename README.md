#帳號detail easychair:
- lumiereli
- cougar9487

[https://easychair.org/my/conference?conf=sqaseminarws2021#](https://easychair.org/my/conference?conf=sqaseminarws2021#)

# Reference
- Coursera: [https://www.coursera.org/learn/sql-data-science/home/welcome][2] Databases and SQL for Data Science
![avatar][/picture/relational_database.png]
# 知識點

- what are relational databases: [https://en.wikipedia.org/wiki/Relational_database][1]

# TODO
- 檢查一下資料（what are the structure, attribute, dimension)跟問題是屬於哪一種(dependent, user centric)？

# Feedback
- From what currently is mentioned in the abstract, the motivation and the
context for the paper could be stressed more that a reader can judge
from the abstract what the paper is about and why you worked on that topic.


# Introduction

可以談到data quality的重要性, 與目前遇到的挑戰

**The rest of the paper is structured as follows: First,** 



In this section, the overview of this report will be presented. 
Then the following two points will be discussed
1. the motivation behind this report
2. a brief introduction of data quality assessment including its importance and challenges 




# fundamentals on Data Attributes
In this section, fundamentals and concept of data quality will first be reviewed and discussed. 
The topics included are definition, classification, attributed, dimensions of data.
Secondly, the process and pipelines for analysing methodologies of DQ are introduced.
This topics regarding these methodologies includes strategies, techniques, dimensions, 
costs, data types, information system types


# Related Work
In this section, 5 state-of-the art data quality assessment methods are introduced in brief.
These methods includes : to decided.
# Evaluation
In this section evaluation in terns of process, techniques, and performances are discussed across these 5 methods.
# Conclusion

This section summarizes all the topics in report. 
The conclusions of evaluation of different method is drew. 
From the best suitable methods, new ideas and customization are proposed to be adapted in the context of CI/CD application in software engineering.
In the end, the future work of data quality assessment for CI/CD application are proposed.

# Literature Review
## Data Quality Assessment
- Functional Forms
	- Simple Ratio.
	- Min or Max Operation.
	- Weighted Average.
- Assessments in Practice

Issues that arise when combining values associ- ated with different scale types (ordinal, interval, and ratio)

- Conclusion

one size fits all” set of metrics is not a solution.
fundamental prin- ciples underlying the development of subjective and objective data quality metrics

## The Challenges of Data Quality and Data Quality Assessment in the Big Data Era

- 1 Introduction

However, the use and analysis of big data must be based on accurate and high-quality data, which is a necessary condition for generating value from big data. 
- 2 Literature Review on Data Quality

They defined “data quality” as “fitness for use” (Wang & Strong, 1996) and proposed that data quality judgment depends on data consumers.

“data quality dimension” as a set of data quality attrib- utes that represent a single aspect or construct of data quality.


- 3 The Challenges of Data Quality in the Big Data Era
	- 3.1 Features of big data
		- 4Vs: Volume, Velocity, Variety, and Value 
	- 3.2 The challenges of data quality
		- The diversity of data sources brings abundant data types and complex data structures and increases the difficulty of data integration.
		- Data volume is tremendous, and it is difficult to judge data quality within a reasonable
amount of time.
		- Data change very fast and the “timeliness” of data is very short, which necessitates higher requirements for processing technology.
		-  No unified and approved data quality standards have been formed in China and abroad, and research on the data quality of big data has just begun.
-  4 Quality Criteria of Big Data
Figure 2: A universal, two-layer big data quality standard for assessment.
***這張圖好用***

- 5 QUALITY ASSESSMENT PROCESS FOR BIG DATA
- 
Figure 3: Quality assessment process for big data.
***這張圖好用***

- 6 Conlcusion

dynamic big data quality assessment process with a feedback mechanism

## Methodologies for Data Quality Assessment and Improvement

1. INTRODUCTION TO DATA QUALITY
2. COMPARATIVE PERSPECTIVES FOR ANALYZING METHODOLOGIES
- 2.1. Common Phases and Steps
- 2.2. Strategies and Techniques
- 2.3. Dimensions
- 2.4. Costs
- 2.5. Types of Data
- 2.6. Types of Information Systems

3. COMPARISON OF METHODOLOGIES

3.1. Methodologies, Phases, and Steps
3.2. Methodologies, Strategies, and Techniques
3.3. Methodologies and Dimensions
3.4. Methodologies and Costs
3.5. Methodologies and Types of Data
3.6. Methodologies and Types of Information Systems
3.7. Summary Comparison of Methodologies

4. CONCLUSIONS AND OPEN ISSUES
4.1. From Data Quality to Information Quality
4.2. Data Quality and Process Quality
4.3. Data Quality and New Types of Information Systems
4.4. Further Open Issues


## A CLASSIFICATION OF DATA QUALITY ASSESSMENT METHODS 2011(這一篇作為主力！！！！)

同音詞 (Homonym), 同義詞 (Synonym)


### INTRODUCTION
Data quality (DQ) assessment provides the basic foundation for improving DQ in organizations

The rest of the paper is structured as follows: First, we introduce a classification of DQ problems and a list of DQ methods currently used in DQ tools. Furthermore, we provide a brief review of previous work on DQ method classifications. The centre of this paper is our proposed classification, which maps DQ assessment methods with DQ problems into a taxonomy and provides detailed examples for each mapping. The section is divided into mapping of independent DQ problems and mapping of context- dependent DQ problems. The paper ends with a conclusion and outlook for future research.


### DATA QUALITY PROBLEMS
Table 1. A Classification of DQ Problems [9]
***這張圖好用***

### DQ ASSESSMENT METHODS

- Column analysis: Number of (unique) values and the number of instances per value as percentage from the total number of instances in that column
- Cross-domain analysis
- Data validation
- Domain analysis
- Lexical analysis
- Matching algorithms: identify duplicates
- Primary key and foreign key analysis (PK/FK analysis) : are good candidates for a PK/FK
- Schema matching: two attributes are semantically equivalent
- Semantic profiling

### EXISTING CLASSIFICATIONS OF DATA QUALITY METHODS
Gartner research takes a different approach and provides a “Magic Quadrant” to guide organizations in their selection of DQ tools. 

Table 2. Classification Mapping Requirements

### CLASSIFYING DQ ASSESSMENT METHODS

#### Classification of Assessment Methods and Context-Independent DQ Problems

##### Discussion of the Context-independent Classification of DQ Methods

#### Classification of Assessment Methods and Context-Dependent DQ Problems

##### Discussion of the Context-dependent Classification of DQ Methods

### CONCLUSION AND FUTURE WORK

Several gaps were identified overall for two DQ problems: missing data and existence of synonyms and homonyms. 
- The first gap relates to the missing data DQ problem, where for example a table is missing a row.
- The other gaps relate to the detection of synonyms and homonyms throughout multiple rows, multiple attributes, multiple relations and multiple data sources. 

One limitation of the classification is that it only considers whether a DQ method addresses a DQ problem (for each taxonomy element), and this may not always be absolute in the sense that some DQ methods may be more comprehensive than others
it may be the case that only the developers of the classification were not able to identify a DQ problem. 
Furthermore, as semi-structured data like XML files and unstructured data



### 可以列為參考

- Ge, M., and Helfert, M., “A Review of Information Quality Research,” Proceedings of the 12th International
Conference on Information Quality, 2007.

[1]: https://en.wikipedia.org/wiki/Relational_database

[2]: https://www.coursera.org/learn/sql-data-science/home/welcome