# Treehacks-2023---Sustainability-project
We leverage the power of Machine Learning as precision agriculture in intercropping farming to tackle climate change and promote sustainability in vulnerable regions around the world.
**Inspiration**
In the book "Biomimicry: Innovation Inspired By Nature," polyculture treasures the diversity and collaboration of plants in which they rely on each other instead of pesticides and fertilizers. In contrast, monoculture (growing only one type of crop throughout one or many years) is mentioned as a poor farming practice because it is highly vulnerable to climate change. In case of extreme weather, the livelihoods and staples of the local people are threatened as no alternatives exist.

After conducting much research, we saw crop diversification via intercropping (growing more than one crop on the same land) or crop rotation (growing multiple crops at different times) is one of the solutions to increase the resilience and sustainability of farming. Also, many African and South(east) Asian countries are agriculture-based economies, but they have been feeling the impacts of climate change for years. As a result, to help these disadvantaged communities overcome this crisis, we believe that the key is to create biodiverse agriculture that mimics nature well.

To introduce a new crop, we need to consider many variables, one of which is the environmental compatibility of the crop and the area. We applied supervised Machine Learning and OpenAI API to build this product.

**What it does**
CROPANIAN uses tree classification as a supervised Machine Learning to predict which crop is suitable based on different features of environmental conditions, namely Nitrogen (N), Potassium (P), Phosphorous (K), temperature, humidity, pH, and rainfall. The farmers and environmental/agriculture organizations enter their input about these metrics. The ML model will generate the answer about whether a crop can be grown in a specific area with its profile and will provide the best suitable crop and crop manual to ensure they can grow the new type of crop. They can also ask questions in the chatbox on the website.

**How we built it**
We use the dataset "crop_recommendation.tab" (Singh, Raul, 2023) from Havard Dataverse to train the model, and our programming language is Python. We worked on Google Colab and utilized ChatGPT to find information about crop compatibility, intercropping challenges, etc. We base the ML training model on a classification tree with binary recursive partitioning to make predictions. Simply put, we input the known labels with features (for example, rice-pH, N, P, K, etc.) and code a training sample + a validation one. We incorporated OpenAI API and SERP API for the feature of crop Manual and conversational question-answer. For the final presentation & prototype, we used WebFlow to create a landing page for the product.

**Challenges we ran into**
We are aware that the decision to introduce a new crop on land or plant them with other plants depends on more variables than only environmental conditions. Farmers need to consider the pest and disease resistance, market demand, and labor requirements of the crops as well. Thus, we intended to build another model using a genetic algorithm as an unsupervised ML to develop such a multi-criteria decision analysis. However, the model is too complex for us, and we made it to the conceptual understanding of the model except for the programming part.

**Accomplishments that we're proud of**
We finally completed the project! We were no longer stuck in the ideation stage, which we struggled a lot in our first hackathon but eventually created a satisfactory prototype. We are also proud that we decided to challenge ourselves despite the relatively new topic of farming and sustainability and made it to the end despite some disagreements.

**What we learned**
A lot! We have learned how to leverage the benefits of API so that we do not have to write code from scratch. We strengthened our understanding of Machine Learning. We could play with different learning models and find the most effective for our use. Attending multiple workshops was inspirational for using various tools and learning new languages.

**What's next for CROPANION**
We want to build a more comprehensive predictive model using genetic algorithms that include more crop compatibility criteria to help farmers make more informed decisions. It is a complex model with different measurements and a combination of both environmental and socio-economic variables. In addition, we want to integrate all these models into an easy-to-understand UI with local languages for Asian and African farmers.
