---
title: "Tracking Generative AI Discourse: A Temporal and Spatial Analysis of Twitter Data"
toc: true
page-layout: article
---

**Abstract:** This fast-paced integration of digital technologies into society has been a growing trend within the past decade, with each new device, program, or application beating the next to 100 million monthly users faster than the last. A portion of this rapid adoption can be attributed to the extensive use of social media platforms like Instagram, TikTok, Reddit, and Twitter (now X), allowing early adopters and stakeholders to share information about these technologies with potential users, and in turn allowing these new adopters to spread information to their networks at scale. Despite their clear impact, it is difficult to say whether the effects of Generative AI over this period – and in turn the discussions about their implications by media figures and influencers – are associated with more positive or negative sentiment, especially around certain salient topics. Understanding the nuances of such discourse is vital for forecasting the future use and the development of Generative AI. With this in mind, the study of discourse around technologies on social media serves an important role in understanding who is using this technology, how it is being used, and what trends may be emerging within the space.

## Status
- Presented at Association for Education in Journalism and Mass Communication (2025) annual conference -- Communication Technology Division Division

## Summary
- We can see from our keyword analysis that discussions about these topics are growing and are dominated by three main keywords: “GenAI,” “LLM,” and “AGI.” We expect this trend to continue as these technologies are further integrated into our everyday lives.
- From our geographic analyses, we find, unsurprisingly, that states with major metropolitan areas are the ones that tweet the most about these topics. Combining sentiment and geographic data, we find that coastal states (the exception being IL) seem to be more positive in sentiment compared to midwestern or agriculturally dominant states, which is unsurprising given the connections between these coastal areas and high-tech like GenAI/LLMs.
- From the network analysis, we observe that discourse surrounding GenAI within communities tends to be broad and multifaceted, focusing on arts, technical methods, trends, and advancements within the field.
- While our multilevel analyses that deal with sentiment over time are not very granular – and overall sentiment is still more positive than negative, even in 24/25 (albeit very close; 0.504) – the trends we observe suggest that there may have been a honeymoon period where the promises of GenAI/LLMs from 2022 have not been realized, causing individuals to be disillusioned with the implementation of these technologies throughout our society.


## Methods / Data
- Data collection was done using Synthesio - a third-party platform for social media data. The collected corpus of tweets consists of a 10% decahose sample of all tweets, filtered using the keywords from the keyword list over a 3-year period from Feb 2022 to Feb 2025. Features include the user ID, date and time of publication, publisher username, tweet content, and a sentiment score.
- For data cleaning, deleted and protected tweets were removed to eliminate inaccessible content. Next, a manual scan was conducted to identify and filter out tweets associated with bot activity by examining common keywords and patterns indicative of automated or spam accounts. The dataset was filtered to include only English-language tweets originating from the US, allowing for a more relevant analysis of domestic discourse, containing 962,314 tweets and 260,617 unique users.
- We fine-tuned a BERTweet model – a large-scale language model specifically designed for English tweets – for binary classification of relevant tweets and sentiment classification. Applying the relevance and sentiment classifiers to the full corpus yielded 700,279 tweets with 215,921 unique users.

## Outputs
- Working Paper: [download](https://drive.google.com/file/d/1equYDB0AJN4zO6cxsnvoiqM4ARJbSrTo/view?usp=drive_link)
- Slides: [link](https://docs.google.com/presentation/d/1tSSEU8c18qnLLqQhztm38b7gfCSHt1Rv/edit?usp=drive_link&ouid=113571876130760026527&rtpof=true&sd=true)