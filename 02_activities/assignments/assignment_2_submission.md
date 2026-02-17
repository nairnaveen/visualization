# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Your answer...

> To evaluate data visualization, we must do it on the 3 core principles - (i) Aesthetic - pleasing to look at, (ii)Substantive - accurate and honest data presentation and (iii) Perceptual - what message is conveyed.
> 
### Example of good visualization: <b>"1854 Broad Street Cholera Outbreak Map <i>by John Snow</i>x`"</b>
>
> Reference - __[Jon Snow's Cholera Outbreak Map] (https://public.tableau.com/app/profile/lidia.vale.starling/viz/Dr_JohnSnowCholeraOutbreakMap/Dashboard1)__
>
> The 1854 Broad Street Cholera Outbreak Map is an outstanding example of integrity and functionality over decoration. 
> (i) Aesthetic - Dr. Snow presented the data (number of deaths) on a spatial layout (street map) using small black bars to represent deaths at specific addresses. The data implements __[Tuffe's principles](https://thedoublethink.com/tuftes-principles-for-visualizing-quantitative-information/)__ using simple marks to convey profound meaning by maximizing clarity, precision, and efficiency by prioritizing data content over design ornamentation.
> (ii) Substantive - The visualization uses __[Gestalt principle](https://www.gestaltprinciples.com/)__ of proximity to show a clear cluster of deaths around a specific water pump. This prompts the viewer to focus on the "insight" (the pump is the source of the infection) and not just the "data" (lists of names).
> (iii) Perceptual - Use of map layout helps the viewer to understand the data without the unnecessary effects or colors that create "noise". The message was clear to point out the source and prevention measures thru elimination / containment of source. 
>
>
### Example of bad visualization: <b>"The Challenger disaster - <i>Tufte's graph</i>x`"</b>
>
Reference - __[Tufte's graph] (https://stanfordmag.org/contents/elemental-evidence)__
>
> The Challenger disaster - is a poignant example of how poor data visualization can severe consequences.
> (i) Aesthetic - The charts used icons of rockets to represent flights. This cutesy icons of rockets obscured key numbers and distracted the viewer from the actual measurements.
> (ii) Substantive - the charts only depicted flights that had experienced damage and excluded data for flights that had no damage. Thus by sampling on the dependent variable and by removing the "successes," they made it impossible to see the trend that O-rings failed more frequently as temperatures dropped.
> (iii) Perceptual - The data was organized chronologically rather than by temperature and listed flight numbers and O-ring damage thus failing to clearly link that damage to outside temperature.




      ```
    - How could this data visualization have been improved?  
      ```
      Your answer...
### For the good visualization example of <b>"1854 Broad Street Cholera Outbreak Map <i>by John Snow</i>x`"</b>
> With the availability of modern digital tools, one could improve the interactivity and layering.
> (i) Use of animation. A __[slider](https://plotly.com/python/range-slider/)__ could show the progression of outbreak over time
> (ii) Use of heat mapping. A density __[gradient heat mapping](https://plotly.com/python/heatmaps/)__ could mark high density areas to the viewer and thus depict the gravity of the situation.
>
>
### For the bad visualization example of <b>"The Challenger disaster - <i>Tufte's graph</i>x`"</b>
> Tufte redesigned the visualization to depict relationship between temperature during launches and incidents of damage to O-rings __Reference - [Tufte;s graph](https://www.asktog.com/books/challenger3.gif)__
> (i) Include data of all flights - this would have depicted that no flight had ever succeeded below $65^{\circ}F$ ($18^{\circ}C$) without some form of O-ring distress.
> (ii) Addition of regression line. A simple regression line would have visually demonstrated the exponential increase in risk as the temperature moved toward the predicted $29^{\circ}F$ launch time temperature.

      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 02/16/2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
