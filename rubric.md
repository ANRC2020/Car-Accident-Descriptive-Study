# Rubric

## Introduction

An introduction that is scored in the top level has very successfully made the case for the study. It will have explained why the topic is interesting, and provided compelling reasons to care about not just the general area, but rather about every concept in the research question and the statistical results to be generated. The introduction will be engaging from the very first sentence, and create a logical story that leads the reader step-by-step to the research question. After reading the introduction, no part of the research question will appear arbitrary or unexpected, instead flowing naturally from the background provided.

## Operationalization

A report that is scored in the top level on operationalization will have precisely articulated and justified the decisions leading to the variables used in the analysis. The reader will be left with a clear understanding of the concepts in the research question, and how they relate to the operational definitions, including any major gaps that may impact the interpretation of results. You should also list how many observations you remove and for what reasons. When there is more than one reasonable way to operationalize a concept, the report will explain the alternatives and provide reasons for the one that was selected. Note that there is often more than one way to operationalize a concept; we are less interested in whether you make the best possible choice, and more in how well you defend your decisions.

## Data Understanding

A report that is scored in the top level will describe the provenance of the data; the audience will know the source of the data, the method used to collect the data, the units of observation of the data, and important features of the data that are useful for judging the analysis.

## Data Wrangling

A report that is scored in the top level on data wrangling will have succeeded to produce a modern, legible data pipeline from raw data to data for analysis. Because there are many pieces of data that are being marshaled, the reports that score in the top level will have refactored different steps in the data handling into separate files, functions, or other units. It should be clear what, and how, any additional features are derived from this data. The analysis avoid defining additional data frames when a single source of truth data would suffice. 

## Visualization

You are required to include at least one plot or table in your report.  A report that is scored in the top level will include plots that effectively transmit information, engage the reader's interest, maximize usability, and follow best practices of data visualization.  Titles and labels will be informative and written in plain english, avoiding variable names or other artifacts of R code.  Plots will have a good ratio of information to space or information to ink; a large or complicated plot will not be used when simple plot or table would show the same information more directly.  Axis limits will be chosen to minimize visual distortion and avoid misleading the viewer.  Plots will be free of visual artifacts created by binning.  Colors and line types will be chosen to reinforce the meanings of variable levels and with thought given to accessibility for the visually-impaired. Your report will be free of "output dumps" - code output that has not been formatted for human-readability. Every single plot and table in the report will be discussed in the narrative of the report.

## Model Specification

A report that is scored in the top level will have chosen a set of regression models that strongly support the goal of the study.  The X-concept of the research question will be represented in a coefficient(s) in every model.  Variables transformations will be chosen to inform the reader of the shape of the joint distribution, and will be human-understandable. If covariates are included, they will be well motivated and will lead to useful insights for the reader. Ordinal variables will not be treated as metric.  Each specification will be a sound, defensible model, and the specifications will be different from each other, outlining the space of reasonable modeling choices.

## Model Assumptions

A report that scores in the top-level has provided an thorough and precise assessment of the assumptions supporting the regression. The list of assumptions is appropriate given the sample size and modeling goals. Each assumption is evaluated fairly, and discussed defensively - without overstating how credible the assumption is or rendering a final up-or-down judgement on the assumption. The report will not miss any important violations of any assumption. Where possible, the report discusses the consequences for the analysis of a violated assumption.

## Model Results and Interpretation

A report that scores in the top level will have interpreted the results of the model appropriately, drawn a conclusion about statistical significance; discussed the practical significance using an effect size measure that is technically correct and well chosen to be compelling to the reader; discussed the broader implications of the results; and will have done so in a way that is clear, concise, and correct. 

## Overall Effect

A report that scores in the top level will have met expectations for professionalism in data-based writing, reasoning and argument for this point in the course. It can be presented, as is, to another student in the course, and that student could read, interpret and take away the aims, intents, and conclusions of the report. 