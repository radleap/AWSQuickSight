# AWS QuickSight 

- See **WorkshopData** for initial dataset, and **WorkshopOutputs** for, um, outputs :)

## Workshop Sections
- Author Workshop
    - Pricing (Authors, Readers, SPICE storage, FAQs, Alerts, Anomoly Detection Pricing)
        - https://aws.amazon.com/quicksight/pricing/
    - Build Dashboard
        - Basic dashboarding. Auto scaling, serverless, integreted in AWS, API support, ML Pay-as-you-go
        - https://catalog.us-east-1.prod.workshops.aws/workshops/cd8ebba2-2ef8-431a-8f72-ca7f6761713d/en-US/author-workshop/1-build-your-first-dashboard
    - Enhancing Dashboard 
        - Sheets, themes, field formats, visual formatting, dashboard layout settings
        - https://catalog.us-east-1.prod.workshops.aws/workshops/cd8ebba2-2ef8-431a-8f72-ca7f6761713d/en-US/author-workshop/2-enhance-your-dashboard
    - Adding Interactivity
        - Cascading filters, filter actions, URL actions, navigation actions, alerts (threshold email)
        - https://catalog.us-east-1.prod.workshops.aws/workshops/cd8ebba2-2ef8-431a-8f72-ca7f6761713d/en-US/author-workshop/3-add-interactivity
    - Datasets
        -Query modes, Dynamix Query Generation, Custom SQL, field Folders, Dataset as source, Versioning
        - https://catalog.us-east-1.prod.workshops.aws/workshops/cd8ebba2-2ef8-431a-8f72-ca7f6761713d/en-US/author-workshop/4-datasets
    - Calculations
        - Calculating in dataset vs analysis layer
        - https://catalog.us-east-1.prod.workshops.aws/workshops/cd8ebba2-2ef8-431a-8f72-ca7f6761713d/en-US/author-workshop/5-calculations
    - Data Security
        - Row Level Security (RLS); Column Level Security (CLS)
        - RLS: 
            - There are lot of scenarios wherein you want to share a standard dashboard with a wide audience but want them to see only data that is relevant to each of them. For example, you might want to let each sales rep see his/her sales data, the state manager to see data for all reps that roll up to him/her and country manager to see data for whole country. This can be easily accomplished by building a single dashboard on top of dataset that is secured with RLS rule
            - QuickSight allows you to bring in data rules that specify the access levels at user and group level.
        - CLS:
            - You might have a bunch of fields with sensitive information (like SSN, Salary, Address etc) in your dataset that you want only users with elevated privileges to see. You can set this up by applying CLS on the dataset. Users who have been granted access to all fields will be able to see all visuals in the dashboards/analyses that are shared with them.
        - https://catalog.us-east-1.prod.workshops.aws/workshops/cd8ebba2-2ef8-431a-8f72-ca7f6761713d/en-US/author-workshop/6-data-security
        - https://docs.aws.amazon.com/quicksight/latest/user/namespaces.html
    - Machine Learning
        - Narratives, Forecasting, Anomaly Detection and Contribution Analysis (pretty cool)
            - Note that anomoly detection does not work with datasets that have Row/column level security. 
        - https://catalog.us-east-1.prod.workshops.aws/workshops/cd8ebba2-2ef8-431a-8f72-ca7f6761713d/en-US/author-workshop/7-machine-learning