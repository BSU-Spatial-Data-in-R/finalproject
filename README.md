# Final Project

## Overview

The final project is an opportunity to bring all of the things you've learned in the course into a single reproducible workflow to answer a question of your choosing. Because each of you are in different stages of collecting your own data and because confronting datasets that aren’t yours can help clarify important concepts and design elements, I’m asking you to **develop an analysis of data that isn’t yours**. This final project should help you demonstrate:

* Proper data management, cleaning, and manipulation technques

* The ability to summarize spatial data and apply different statistical analyses to it

* The ability to evaluate the performance of statistical models

* The ability to generate visualizations that support your analyses

* The ability to integrate code, analysis, and visualization with text descrbing your approach and discussing your results

## Instructions

1. After you've joined the assignment repository, you should have this file (named Readme.md) inside of a R project named finalproject-xx where xx is your github username (or initials).

2. Once you've verified that you've correctly cloned the assignment repository, create a new Quarto document. Name this file finalproject-xxx.qmd and give it a title (like M Williamson Final Project). Make sure that you select the html output option (Quarto can do a lot of cool things, but the html format is the least-likely to cause you additional headaches). We'll be using Quarto throughout the course so it's worth checking out the other tutorials in the getting started section.

3. Copy the questions below into your document and change the color of their text.

4. Save the changes and make your first commit!

5. Answer the questions making sure save and commit at least 4 more times (having 5 commits is part of the assignment).

6. Render the document to html (you should now have at least 3 files in the repository: Readme.md, finalproject-xx.qmd, and finalproject-xx.html). Commit these changes and push them to the repository on GitHub. You should see the files there when you go to github.com.

** Remember to save your data to the folder with your name in our shared [Google Drive](https://drive.google.com/drive/u/0/folders/1ca87_eYhoWtQwX8upiiAiajX39PM_S1X) so that it syncs to the server and all of the pathnames work.**

## Requirements

**Datasets.** The ability to manipulate and integrate a variety of data types, resolutions, and formats is a key component of this course. Your analysis should incorporate at least 5 datasets. The ultimate compostion of your database is up to you, but I'd like you to include 1 tabular dataset, 1 vector dataset, and 1 raster dataset. You should choose the other 2 (or more) to give you practice with the data types that are most relevant to your objectives and/or research.

**Analyses.** You've learned several classes of analyses (e.g., overlays, point-pattern, multivariate regression, and statistical learning). Apply at least one (preferably the one most tied to your own objectives and research) of these analyses to address your question. In the course of doing so, you'll need to justify your choice, assess whether your data meets appropriate assumptions, and evaluate the implications of key assumptions you make. For example, if you're conducting an overlay analysis, how does your choice of threshold affect the ultimate result? If you've fit a statistical model based on summary statistics (e.g, mean, median), how well does the model fit? How does the model change if you use different slices of the data?

**Visualizations.** You should produce a minimum of 3 visualizations to accompany your analysis. One of these should be a publication quality location map. The others are up to you, but should a) help you tell the story of your analysis and b) help you meet your objectives for the course and your own research. These can be additional maps of results, figures that summarize your data or results in non-spatial ways, or interactive graphics that allow you to explore parts of your analysis. 

**Reporting**

You can generate a 'manuscript' style document (using Quarto) or a flexdashboard (using Quarto and shiny) as the final product. Your report should include:

1. A brief (1-2 paragraphs) description of your question and why you're interested in it.

2. A Methods section with subsections describing the data sources, any processing steps you took and why, and your process for the analysis. Show your code and provide annotation to describe what you are attempting do with the various steps.

3. A Results section that includes tabular results as well as any relevant visualizations that describe your data and analysis.

4. A Discussion of your results that puts your results in the context of your question, considers alternative analysis strategies and why they may or may not be better than the approach you chose, describes additional data that might be important for your question, and considers the role of extent and resolution in your analysis.

