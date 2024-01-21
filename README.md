# Treehacks-2023---Sustainability-project
We leverage the power of **Machine Learning** as precision agriculture in **intercropping farming** to tackle climate change and promote sustainability in vulnerable regions around the world.
## Inspiration :book:
In the book "Biomimicry: Innovation Inspired By Nature," **polyculture** treasures the diversity and collaboration of plants in which they rely on each other instead of pesticides and fertilizers. After conducting much research, we saw crop diversification via intercropping (growing more than one crop on the same land) or crop rotation (growing multiple crops at different times) is one of the solutions to increase the resilience and sustainability of farming. As a result, to help developing agricultural countries like Vietnam overcome the rising climate crisis, we believe that the key is to create biodiverse agriculture that mimics nature well.

## What it does :computer:
CROPANION uses **Tree classification (Random Forest)** as a supervised Machine Learning to predict which crop is suitable based on different features of environmental conditions, namely Nitrogen (N), Potassium (P), Phosphorous (K), temperature, humidity, pH, and rainfall. The farmers and environmental/agriculture organizations enter their input about these metrics. The ML model will generate suggestion for the **best compatible crops** for the input condition and a crop manual to ensure they can grow the new type of crop. They can also ask questions in the **chatbox** on the website.

## How we built it :rocket:
We use the **dataset "crop_recommendation.tab"** (Singh, Raul, 2023) from Havard Dataverse to train the model, and our programming language is **Python**. We base the ML training model on a **classification tree with binary recursive partitioning** to make predictions. Simply put, we input the known labels with features (for example, rice-pH, N, P, K, etc.) and code a training sample + a validation one. We incorporated **OpenAI API and SERP API** for the feature of crop Manual and conversational question-answer. For the final presentation & prototype, we used **WebFlow** to create a landing page for the product.

## Challenges and what we are proud of :clap:
We are aware that the decision to introduce new crops or plant them with other crops depends on more variables than only environmental conditions. Farmers need to consider pest and disease resistance, and other **socio-economic variables** such as market demand, and labor requirements of the crops as well. Thus, we accepted the challenge of expanding the original model using a **Genetic algorithm as an unsupervised ML** to develop such a multi-criteria decision analysis. 

