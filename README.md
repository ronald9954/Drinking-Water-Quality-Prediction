# Drinking-Water-Quality-Prediction
Drinking Water Quality Prediction for kaggle competition -  https://www.kaggle.com/competitions/drinking-water-quality/submissions


Estonian government AI testbed competition invites everyone with expertise in data science and analysis to join an experimental testbed to find solutions to real-world problems using open data. We look forward to welcoming a range of specialists to come and work with us and become part of one of the most technologically advanced government projects in Europe contributing to the development of AI Gov-stack that benefits people across the globe. The AI testbed competition encompasses various works in the fields of data science, machine learning, and language technology, that open a way to contribute and become a part of developing the open-source AI Gov-stack.
Pick a competition you are interested in and help us to build the coolEST and brightEST digital state!

Background
Despite the fact that most of our planet is covered with water, not more than 3 % of this amount is fresh. To make sure that the water is safe to drink the Estonian Health Board has been measuring its quality in more than thousand water stations across the country thereby making sure that every citizen will get the freshest water right from their tap.
To bring water quality measurement to the next level and automate working process of Estonian water inspectors, we would like to invent predictive water quality model that would enable us to prioritize the tests or react proactively to the deterioration of the water conditions. Therefore, enhancing the role of scientific and data-driven approach on a governmental level.

Goal
The goal of this competition is to create a model that predicts the water quality in Estonian water stations based on the government’s open data of the previous measurements.


-- sample_submission.csv - Sample submission from the organizer<br />
-- train.csv - Training data from the organizer<br />
-- test.csv - Test data from the organizer<br />
-- Drinking Water Problem- Accuracy version - 2022_10_04 _1710.ipynb - The notebook with 0.87368 Private score and 0.89361 Private score<br />
-- Drinking Water Problem- Sensitive to non-compliance version - 2022_10_04 _1745.ipynb - The notebook with 0.83157 Private score and 0.81914 Private score<br />

Though Drinking Water Problem- Accuracy version has a higher accuracy, many of the "correct guesses" are guessing the compliance case. It fails to find out non-compliance cases efficiently.
Drinking Water Problem- Sensitive to non-compliance version is more effective in finding out non-compliance cases.

