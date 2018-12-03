## Data Scavenger Hunt: Depression

1. Pick out your outcome - and find a buddy (10 min)
2. Quick Talk about EDA (5-10 min)
    a) Real world examples
    b) Why we do it
3. Introduce the Shiny Interface (10 minutes)
    a) Overview - How many patients in our dataset?
    b) Categorical (factor = category)
    c) Continuous
4. Quick Answer questions - Depression
    1. How many missing values are there for Depression?
    2. How many people in the dataset have the "most" number of Depressive Episodes?
    3. Do the `Race1` and `Race3` categories overlap? What is the relationship of `Race3` to `SurveyYr`?
    4. Is there something strange about `Age`?
    5. Is number of sleep hours associated with depression?
    6. Is marijuana use associated with depression?
    7. What about sleep trouble?
    8. How is sleep trouble and marijuana use related?
5. Quick Answer questions - Physical Activity (See app [https://minnier.shinyapps.io/nhanes_explore_physactive/](https://minnier.shinyapps.io/nhanes_explore_physactive/))
    1. How many missing values are there for PhysActive (yes/no physically active)?
    1. What are the characteristics of people who have missing responses for PhysActive?
    1. How does missingness and responses in PhysActive relate to responses and missingness in PhysActiveDays and PhysActiveDaysAtLeast3? How does the proportion of missingness in PhysActiveDaysAtLeast3 relate to PhysActive response? Is this what you would expect?
    1. Is there something strange about `Age`?
    1. Is number of sleep hours associated with physical activity?
    1. What about levels of education?
    1. What about BMI? Is the association of BMI with physical activity dependent on which measure of activity you use -- PhysActive (yes/no) or PhysActiveDaysAtLeast3?
6. Conclusions
    1. What are the strongest associations with your outcome of choice?
    2. Are any of the covariates associated with each other?
    3. Are the associations what you expected?
    4. Sampled structure of NHANES
