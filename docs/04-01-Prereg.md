

# Pre-registration guidance {#Prereg-overview}

## Overview and submission details

The two main submissions for this project are:

1. The group pre-registration (1000 word limit, worth 30% of the course)

2. The individual full report (3000 word limit, worth 50% of the course)

These are two individual but connected assignments. You will collaboratively write the pre-registration in groups of 5 or 6 to plan your study. You will then individually write the full report, applying what you planned in the pre-registration. 

<img src="images/prereg vs full report.png" alt="Collaboratively write the pre-registration then individually write the full report" width="100%" style="display: block; margin: auto;" />

In this chapter, we will focus on the pre-registration as the first major assignment of semester 2. The word limit includes all the text within your responses to the five questions at the start of the pre-registration template, including any in-text citations. However, it **does not** include the text of the questions in the template, your reference list, or your analysis code

Please submit the completed .Rmd file, the two data files, and a copy of the knitted Word file. For further details and confirmation of the deadline, please see the **pre-registration AIS** on the Moodle course overview page.

Your marker should be able to download all of the files and reproduce the knitted Word document without any errors. Before you change anything, knit the file to make sure there are no initial errors. Once you have a complete draft, we also recommend making sure another member of your group can knit the document to ensure it is reproducible across different computers.

One member of your group should submit on behalf of the team. After the submission deadline, peer ratings will be available to judge your contribution and the contribution of everyone in your group.

## Group work

