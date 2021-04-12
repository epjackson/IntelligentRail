EDWARD JACKSON
Capstone submission - Intelligent Rail

Please note that there are significant changes to this project since the presentations
as a result hyperparameter optimisation and further feature engineering. Consequently,
visualisations and insights must be interpreted in the context of this final submission.
(The presentation materials were a fair representation of project progress at the time.)

Submission contents
-------------------

I have not provided additional notebooks used to trial various lines of enquiry during this project.
However, the following submission captures the 'journey' nicely!

Conda environment
- ejackson_env.yml   ----- environment required to run notebooks

Data
- monthlytgvpunctuality.csv   ----- downloaded from SNCF open data
- interceptions_programmees_sur_ligne.csv   ----- downloaded from SNCF open data
- french_regions.geojson   ----- downloaded from data.gouv.fr
- speed_limit_shapefiles.csv   ----- downloaded from SNCF open data
- route_lengths_new.csv   ----- data collated by me using Internet search and SNCF network map
- network_map.pdf   ----- SNCF network map

Data arising from notebooks (i.e. if all notebooks are run in order, data files are generated)
EXAMPLE ONLY
- data_final.csv   ----- final dataset for modelling generated from Jupyter notebook 4 (for reference only)

Notebooks
- Edward_Jackson_IntelligentRail_Feature engineering_Notebook1   ----- Jupyter notebook 1 (maintenance data)
- Edward_Jackson_IntelligentRail_Feature engineering_Notebook2   ----- Jupyter notebook 2 (speed limit data)
- Edward_Jackson_IntelligentRail_Feature engineering_Notebook3   ----- Jupyter notebook 3 (collating lines, regions, speed restrictions)
- Edward_Jackson_IntelligentRail_EDA&cleaning_Notebook4   ----- Jupyter notebook 4 (EDA & cleaning)
- Edward_Jackson_IntelligentRail_Modeltraining_Notebook5   ----- Jupyter notebook 5 (Model training)
- Edward_Jackson_IntelligentRail_ModelEvaluation_Notebook6   ----- Jupyter notebook 6 (Model evaluation and insights)

White paper
- Edward_Jackson_IntelligentRail_Report.pdf