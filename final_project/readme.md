# BA 505 Final Projects
## Fall 2018
__This is last year's final project document, it will be updated later in the semester.__

## Overview
Students work in 3-person teams to define and complete a moderately-sized analytical project in Python. Detailed instructions are provided regarding selecting and framing a suitable analysis. Grading criteria will reflect demonstrated achievement of the objectives and compliance with the requirements.

## Objectives
* Apply Python skills to a student-selected analytical project of moderate (but nontrivial) scope and complexity.
* Demonstrate mastery of Python, NumPy, Pandas, Matplolib, Jupyter, and GitHub.
* Work in teams, with professional-quality tools and standards.

## Project Requirements
* **All work must be your own.** It is your responsibility to demonstrate the unique contributions made by your work. You are also expected to thoroughly understand and be able to explain any work done by your teammates.
* **Academic honesty policies and scholarship norms apply.** All relevant previous work and data sources must be properly cited.
* **The analysis must be fully reproducible, even and especially with new data.** This is to be professional work, subject to prevalent standards. Suggestion: create a separate module to load/clean/integrate your data. That will allow us to test and reuse your work in other projects.
* **Descriptive analytics (as in QA400) are sufficient.** However, there is no need to constrain your work. If you can apply forecasting or decision modeling, then feel free to do so.
* **The analysis should stand on its own.** All work will be posted a *public* repository created via GitHub Classroom. You will be asked to present your work on the final day of class, but the analysis itself should be readily accessible and understandable from your GitHub repositories without installing any additional software.
* **Project size and scope should be sufficient to demonstrate mastery of Python, NumPy, Pandas, and Matplotlib.** At a minimum the datasets used should have at least 10K records with a dozen or more fields. Further, there should be some opportunity for you to filter/reduce/analyze the data using Pandas and NumPy. If the work could just as easily be performed by an undergraduate in Excel, then keep looking for another project.
* **All data used must be posted in your GitHub repository.** If you are borrowing data from Kaggle, then please cite the original source in your `Readme.md` file. It should be possible for anyone to reproduce your work, including collecting the data from original sources.
* **Document your work.** At a minimum, each analytical step (code cell) should be documented with markdown cells above and below stating your intention (above) and interpretation (below). Your notebooks should tell a story about the data. **One should be able to read the rendered notebook in GitHub and know exactly what you did, why you did it, and why we should care about the results.**

## Instructions  

1. **Watch and learn.** Study the following tutorial, which sets the bar for what constitutes A-level work in this course:  
[Reproducible Data Analysis in Jupyter](https://jakevdp.github.io/blog/2017/03/03/reproducible-data-analysis-in-jupyter)  
The tutorial is in 10 parts, with some of the more advanced work in the second half. At a minimum, your project should use the practices demonstrated in videos 1-5. To get the best grade, however, try something more advanced like the practices shown in videos 6-10.  
2. **Survey the best examples you can find.** One very convenient place to look is [Kaggle](https://kaggle.com), which has submissions from numerous data analytics competitions. Here a few particularly engaging Kaggle submissions to study:
  * [asindico//from-exploration-to-prediction](https://www.kaggle.com/asindico/from-exploration-to-prediction)
  * [anokas/exploratory-data-analysis-4 2017](https://www.kaggle.com/anokas/exploratory-data-analysis-4)
  * [sudalairajkumar/simple-exploration-notebook-5](https://www.kaggle.com/sudalairajkumar/simple-exploration-notebook-5)
  * [pmarcelino/comprehensive-data-exploration-with-python](https://www.kaggle.com/pmarcelino/comprehensive-data-exploration-with-python)

   While some are more "finished" than others, you'll find that each tells a story with data. Try to learn to do that.  

3. **Find a suitable data source.** It must meet the requirements above. Collecting your own data (from an API, crawling/scraping, etc.) is encouraged though not required. If you are using a dataset discovered through Kaggle, then be sure to cite it and state how the analysis you are doing is different. Whatever you do, don't just replicate someone else's analysis. That will result in an immediate F for the course and (very likely) expulsion from the program. 
4. **Develop a few research questions that you'd like to answer based on the data.** The questions should be stated in the preamble to your notebook. The analysis should also demonstrate your abilities. Read the requirements again to makes sure your analysis will comply.
5. **Do some analysis**. This is likely to be a learn-as-you-go process. Suggestion: each team member should keep a scratch notebook file for trying things out. Then transfer your work to the finished notebook just before completion. However, delete your scratch notebooks just before your final commit and push to GitHub. 
6. **Try something more advanced.** Once you have a basic framework for your analysis, extend it with something more advanced. Perhaps you could try an advanced plot or maybe another data source or maybe replicated sampling to demonstrate reproducibility/lack of bias.
7. **Write and commit a `Readme.md` file inside your repository outlining your project.** This file is what GitHub will display by default for your repository, so make a good impression. It's standard Markdown, just like we use in Jupyter. Instead of using slides, you will start and end your final presentation with the `Readme.md`, so use it to link to all your files and provide (meta) information about your project: motivations, data sources, challenges, lessons learned, etc. Suggestion: write this stuff early and update it as you go along.
8. **Clean up your final notebook and GitHub repo.** The final notebook is your presentation (i.e., there will be no slides) so make sure it is readable on a TV monitor from across the room. It is also your report, so make sure every objective, decision, interpretation, and conclusion you make is throughly explained and professional-looking. (Yes, styling and organization matters. We're professionals, right?) Make sure you don't have any unfinished or extraneous artifacts left over from your explorations. (Again, we're professionals, not undergrads.)

## Timeline/Workplan
* **Nov 6:** Review assignment, form teams, and begin planning out the work. Do not create any shared GitHub repositories yet. 
* **Nov 13:** Follow instructions in class to set up your teams and shared repositories in GitHub classroom. Also prepare a short (5-minute verbal) walkthrough for your project that covers i) data source; ii) research questions; iii) anticipated challenges; and iv) what results you expect to present on the final day of class.
* **Nov 20 and 29:** Use the class time to meet with your team and ask questions when needed. (Note: You are expected to show up for class. We have other classwork like Quiz 5 to do yet.)
* **Dec 4:** Preview of your results. This is like a dress rehearsal to address any remaining problems before your final presentations. 
* **Dec 11:** Present your finished work. Walk us through your project, including your source/motivations, finished notebook, modules/testing, and lessons learned. There will be no slides for this. Just use your work. See the instructions for the `Readme.md` file above. 
