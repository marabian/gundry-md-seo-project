# Gundry MD SEO Project

## About

This project explores the potential use-cases of Generative AI, particularly GPT models, in conducting SEO research for Dr. Gundry's product website. It delves into preliminary aspects such as keyword grouping, sentiment analysis, relevance checking, and competitor theme analysis. The goal is to investigate how Generative AI can contribute to refining SEO strategies for Gundry MD, presenting a foundational exploration.

## Features

1. **Keyword Analysis**
    * Extracts top 100 keywords associated with [Gundry MD Website](https://gundrymd.com/) using [DataForSEO API](https://dataforseo.com/).
    * Uses [OpenAI's GPT API](https://openai.com/blog/openai-api) to group these extracted keywords based on thematic similarity, relevance, or any other criteria the AI model deems appropriate.

2. **SERP Analysis**
    * Uses *DataForSEO* API to obtain SERP results for select keywords obtained in step 1.
    * Perform sentiment analysis on SERP results.
    * Check relevance of SERP results to Gunder MD.
    * Identify industry competitors in SERP results.
    * Analyze the themes of competitors SERP results.

3. **More Ideas using Generative AI**
    * Content Creation
    * Analyze YouTube Videos
    * Analyze Website Carousels
    * Assist with A/B Testing

## Generative AI use-cases

I've identified nine applications of generative AI for SEO purposes. The notebook already incorporates the first four of these use-cases (refer to "Generative AI Use-case 1" for examples). Additionally, I delve into the concepts behind the remaining five use-cases, providing insights and potential strategies for leveraging generative AI to further improve SEO efforts.


1. Generative AI Use-case 1: **Group keywords**

* Grouping keywords is a common and effective practice in SEO. It helps in organizing your SEO strategy around thematic clusters or topics, improving content relevance, and enhancing user experience on your website. This approach aligns with search engines' focus on topic relevance and intent matching, potentially boosting your site's rankings for related searches. Grouping keywords can also streamline content creation and optimization efforts, making it easier to target multiple related keywords within a single piece of content or across a series of interconnected pages

* In the notebook, I used *OpenAI's* **gpt-3.5-turbo** modelto group these 100 keywords. I asked the model to identify natural clusters or groupings based on thematic similarity, relevance, or any other criteria it deems appropriate.


2. Generative AI Use-case 2: Sentiment Analysis and relevance

3. Generative AI Use-case 3: Analyzing Themes for SEO competitors

4. Generative AI Use-case 4: Extract Industry Competitors from SERPs

5. Generative AI Use-case 5: Analyzing Microsites for Competitor analysis

6. Generative AI Use-case 6: Content Creation and Optimization¶

7. Generative AI Use-case 7: Analyze Youtube Videos

8. Generative AI Use-case 8: Analyze Website Carousel

9. Generative AI Use-case 9: Assist in A/B Testing
