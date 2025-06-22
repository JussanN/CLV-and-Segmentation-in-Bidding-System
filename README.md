# Integrating 6-month Customer lifetime value prediction and Segmentation into Value-based bidding
This is the final project for the Advanced Topics in Data Science course (CS 1090B), part of the Master’s Program in Data Science at Harvard University. The project focuses on integrating 6-month customer lifetime prediction and segmentation into value-based system.

Our goal is to build a scalable and interpretable machine learning framework that integrates customer segmentation, customer value prediction, and a value-based bidding system for digital advertising. By clustering customers using behavioral and transactional data, we identify meaningful segments that inform a predictive model of customer lifetime value (CLV). This predicted value serves as the foundation of a value-based bidding strategy, where advertisers allocate budget based on each customer’s estimated future worth. The system simulates real-time auction dynamics to evaluate performance in terms of Return on Ad Spend (ROAS) and budget utilization, ultimately enabling more personalized marketing and smarter ad spend decisions.

We will use K-means for segmentation and various machine learning models such as Multilinear Regression, Random Forest and Neural Netorks to predict 6-month customer lifetime value (CLV). To evaluate the models, we'll use cross-validation R2, a metric that shows how well the model's predictions match the actual 6-month CLV. Finally, we'll leverage the CLV to build and simulate a value-based bidding system.

For a detailed explanation, please refer to the [Project video](https://harvard.zoom.us/rec/play/SXLv7WtscupvOoCPk7_arX7qz77w4HxLlWGyMrFKZmPorx3y-wwON7lfZuM1HdevTVvryR-U8cLiopRp.GVQN43Efm1GjuAYo?eagerLoadZvaPages=&accessLevel=meeting&canPlayFromShare=true&from=share_recording_detail&startTime=1746641998000&componentName=rec-play&originRequestUrl=https%3A%2F%2Fharvard.zoom.us%2Frec%2Fshare%2FdG1jC0tyYR6Hp0fH9fdjycLaWZNKrMdT1sbrkSA88fG2skNjOcIit7Opl_SwwHYt.aWh9ylShKByP-Shs%3FstartTime%3D1746641998000) and the Python notebook included in this repository.

The data source used in this project is a retail dataset and it can be found on [Kaggle]([https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma](https://www.kaggle.com/datasets/sahilprajapati143/retail-analysis-large-dataset))

Done by Jussan Da Silva Bahia Nascimento, Selina Qian, Mengdi Chai, Zhongling Tang, Daisy Lyu