Before we outline the role of pre-registration and the template you will complete, it is important to consider group work. Everyone should contribute equally but this does not mean that everyone needs to independently complete every question. If you have not done so already, read the [chapter dedicated to group work](#groupagreement-AIS) where we outline the group work agreement, our expectations around working respectfully and professionally, and task sharing advice. 

You may wish to divide the work:

- By writing/coding

- By question

**Remember though**: Everyone should understand each bit and be able to run and adapt the analysis code as you will need to work individually for the final data analysis and write-up.

## The role of pre-registration

For the development and history behind the rise of pre-registration in psychology, you might want to revisit semester 1 week 2 where we introduced the replication crisis, and week 14 where we looked at past and future developments in the open science movement.

A pre-registration outlines your research design and analysis plan ahead of time. You are writing down your plan for what you are going to do before you collect and/or analyse your data (<a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5856500/" target="_blank">Nosek et al., 2018</a>). As scientists, we want to distinguish between what we planned ahead of time compared to what we decided after seeing the outcome.

When you design your study and consider how you will analyse your data, there are many decisions to make:

-   What do I predict will happen?

-   How many people should I test?

-   Who should I test?

-   Which groups will I compare?

-   What data should I exclude?

-   What do I measure?

-   How do I measure it?

-   What statistical test should I use?

-   What alpha value should I use?

During the replication crisis, psychologists recognised the flexibility in those decisions could - intentionally or unintentionally - produce specific results. It is easy to forget what you originally planned when you analyse the data weeks, months, or even years later, and it is easy to convince yourself that your decision makes sense when the results look like what you were expecting.

So, the aim of pre-registration is to constrain as many of those decisions in advance as possible; the more specific the better (<a href="https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3000937" target="_blank">Bakker et al., 2020</a>). This means after you submit the pre-registration, you can look back and check what you planned to do. If you need to change your plan, then you can transparently explain what changed and why you changed it.

## Deviations from your pre-registration

A pre-registration is your plan - to the best of your knowledge - going into data collection and data analysis. However, like the title of an influential blog post, it is a plan and not a prison (<a href="https://www.cos.io/blog/preregistration-plan-not-prison" target="_blank">DeHaven, 2017</a>). In a study surveying researchers on the perceived costs and benefits, 8.4% mistakenly believed that pre-registration means there is no room for exploratory analyses (<a href="https://www.sciencedirect.com/science/article/pii/S0749597821000649" target="_blank">Logg & Dorison, 2021</a>).

In reality, there is nothing stopping you from changing your plan. When it comes to your final analysis, you may need to change your plan for many reasons:

- Missing data causes an issue;

- Problems with statistical assumptions you did not anticipate;

- You realised your plan was not a good one (<a href="https://bartlettje.github.io/2017-03-29-effective-preregistration/" target="_blank">James wrote</a> about his first attempt at pre-registration which was not great...).

What matters is transparency; pre-registration forces you to outline what you planned from the start and what you changed. There are some components which **should not** change, like your hypotheses. But there are plenty others like your choice of statistical test which can change if you have a rationale for doing so.

## How will the preregistration differ to your final report?

One common question is how the pre-registration and the data you are using will differ to your final report.

In a typical study, you write the pre-registration before collecting data, or the very least before analysing the data. It is your plan for how you will design your study and analyse the data. It can be difficult to imagine and precisely describe the data analysis process without data, so it is normally a good idea to use fake data that is in the same format as your real data. This means you can demonstrate how you will analyse the data based on this fake data. It is **not** there to many any conclusions, you are just using it to demonstrate your plan.

This is what we are trying to recreate in this assignment, but we share a small chunk of the real data for you to use. This means you can see how the data will look and demonstrate the code you will use to process and analyse the data.

<img src="images/prereg data.png" alt="preregistration data extract vs the full data set" width="100%" style="display: block; margin: auto;" />

Once you get the final real data files, you will be able to replace the preregistration data files and use the same code. It is this point you start making conclusions and thinking whether you addressed your research question and your hypothesis or not. 

::: {.dangerous data-latex=""}
You **do not** need to compare your final results to what you observed in the pre-registration as that was only to demonstrate your plan.
:::

Preparing the data analysis plan and coding means you did a lot of the hard work ahead of time and you only have to check your plan is still a good idea. <a href="https://www.sciencedirect.com/science/article/pii/S0749597821000649" target="_blank">Logg and Dorison (2021)</a> found 79% of researcher agreed pre-registration helps clarify ideas before running a study and 50% agreed it front-loads work in reporting your findings. If there is something you did not consider ahead of time - like not meeting one of the statistical assumptions - then you can edit your code and explain in your report there were deviations from your plan.

## Question guidance

In this section, we have outlined each question you will complete with some points of advice and reference to where you can revise the relevant content from semester 1 and 2. You can download the pre-registration template from the "Project resources for the pre-registration and report" tab of RM1 ODL Moodle. 

::: {.warning data-latex=""}
All sections should be written in coherent paragraphs and not as bullet points or lists. The below is just a guide of the elements that should be covered. Most sections can be supported by citations, so try to include them where you make a decision and where you need evidence.
:::

### 1. Present a concise evidence-based rationale, for the current study, along with your research question and hypothesis.

Be concise. This is not the full introduction to your report, it is a check that you have read a selection of the literature to inform your research question and hypothesis. See semester 1 week 3 and week 4 for types of evidence and using citations. See the [Finding, Reading, and Organising Journal Articles chapter](#Writing-02) for guidance. 

Remember that the rationale is a snapshot of the future introduction. Remember logical flow and the overall structure of a rationale. See semester 2 week 3 on introductions, the rationale, research questions, and hypotheses. The [Structure of the Introduction and Rationale](#intro-rationale) chapter outlines the introduction and different strategies for identifying a rationale. 

Ensure you clearly outline your research question and hypothesis at the end of the rationale. Make sure your hypothesis is fully operationalised.

### 2. Describe the key variables, specifying how they will be measured, how many levels they have (if relevant), and how participants will be assigned (if relevant).

Your approach to this question will depend on whether you are using a correlation and two sub-scales from the MSLQ, or a t-test using one sub-scale and one categorical demographic variable. Think about what information you will need depending on the design you are planning to use. See semester 1 week 1 and 3 for research design terminology and descriptive statistics. The [MSLQ Overview chapter](#MSLQ-overview) defines all the sub-scales and demographic variables you can use. 

For the MSLQ sub-scales, think about:

-   Which sub-scales are you using?

-   How are they calculated (mean/sum)?

-   How many questions do they have?

-   What are the minimum and maximum scores?

-   Are they valid and reliable?

For categorical demographic variables, think about:

-   How many levels does each category have?

-   How are these levels defined, e.g., who is a mature student?

### 3. Describe your precise rule(s) for including and/or excluding observations and/or participants in your study.

There is a subtle difference between inclusion and exclusion criteria. Inclusion criteria are the specific participants you are looking for. Participants must meet the criteria to be included in your study. For example:

-   Are you only interested in postgraduate students?

-   Are you only going to include mature students?

-   Are you looking for a specific age range?

Remember **you** are making these specific decisions. If you are focusing on a specific sample/population, then think about whether this follows logically from your rationale with supporting citations.

Exclusion criteria are applied to the participants that have been included in your study. They meet your inclusion criteria, but you are checking to see if they can be included in the data analysis. For example:

-   Will you exclude people who have missing data? If so, is this the case for any missing data, or only certain variables?

-   Are there any variables where you would consider certain values to be outliers? What happens if one person scores much higher or lower compared to the rest of your sample?

This is probably the first time you have completed a research report like this, so you might not have all the answers at this point. A good thing to do is note any reasons why people were excluded from the papers you were reading and think about if they apply here. This is another area where it is important to justify your decisions with supporting evidence where possible. There are many ways of identifying outliers, so which method did you use and why? Semester 2 week 4 outlines decision making in data analysis and covers concepts like outliers and missing data. 

### 4. Describe exactly which inferential analysis you will conduct to test your hypothesis. Include details of any assumption tests you will conduct.

In this question, you will outline which statistical test will help you best address your research question and hypothesis, given your design. See semester 1 weeks 6-12 on hypothesis testing and statistical tests. Be as specific and precise as you can, considering:

-   What type of correlation/t-test best suits the data you are working with? Pearson, Spearman. Student's between-subjects, Welch's between-subjects, etc.

-   How will you test the assumptions? What will you do if those tests fail? Think about stating the assumptions and how you will test them through visualisations or statistical tests.

-   What alpha value will you use?

-   Would a one- or two-tailed test best address your hypothesis?

Where necessary, justify your decisions with supporting citations. For example, is there a paper that says one test is more appropriate than another?

### 5. Discuss how many observations/participants will be required to detect your smallest effect size of interest, based on your alpha and power. Provide the rationale for your choice of the smallest effect size of interest.

Ultimately, you do not have control over the final sample size because the data already exist; we have been collecting the data successively over the last few years. However, it is important to show you can justify your sample size and inform your decision with a power analysis even when it might be different to the final sample size.

This will be important when it comes to your dissertation and any future research when you could perform a power analysis to justify what sample size you aim for. For this question, your power analysis will solve for "n" - the number of people needed. Once you know the final sample size, you can reflect on your final sample size and the sample size you were aiming for in the pre-registration. 

See semester 1 weeks 6-11 for revising statistical power as a concept and how it applies to correlations and t-tests. Chapter 11 of the data skills book <a href="https://psyteachr.github.io/quant-fun-v2/power-and-effect-sizes.html" target="_blank">Fundamentals of Quantitative Analysis</a> demonstrates how to perform a power analysis using R. Semester 2 week 5 will also specifically address pre-registering a power analysis.

You will need to think about the inputs you use for the power analysis (you might find <a href="https://open.lnu.se/index.php/metapsychology/article/view/3078" target="_blank">Bartlett and Charles (2022)</a> useful for thinking about the decisions you need to make):

-   Alpha

-   Your smallest effect size of interest

-   Power

-   Whether you are using a one- or two-tailed test

You can establish the smallest effect size of interest in numerous ways such as previous studies, a review, or a meta-analysis. We will spend more time on this decision and the process of pre-registering a power analysis in semester 2 week 5. However, it is best not to use the pre-registration data extract to establish an effect size for your final data.

### 6. References

Please provide the reference list for any citations you use in answering the questions above. The reference list should be consistent with APA 7th edition, but note we do not expect details like a hanging indent since its difficult to format in an R Markdown document. For example:

Logg, J. M., & Dorison, C. A. (2021). Pre-registration: Weighing costs and benefits for researchers. *Organizational Behavior and Human Decision Processes, 167*, 18-27. https://doi.org/10.1016/j.obhdp.2021.05.006

### 7. Analysis code

The completed .Rmd file for the pre-registration should contain your analysis code in R using the pre-registration data extract we supplied.

The final data set will be in the same format so you can reuse the code. Analysing the mock data allows you to visualise what the final data might look like and helps you recognise the decisions you will need to make.

You may not be able to prepare all of the code now, but you can do most of the wrangling, processing, and planned statistical tests. For example, you might not be able to prepare the code to remove everyone based on a given criterion just yet as it might not apply to the data extract and only the full data will allow that, but you can definitely make a start on all of the sections.

## Preregistration examples

As a final reference point, you might find it useful to look at examples of pre-registrations to see how they are framed. Just keep in mind there are different pre-registration templates. Some are shorter, while others are longer. Remember this is an assessment, so they might include additional sections we have not asked you to include, so make sure you follow the template we provide.

**Note**: These examples are not meant to provide a gold standard of what to aim for. Their writing style, presentation, and content might be different to guidance we have provided throughout this course. We just think it is useful to see different examples of a pre-registration and use them to reflect on your own work.

1.  Moeller and Paterson (2019): <a href="https://doi.org/10.17605/OSF.IO/XTK9Q" target="_blank">In the face of intellectual disability</a>.

2.  Palmer and Bartlett (2019): <a href="https://osf.io/dg7w5?view_only=None" target="_blank">Faith Impaired Perceptions of Self-Forgiveness</a>.

3.  Zulkefli, Tulloch, and Bartlett (2022): <a href="https://osf.io/t645q" target="_blank">Emotion Regulation and Socioeconomic Status : A Cross-Cultural Replication Study</a>.
