## Table 1: First Test Run

| Code | Code Snippet                       | Task Description | Proposed Facets                 | Detected Problems                     | Improvements      |
|------|------------------------------------|----------------- |---------------------------------|---------------------------------------|-------------------|
|Fr1x1 |<img src="res/Fr1.png" width= "300">|Loop & Index Understanding|Analytical, Abstraction |Only reliably tests analytical thinking|Focus solely on the cognitive facet of analytical thinking|
|Fr1x2 |See code snippet Fr1x1|Edge Case Handling|Abstraction|Requires language-specific knowledge; primarily tests analytical thinking|Delete task|
|Fr1x3 |See code snippet Fr1x1|Flowchart Comparison|Analytical, Abstraction|Did not require either abstract thinking/analytical thinking; made rule-based thinking easy |Provide several flowcharts that can reflect different aspects|
|Fr2x1 |<img src="res/Fr2.png" width= "300">|Detect Output|Analytical, Abstraction|Only reliably tests analytical thinking|Focus solely on the  cognitive facet of analytical thinking|
|Fr2x2 |See code snippet Fr2x1|Assigning Inputs to Outputs|Analytical, Abstraction|Presentation format and task are not very intuitive and are too complex|Delete task|
|Fr2x3 |See code snippet Fr2x1|Detecting Correct Statements on Behavior|Analytical, Abstraction|Ambiguous evaluation scheme (binary, even though multiple answers may be correct); the focus is mainly on the ability to think abstractly|Focus solely on the cognitive aspect of abstract thinking; Rating system expanded
|Fr3x1 |<img src="res/Fr3.png" width= "300">|Method Naming|Analytical, Abstraction|Code too complex; None of the intended aspects are reliably tested due to poor results, though there is a tendency towards abstract thinking|Simplify the code; focus on abstraction|
|Fr3x2 |See code snippet Fr3x1|Error Detection|Analytical, Abstraction, Critical|only reliably assesses analytical and critical thinking|Focus on only one cognitive facet
|Fr4x1 |<img src="res/Fr4.png" width= "300">|Code Snippet Comparison|Analytical, Abstraction, Critical|Ambiguous marking scheme (binary, even though multiple answers may be correct); the distinctiveness of the facets is not guaranteed due to additional cognitive demands|Rating system expanded; Focus on critical thinking|
|Fr5x1 |<img src="res/Fr5.png" width= "300">|Functionality Check|Analytical, Abstraction, Critical|Code functionality already tested in Fr4x1|Delete task|
|Fr5x2 |See code snippet Fr5x1|Code Evaluation|Critical|Participants have already linked Fr5x2 and Fr5x3 in their answers|Combine Fr5x2 and Fr5x3 into one task|
|Fr5x3 |See code snippet Fr5x1|Code Improvement|Critical|-|Adapt phrasing of the task so that it includes Fr5x2|

## Table 2: Second Test Run

| Code | Task Description | Code Snippet | Tested Facet | Explanation |
|------|------------------|--------------|--------------|-------------|
|Q1x1 (former Fr1x1)|Loop & Index Understanding|<img src="res/Q1.png" width= "300">|Analytical|Tests analytical thinking by requiring students to trace the code step by step, analyze loops and conditions, and distinguish subtle differences in the answer choices.|
|Q1x2 (former Fr1x3)|Flowchart Comparison|See code snippet Q1x1|Depends on Flowcharts and their errors|-|
|Q2x1 (former Fr2x1)|Detect Output|<img src="res/Q2.png" width= "300">|Analytical|Tests analytical thinking by requiring students to mentally trace the program flow, follow loop and condition behavior step by step, and recognize how the output string is constructed.|
|Q2x2 (former Fr2x3)|Detecting Correct Statements|See code snippet Q2x1|Abstraction|Participants must move beyond tracing single outputs and instead understand the general behavior and structure of the program. They need to integrate loops, conditions, and index handling into an overall understanding of how the function operates for different inputs.|
|Q3x1 (former Fr3x2)|Error Detection|<img src="res/Q3.png" width= "300">|Critical|Participants must not only trace how the code works, but also evaluate whether it behaves correctly for different inputs. They need to compare multiple test cases, identify edge cases that reveal logical flaws, and judge whether the algorithm achieves its intended purpose or fails under certain conditions.|
|Q4x1 (former Fr3x1)|Method Naming|<img src="res/Q4.png" width= "300">|Abstraction|Participants must identify the overall purpose of the code and translate its behavior into a meaningful conceptual description. Instead of focusing only on individual lines, they must integrate the conditions and data processing into an understanding of the algorithm’s function and express it through an appropriate method name.|
|Q4x2 (former FR4x1)|Code Snippet Comparison|<img src="res/Q4x2.png" width= "300">|Critical|Participants must evaluate each code snippet against a formal specification and judge whether it correctly implements the required behavior. They need to detect correctness (does it preserve non-negative values and replace only negatives), and distinguish subtle logical differences between similar implementations rather than just understanding the code flow.|
|Q5x1 (former Fr5x3)|Code Improvement|<img src="res/Q5.png" width= "300">|Critical|Participants must evaluate the code beyond its output, focusing on correctness, efficiency, and readability. They need to identify logical errors (incorrect max calculation), unnecessary computations, and poor design choices, and then justify improvements such as simplifying the structure and removing redundant operations.|
