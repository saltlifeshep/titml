
# Product Requirements Document: "Tell It To Me Like" (TITML)

**Author:** Gemini
**Date:** July 7, 2025
**Version:** 1.0

---

## 1. Executive Summary

"Tell It To Me Like" (TITML) is an AI-powered educational platform designed to simplify complex topics for a broad audience. Users can describe any task, subject, or area of interest through an intuitive chat interface. The system then leverages a powerful automation engine (n8n) to generate a comprehensive suite of learning artifacts. These artifacts are designed to cater to different learning styles and include detailed PDF documents, short-form videos, diagrams, explainer videos, and more. 

TITML aims to make learning accessible and engaging. While initial content is provided for free to demonstrate value, full access to the rich media library is available via a flexible monetization model, including pay-per-artifact options and all-access memberships. The platform will build a community and drive user acquisition through automated content distribution to major social media channels and an integrated affiliate program.

## 2. Goals and Objectives

*   **Primary Goal:** To become the go-to platform for users seeking simplified, multi-format explanations of any topic.
*   **Business Objective:** Achieve profitability within 18 months through a combination of individual content sales and recurring membership revenue.
*   **User Objective:** Provide users with a fast, easy, and effective way to understand new subjects, regardless of their preferred learning style.
*   **Marketing Objective:** Build a strong brand presence and a self-sustaining content ecosystem through automated social media outreach and a robust affiliate network.

## 3. Target Audience

*   **Students:** High school, college, and university students looking for supplementary material to aid their studies.
*   **Lifelong Learners:** Adults with a curiosity to learn new skills or understand complex current events, hobbies, or professional topics.
*   **Professionals:** Individuals needing to quickly get up to speed on new technologies, methodologies, or industry trends.
*   **Content Creators & Educators:** Teachers, YouTubers, and bloggers looking for well-researched and structured source material.

## 4. Core Features & User Stories

### Epic: User Interaction & Content Request

*   **As a new user,** I want to visit the homepage and immediately understand what the service does so I can make my first request.
*   **As a user,** I want to interact with an AI chat assistant to describe the topic I want to learn about.
*   **As a user,** I want the AI to ask clarifying questions to better understand my request and tailor the content to my needs (e.g., "Explain it to me like I'm a 10-year-old" or "Explain it for a graduate-level course").
*   **As a user,** I want to receive an email notification when my requested content artifacts are ready.

### Epic: Artifact Generation

*   **As the system,** I will use n8n workflows to manage the entire artifact generation pipeline.
*   **As the system,** I will generate a core PDF document that is well-structured, includes detailed explanations, and provides attribution links for all sources used.
*   **As the system,** I will generate a series of short-form videos (under 60 seconds) summarizing key points, suitable for platforms like TikTok, Instagram Reels, and YouTube Shorts.
*   **As the system,** I will create clear, concise diagrams, pictures, and infographics to visually explain complex relationships or processes.
*   **As the system,** I will produce a 3-5 minute explainer video that walks through the topic in a digestible format.
*   **As the system,** I will generate an audio-only version of the explainer video to be used for a podcast.
*   **As the system,** I will create interactive quizzes or flashcards to help users test their knowledge.

### Epic: Content Library & Monetization

*   **As a user,** I want to receive the initial PDF artifact for free to evaluate the quality of the content.
*   **As a user,** I want to see a preview of all the generated artifacts (e.g., watermarked images, video thumbnails, quiz descriptions) before deciding to purchase.
*   **As a user,** I want the option to purchase a single artifact for a small, one-time payment.
*   **As a user,** I want the option to purchase a monthly or annual membership for unlimited access to all current and future content.
*   **As a user,** I want to be able to search the entire library of previously generated content using keywords, topics, or tags.
*   **As a user,** I want my personal library of purchased/unlocked content to be easily accessible from my account dashboard.

### Epic: Content Distribution & Marketing

*   **As the system,** I will automatically publish generated content to the relevant social media platforms based on a schedule.
    *   **Podcasts:** Publish audio explainers.
    *   **YouTube:** Publish long-form and short-form explainer videos.
    *   **Facebook (Page/Group):** Publish links to new topics, videos, and engage with the community.
    *   **X/Instagram/TikTok:** Publish short-form videos, infographics, and key takeaways.
*   **As an admin,** I want a dashboard where I can view, manage, and set the content distribution schedule for all social media channels.
*   **As an admin,** I want to be able to manually approve or reject content before it is published.

### Epic: Affiliate Program

*   **As a user,** I want to be able to sign up for an affiliate program to earn commissions.
*   **As an affiliate,** I want a unique referral link and a dashboard to track my clicks, referrals, and earnings.
*   **As an affiliate,** I want to receive a commission for every new member or individual sale that comes from my referral link.
*   **As the system,** I will provide affiliates with marketing materials (e.g., banners, pre-written posts) to help them promote TITML.

## 5. Technical Considerations

*   **Backend:** A scalable serverless architecture is recommended to handle fluctuating demand.
*   **AI/LLM:** Integration with one or more leading Large Language Models for chat interaction and content generation.
*   **Automation:** n8n will serve as the central nervous system for the content generation and distribution workflows.
*   **Frontend:** A modern JavaScript framework (e.g., React, Vue, Svelte) for a responsive and interactive user experience.
*   **Database:** A combination of a document database (for content) and a relational database (for user/transaction data) is recommended.
*   **Payments:** Integration with a reputable payment gateway like Stripe or PayPal to handle one-time payments and recurring subscriptions.

## 6. Success Metrics

*   **User Engagement:** Daily/Monthly Active Users (DAU/MAU), average session duration, number of content requests per user.
*   **Conversion Rate:** Percentage of free users who convert to paying customers (either single purchase or membership).
*   **Revenue:** Monthly Recurring Revenue (MRR), Average Revenue Per User (ARPU), affiliate-driven revenue.
*   **Content Library Growth:** Number of new topics and artifacts generated per week.
*   **Marketing Reach:** Social media follower growth, engagement rates, website traffic from social channels.
*   **Customer Satisfaction:** Net Promoter Score (NPS), user reviews, and feedback.

## 7. Future Considerations (Roadmap)

*   **Team/Enterprise Plans:** Offer multi-seat licenses for businesses or educational institutions.
*   **Advanced Content Customization:** Allow users to "remix" or customize generated artifacts.
*   **Live Sessions:** Host live Q&A sessions with experts on popular topics.
*   **Community Features:** Implement forums or discussion boards for users to interact and learn from each other.
*   **Localization:** Translate the platform and content into multiple languages to reach a global audience.
