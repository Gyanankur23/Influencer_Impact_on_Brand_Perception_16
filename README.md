# Influencer_Impact_on_Brand_Perception_16 CaseCraft Analytics Project Sprint Project 16

## 🌟 Overview  
This project maps influencer impact on brand perception using synthetic social media data. It blends Flair NLP sentiment tagging, Sankey diagrams, treemaps, and regression modeling to decode how influencer tone and engagement shape brand reputation.

## 🎯 Objective  
To analyze influencer-brand sentiment flows, visualize engagement clusters, and predict brand perception scores from influencer mix.

## 📱 Dataset & Features  
- Posts: 500 synthetic influencer-brand interactions  
- Influencers: @stylequeen, @techguru, @fitlife, @foodie, @traveljunkie  
- Brands: Zara, Apple, Nike, Starbucks, Airbnb  
- Features:  
  - Post text  
  - Likes, comments → engagement  
  - Sentiment (Flair: POSITIVE/NEGATIVE)  
- Derived: sentiment score (±1), perception score = sentiment × engagement

## 📊 Visual Explorations  
- **Sankey Diagram**: Influencer → Brand → Sentiment flow  
- **Treemap**: Engagement clusters by influencer  
- **Heatmap**: Brand frequency per influencer  
- **Histogram**: Likes distribution

## 🤖 Sentiment & Modeling  
- Sentiment tagging via Flair NLP  
- Perception score = sentiment polarity × engagement  
- Model: Linear Regression  
- Input: one-hot encoded influencer and brand  
- Output: brand perception score  
- Performance: R² score confirms predictive strength

## 🧠 Key Insights  
1. **Influencer Tone Matters**: Positive posts with high engagement drive perception  
2. **Brand-Specific Sentiment**: Nike and Apple receive more positive sentiment  
3. **Engagement Clusters**: @fitlife and @foodie show highest audience interaction  
4. **Sankey Utility**: Reveals sentiment flow across influencer-brand pairs  
5. **Model Utility**: Predicts perception score from influencer-brand mix

## ✅ Final Conclusion  
Influencer sentiment and engagement are powerful predictors of brand perception. This framework enables strategic influencer selection, sentiment monitoring, and perception modeling—ideal for marketing teams optimizing brand partnerships.