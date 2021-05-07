## Prediciting Brazilian music from Spotify Playlists with Unsupervised Machine Learning
A project by [Francisco Ebeling](https://github.com/ebelingbarros).

![Picture](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/pic06brasil.jpg)

## Contents:

- [The project](#The_project)
- [The files](#The-files)
- [Vizualizations and results](#Vizualisations-and-results)

***


## The project
The business analytics team Fleur Delacour, aka the authors of this project, were asked to answer some business questions for a real estate company using a dataset of almost 22.000 real estate sales in Washington state, USA.

To answer the basic questions of the business, we imported the data into a SQL database using MySQL and the MySQL Workbench client.

Additionally, the company wanted to explore some relationships within the data using visualizations to make these relationships easy to consume for the stakeholders and decision-makers. We used Tableau to achieve this goal.

Finally, the company wanted to predict the price of real estate units with the given data. 
We achieved this by applying multiple linear regression algorithms after cleaning and wrangling the data with python in Jupyter Notebook.
After our first approach, we finetuned the model to increase the precision of our predictions.

After our analysis was completed, we delivered our insights in a 5-minute presentation, focussing on the business implications of our results. 

## The files
- Slides with the business implications: [Here](https://docs.google.com/presentation/d/1mR-rkAEYC1kN9f_6xhFMIaHyXNbBA2OWy5GpS1C8iw8/edit#slide=id.gc59bf226dc_0_2)
- A live presentation of our conclusions: Recorded and uploaded later to the repo
- Questions and answers using SQL: [SQL_File](https://github.com/Caparisun/Linear_Regression_Project/blob/master/SQL_Files/Regression%20project.sql) and the [solutions](https://github.com/Caparisun/Linear_Regression_Project/blob/master/SQL_Files/README.md)
- A Tableau dashboard: [Story](https://public.tableau.com/profile/federico.giuliani#!/vizhome/Mid_Project_Data/StoryProject?publish=yes) and [solutions](https://github.com/Caparisun/Linear_Regression_Project/blob/master/Tableau/readme.md)
- Exploration of the data: [Jupyter Notebook](https://github.com/Caparisun/Linear_Regression_Project/blob/master/Notebooks_and_data/1.basic_data_exploration.ipynb)
- Data cleaning and wrangling: [Jupyter Notebook](https://github.com/Caparisun/Linear_Regression_Project/blob/master/Notebooks_and_data/2.Datawrangling.ipynb)
- Applying the models: [Jupyter Notebook](https://github.com/Caparisun/Linear_Regression_Project/blob/master/Notebooks_and_data/3.Applying_Model.ipynb)
- Applying the same models to a normalized data frame [Jupyter Notebook](https://github.com/Caparisun/Linear_Regression_Project/blob/master/Notebooks_and_data/5.applying_model_norm.ipynb)
- Refinement of the first model, exploring multiple different wrangling approaches [Jupyter Notebook](https://github.com/Caparisun/Linear_Regression_Project/blob/master/Notebooks_and_data/6.Refinement.ipynb)

We will provide a quick summary of the solutions further below, but first, we want to outline our process.

## Visualizations and results

![Picture](https://github.com/Caparisun/data_mid_bootcamp_project_regression/blob/master/Pictures/Process.jpg)


%%html
<div class='tableauPlaceholder' id='viz1620387883133' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Br&#47;Brazilianmusicprediction-featuresclustered&#47;Story1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Brazilianmusicprediction-featuresclustered&#47;Story1' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Br&#47;Brazilianmusicprediction-featuresclustered&#47;Story1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='de' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1620387883133');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='1014px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>



