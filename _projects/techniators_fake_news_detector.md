---
layout:      project
title:       Techniators 💻🤖 Fake News Detector
date:        2023-03-06
image:
  path:       /assets/gif/fake_news_detector_demo.gif
  srcset:
    1920w:   /assets/gif/fake_news_detector_demo.gif
    960w:    /assets/gif/fake_news_detector_demo.gif
    480w:    /assets/gif/fake_news_detector_demo.gif
caption:     Judge's Award in Hack The Threat 23 Hackathon
description: >
  Judge's Award in Hack The Threat 23 Hackathon
hide_description: true
links:
  - title:   GitHub
    url:     https://github.com/UBC-MDS/Techniators
featured:    false
---

{:.center_element_square_radius}
![sticker](/assets/img/projects/techniators/techniators_sticker.png)

[Techniators 💻🤖](https://hackhpc.github.io/HacktheThreat23/teams/#Techniators).
{:.figcaption}

## Introduction

We are delighted to announce that our team has won the Judges Award and Best Team Goals Presentation in the
[Hack The Threat 23 Hackathon Competition](https://hackhpc.github.io/HacktheThreat23/)
organized by [Simon Fraser University](https://www.sfu.ca/big-data.html), [Texas Advanced Computing Center](https://www.tacc.utexas.edu/), [Amazon Web Services](https://aws.amazon.com/), and [HackHPC.org](http://hackhpc.org/). This is an incredible achievement that has been made possible by the collaboration and hard work of our team.

During  the Hack The Threat 23 Hackathon, our team was challenged to identify and solve data challenges and problems within the scope of cybersecurity, environmental, and social threats. We focused on social threats and developed a fake news detector that uses machine learning (ML) and natural language processing (NLP) to help restore trust in the media.

Our solution leverages digital technologies to analyze news articles and provide customers with a potential truthfulness label, sentiment analysis, word cloud, and distribution plot. These insights can help users evaluate the accuracy of a news article.

If you're interested in learning more about our fake news detector or supporting our mission to promote trust in public media, we invite you to explore this webpage and contact us. Our team is always open to new opportunities and partnerships that can help us further improve our application.

## Background

Fake news is a growing problem that has serious consequences for individuals and society as a whole.
With the rise of social media and the internet, it has become easier than ever for false information to spread rapidly and widely. This misinformation can be used to manipulate people's perceptions of reality, especially in the world of politics, where it can be used to sway public opinion, promote advertising for or against a specific candidate or party, or perpetuate conspiracy theories that erode trust in institutions.

In 2016, a [false story about a Washington D.C. pizza restaurant](https://www.bbc.com/news/blogs-trending-38156985) being involved in a child sex trafficking ring went viral on social media. The story was completely fabricated but led to a man traveling to the restaurant with a gun. Fortunately, no one was harmed, but this incident demonstrates the dangerous consequences of fake news, including harm to innocent people and businesses, financial losses, and even violence.

## Solution

Based on the impact of fake news on social threats, it is critical to develop solutions to combat fake news and promote trust in the media. This is where our fake news detector comes in, using machine learning to analyze news articles and provide users with insights into the potential truthfulness of the information. By building trust in media and promoting accurate information, we hope to contribute to a healthier and more informed society.

> Our Goals: Create an app that makes fake news detection easier, more streamlined and consistent.
{:.lead}

![one_page](/assets/img/projects/techniators/one_page.png)

[Slide Deck URL](https://github.com/UBC-MDS/Techniators/blob/main/Techniators_hackthethreat23_presentation.pdf)

## Technologies used

| Functionalities | Technologies & Tools |
|:-----------------:|:-----------:|
| Machine Learning & Data Processing | Python, Scikit-learn, Natural Language Toolkit (NLTK), AWS Sagemaker |
| Web Development | Streamlit |
| Web Deployment | AWS EC2, AWS S3 |

![Architecture](/assets/img/projects/techniators/fake_news_detector_architecture.png)

Our application is deployed on the Amazon Elastic Compute Cloud (EC2) server, while our machine learning model is stored in the Amazon Simple Storage Service (S3). We leverage Amazon SageMaker for model training and data processing, which ensures a highly secure and scalable application. By utilizing these cloud-based services, we are able to provide a reliable and robust solution that is capable of handling a large volume of data with high accuracy and efficiency. We are confident that our solution will meet the needs of our users and provide them with a reliable tool for detecting fake news and promoting trust in media.

## Demo & Screenshots

![demo11](/assets/img/projects/techniators/demo_1_1.png)
Real News Example
{:.figcaption}

Once a news article is inputted into our application, it undergoes a preprocessing stage where we perform feature engineering to create three additional features: special character count, uppercase letter count, and sentiment score. This process helps to improve the accuracy of our machine learning model by providing additional relevant information about the input news article.

After the preprocessing stage, the data is then fed into our machine learning model for prediction. Our model leverages advanced algorithms to analyze the input data and make a determination on whether the news article is real or fake.

![demo12](/assets/img/projects/techniators/demo_1_2.png)
Word Cloud Plot
{:.figcaption}

As part of our solution, we provide clients with valuable insights into the content of their input news article. This includes a word cloud that highlights the most frequent words in the article, with larger font sizes indicating higher frequency. In addition, we generate a word frequency plot that displays basic statistics on the keywords found in the article, such as the frequency distribution.

![demo13](/assets/img/projects/techniators/demo_1_3.png)
Word Distribution Plot
{:.figcaption}

These visualizations are designed to provide clients with a deeper understanding of the content of their news article, allowing them to gain additional insights into its potential truthfulness.

## Accomplishment

### Awards

🏆 Best Team Goals Presentation

🏆 Judges Award

### Project Milestones

1. Built an end-to-end machine learning pipeline

2. Trained a machine learning model to predict news truthfulness

3. Intergrated the ML model in Streamlit application

4. Deployed the trained model to AWS cloud

## Next Steps

- Train AI generated dataset (OpenAI API data collection)

- ML model comparsion

- in-depth hyperparameter tuning

## Conclusion

In conclusion, our team is thrilled to have won the Best Team Goals Presentation and the Judges Award in the Hackathon. Our participation in the Hack The Threat 23 Hackathon provided us with an opportunity to tackle a pressing issue in our society - fake news. By developing a fake news detector using machine learning, we hope to contribute to rebuilding trust in media and promoting accurate information.

Our solution offers several benefits, including the ability to detect potentially false information quickly and easily, as well as providing users with sentiment scores, a word cloud, and a distribution plot for deeper insights. We believe that our solution has the potential to be useful for individuals, media organizations, and policymakers in combatting the spread of fake news, or even AI generated news article.

Overall, we are proud of our team's effort and the solution we developed during the hackathon. We look forward to further developing and enhancing our application, and we are open to new opportunities and partnerships that can help us achieve our mission of combating fake news and promoting trust in media.

### Special Credits 🙌

Great thanks to my delegated and supportive teammates [Lisa Sequeira](https://ca.linkedin.com/in/lisasequeira) & [Sarah Abdelazim](https://www.linkedin.com/in/sarah-abdelazim-09709bb2).

Appreciate all the support and advice from the organizer ([Jeaime Powell](https://www.linkedin.com/in/jeaimehp/?original_referer=https%3A%2F%2Fjeaimehp.github.io%2F)) & mentors ([Esthela Gallardo](https://www.linkedin.com/in/esthela-gallardo-a60672108)).
