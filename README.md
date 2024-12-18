![Image genarted using DALL·E](fig/rds.png)


# DSC 261: Responsible Data Science 



## Description:

This course delves into Responsible Data Science, emphasizing the importance of conscientious practices in data analysis and application. It commences with Causal Inference, enabling students to distinguish between correlation and causation for accurate data interpretation. Subsequent modules cover Algorithmic Fairness to promote unbiased AI development, and Explainable AI, which aims to enhance the transparency and reliability of AI outputs. The curriculum concludes with Data Cleaning, Profiling, and Debiasing, where students learn to refine data quality and mitigate inherent biases. The course is tailored for those seeking to apply data science principles responsibly in practical scenarios.



## Instructional team:

**Instructor:**

[Babak Salimi](https://bsalimi.github.io/), bsalimi@ucsd.edu

**Course Assistants:**


Jiongli Zhu, [jiz143@ucsd.edu](mailto:jiz143@ucsd.edu)   

Parjanya Prashant, [pprashant@ucsd.edu](mailto:pprashant@ucsd.edu)  


**Lectures**:

Tuesdays and Thursdays at	3:30pm-4:50pm




**Office Hours:**
Babak: Mondays 2 pm.

TAs (Jiongli/Parjanya): Wednesdays 9 am.

**Note:** Office hours will be held via Zoom (link can be found on the Canvas calendar). 





### Course Workload

In this course, students will engage in a **project-based and presentation learning experience**, emphasizing teamwork, practical application of data science techniques, and effective communication. Groups of 5-6 students will collaborate to develop projects on topics relevant to the class.  
**Team formation**: Team formation details will be announced by the TA via a Google Doc.

#### Paper Presentation (Mid-Quarter)
- **Each team will present 2-3 related papers in one domain.** 
- The presentation will be **20 minutes**, followed by a **10-minute discussion**. 
- Presentation topics will be selected by the teams, and details will be announced by the TA.

- **Depth of Analysis (40%)** – Understanding, critique, and synthesis of the papers.
- **Clarity & Organization (30%)** – Clear structure, effective visuals, and presentation.
- **Discussion Engagement (20%)** – Thoughtful questions and interaction with the audience.
- **Team Collaboration (10%)** – Equal contribution from all members.

#### Project Requirements:
Each project must:

- **Present a clearly defined hypothesis** and contribute in at least one of the following areas:
   - Propose a novel theory or algorithm.
   - Apply an existing approach to a new domain.
   - Reimplement a paper where no public code is available.

- **Experiments** should be rigorously designed, with well-defined, measurable metrics. All results must include error bars.
   - For theory-focused projects, formal proofs are required.

#### Grading for Projects:
Grading will be based on:

- **Contribution and Effort**
- **Writing**
- **Execution**

**Note on Results:** Projects with thoughtfully designed experiments and solid execution will **not be penalized for yielding negative results**.

#### Checkpoints:
The course will have three project checkpoints:
1. **Initial Proposal**
2. **Midterm Update**
3. **Final Report**

Students are encouraged to meet with the instructor team regularly for guidance. The project will culminate in a short in-class presentation, where students will also create visual posters and dynamic presentations.

#### Grading for Projects: 
Evaluation will consider:
1. **Team Effort**
2. **Quality of Related Work Survey**
3. **Effectiveness of Presentation**
4. **Final Report**
5. **Peer Reviews** (constructive feedback from and to peers)


Titles and abstracts of courses in the last offering can be found here: [Past Projects](past_projects.md)

## Project Timeline

### Week 1: Project Kickoff
- **Activities**: Introduction to course and project guidelines. Begin forming teams.

### Week 2: Team Formation and Topic Selection
- **Activities**: Finalize teams [here](https://docs.google.com/spreadsheets/d/1sO7Y_b_YuelmC2Ys_ggKFK-Jkxeh5RuPyoeJZesLF1M/edit?gid=0#gid=0). Select project topics and submit initial ideas for approval.
- **Signup**: Sign up for the presentation time [here](https://docs.google.com/spreadsheets/d/13eWRHsXzwiKXDK9C1TbWrGLuO-o7ax1oOy4_BFxpuO0/edit?gid=0#gid=0).

### Week 3: Project Proposal Development
- **Activities**: Develop and refine project proposals. Closely work with TAs for brainstorming. Outline objectives, methodologies, and expected outcomes.
- **Template**: Please use this [template](https://www.overleaf.com/latex/templates/sample-acm-ccs/hqrzvbjgvfvz) for proposal and final reports.

### Week 4: Proposal Submission and Feedback
- **Activities**: Submit detailed project proposals. Receive feedback from the TAs and make necessary adjustments.

### Week 5-8: Project Execution Begins
- **Activities**: Start executing the project according to the plan. Focus on data collection and initial analysis.

### Week 9-10: Project Presentation
- **Activities**: Finalize project outcomes. Prepare demonstration models and poster presentations.


### Grading Breakdown

- **Paper Presentation**: 30%
- **Project Proposal**: 10%
- **Execution**: 30%
- **Demonstration**: 10%
- **Project Presentation**: 10%
- **Class Participation**: 10%



## **Calender:**

**(subject to change)**

# Course Calendar: 

| Week | Date | Lecture Topics | Slides | Readings |
|------|------|----------------|--------|----------|
| 1    |  Oct 1    |     Introduction           |  [Introduction and Course Overview](https://drive.google.com/file/d/1-Vxxf6rQRE6h3SczQq0VXdqqYzRH9f5s/view?usp=sharing)  [Introduction to Causal Inference](https://drive.google.com/file/d/1-c3cbYkAfX9MNF16m_-FiRi-ZzSt5PXU/view?usp=sharing)    |       * [Yuval Noah Harari argues that AI has hacked the operating system of human civilization](https://www.economist.com/by-invitation/2023/04/28/yuval-noah-harari-argues-that-ai-has-hacked-the-operating-system-of-human-civilisation)<br> * [Book Extract: Yuval Noah Harari on AI](https://www.theguardian.com/technology/article/2024/aug/24/yuval-noah-harari-ai-book-extract-nexus)<br> * [President Biden Issues Executive Order on Safe, Secure, and Trustworthy Artificial Intelligence](https://www.whitehouse.gov/briefing-room/statements-releases/2023/10/30/fact-sheet-president-biden-issues-executive-order-on-safe-secure-and-trustworthy-artificial-intelligence)<br> * [AI, Fake News, and Misinformation](https://www.washingtonpost.com/technology/2023/12/17/ai-fake-news-misinformation/)<br> * [Generative AI is the Ultimate Disinformation Amplifier](https://akademie.dw.com/en/generative-ai-is-the-ultimate-disinformation-amplifier/a-68593890)  |
| 2    |   Oct 8   |        Graphical Models and Potential Outcomes        |    [Graphical Models](https://drive.google.com/file/d/1-2uXezfU5uWyZ29g_ijtpYoQRskokzpO/view?usp=sharing) [Potential Outcomes](https://drive.google.com/file/d/1-3DO_Z25rcU1x5adhIwEv_39JWj41tk4/view)    |          |
| 3    |   Oct 15   |        Structural Causal Models        |    [Structural Causal Models](https://drive.google.com/file/d/11kuirVbjFGp6gLN-WWgjWYvlLC3SuNc6/view?usp=sharing)    |          |
| 4    |   Oct 22   |        Algorithmic Fairness        |    [Algorithmic Fairness](https://drive.google.com/file/d/11MqXj5uQfXfYJ30EyMIMz9N4u2R7ZjZ4/view?usp=sharing)    |          |
| 5    |   Nov 7   |      Bias Mitigation  <br> Group 3 Presentation          |   [Bias Mitigation](https://drive.google.com/file/d/11MqXj5uQfXfYJ30EyMIMz9N4u2R7ZjZ4/view?usp=sharing)       |  <br> * [Optimal Transport Blog Post](https://alexhwilliams.info/itsneuronalblog/2020/10/09/optimal-transport/) <br> * [Paper 1](https://arxiv.org/abs/2403.02372) [Paper 2](https://arxiv.org/abs/2212.10839) <br> * [Group 3 Paper 1](https://ojs.aaai.org/index.php/AAAI/article/view/17135)          |
| 6    | Nov 12 |  Group 4 Presentation  <br> Group 1 Presentation   |        | * [Group 4 Paper 1](https://www.nature.com/articles/s42256-019-0048-x) <br> * [Group 1 Paper 1](https://proceedings.neurips.cc/paper/2018/hash/d04863f100d59b3eb688a11f95b0ae60-Abstract.html) [Group 1 Paper 2](https://proceedings.mlr.press/v80/mirman18b/mirman18b.pdf) [Group 1 Paper 3](https://arxiv.org/abs/2210.07394)      |
| 7    | Nov 14 | Group 2 Presentation  <br> Group 5 Presentation   |        | * [Group 2 Paper 1](https://arxiv.org/pdf/1909.06677) [Group 2 Paper 2](https://arxiv.org/abs/2304.10655) <br> * [Group 5 Paper 1](https://arxiv.org/abs/2403.06634) [Group 5 Paper 2](https://arxiv.org/abs/2202.07646)       |
| 8    | Nov 19 | Group 8 Presentation  <br> Group 9 Presentation               |        |  * [Group 8 Paper 1](https://arxiv.org/abs/2110.14297) [Group 8 Paper 2](https://arxiv.org/abs/1810.03292)        |
| 9    | Nov 21 | Group 6 Presentation  <br> Group 7 Presentation               |        | * [Group 6 Paper 1](https://arxiv.org/abs/2312.04350) [Group 6 Paper 2](https://arxiv.org/abs/2305.00050) <br> * [Group 7 Paper 1](https://arxiv.org/abs/2201.12872) [Group 7 Paper 2](https://arxiv.org/abs/2103.05045)     |
| 10   | Nov 26 |                |        |          |
       

**Note**: The readings and slides are placeholders and should be replaced with actual links to resources.





## Textbook

[Causal Inference in Statistics: A Primer
](http://bayes.cs.ucla.edu/PRIMER/) 

[Trustworthy Machine Learning](http://www.trustworthymachinelearning.com/)

[Fairness and Machine Learning: Limitations and Opportunities](https://fairmlbook.org/)

[Interpretable Machine Learning
A Guide for Making Black Box Models Explainable](https://christophm.github.io/interpretable-ml-book/)


