# netflix_data-pipeline
epic_1:
Using Azure resources and services



epic_3:
Using Workflow ingest the data to silver layer


Using "dbutils.jobs" we are passing the output of one task to another/ next activity.
dbutils.jobs.taskValues.set(key=')


A static value can be passed directly between tasks but multiple values/ files/array values need tp be looped and processed within looped activity.

epic_4:

"4_silver transform data" where data cleaning and transformation occured. Storing it after transformation to silver layer container.

epic_5:
5_Lookup notebook2 to shedule the workflow to run on user defined  weekday
Run my 'netflix_title' file on weekday "5" using workflow

epic_6:



