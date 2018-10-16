# YT8M
(Machine) Learning from YouTube8M dataset 
This repository hosts the Jupyter notebooks used in our analysis of YouTube8M dataset.
YouTube-8M is one of Google’s latest contributions to research in Machine Learning and Artificial Intelligence.

Starting in 2017, it is a dataset with 8 million video IDs labeled with more than 4000 classes. It was released as raw data for a Kaggle competition. This year 2018, competing data scientist have been summoned once again and the dataset contains 6.1 million videos and a few classes less (only 3862). Videos are selected according to some criteria such as being public and having at least 1000 views, lasting between 120 and 500 seconds and having association with at least one entity from the target vocabulary (one of the 3862 words mentioned above).

The purpose of the challenge is to forecast the class or classes to which a video will be associated with by inspecting its internal frame structure and associated labels. Some tools are even provided (here) by Google with the goal of facilitating the task and raise the level of the results.

Last September 9th, 2018, a workshop versing on the different experiences from competitors and organizers of the challenge took place in Munich: The 2nd Workshop on YouTube-8M Large-Scale Video Understanding. Although this year Epic Labs was too busy to attend (we were in IBC!!!), we still wanted to make some contribution to the community and help spread the word about this awesome dataset.

With the launch of Epìc Labs’ LightFlow and its Smart Encoding abilities we got inspired to make some exploration of the data. For a while already, we had the intuition that different kinds of videos have optimal codifications, and this depends to some extent on their content. YT8M’s labeled videos gives us the perfect chance to scientifically prove our guess!

* Crawling YouTube videos
* Analyzing labels and bitrate ladders
* Forecasting ladders from labels
