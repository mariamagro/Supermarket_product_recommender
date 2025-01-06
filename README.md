# Spanish Supermarkets Products analysis and recommender system

This project is a complete Spanish supermarket analysis that includes the following steps:
- Scrap 11 different Spanish webpages supermarkets to obatin the products they offer and some characteristics of them.
- Use the OpenFood API to retrieve information about categories, labels and Nutri-score of the previous products.
- Huge preprocessing to normalize all the datasets to create a big one.
- Analyze the dataset using clustering.
- Generate a recommender system based on the product you are searchig for.
- Make graph analysis to see communities and other interesting information.
- Generate a interactive Gradio dashboard that includes all previous steps in one, where the user can search for products based on different filters and then get recommendations based on them. Also, they can explore some information of the differnt supermarkets.

This project has been made in collaboration with Sara Piñas, Marina Gómez Rey and Eduardo González.

## Files

- Final_code -> complete implementation including scrappings, API, preprocessing, clustering, graph analysis, recommender system and final interactive Gradio Dashboard.
- Final_complete_dataset -> dataset used so that the Gradio can run.
- Original_scrapped_datasets -> 11 original datasets that come from the scrapping of the codes present in the notebook.
