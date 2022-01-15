# App-Tracker-Precaution

Done in nwHacks Hackathon 2022.

Collaborators: Danial Khan, Sully Najm, Payas Hasteer, Abhi Sharma

Description of Platform:

- Designing an application that allows users to track locations prone to communicable diseases.
- It tells you what precaution to take based on the disease.
- Supposing a user reports that they have 'x' disease in an area, other users can check what precautions they can take at certain locations.

Variables used in Data Analysis:

- radius from person
- Number days it has been since the person has had it
- severity of the disease (high medium or low when user fills it out)
- Number hospitalizations
- each disease has an r value --> the rate at which it spreads (with preloaded data)

Technologies used:
- Google maps API
- scikit-learn
- seaborn
- pandas
- matplotlib

General stages for our project:
1. Connecting the google api with the backend
2. Data Preprocessing, applying ML techniques to analyse the data
3. Use front-end to retrieve all data with visualisations
