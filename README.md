# Presentation at the COMPTEXT 2024 in Amsterdam
Saturday, 4th of May, 2024 (Panel: Politics in the Digital Age)

Title: Effects of Source Trustworthiness on Online Discussions 

Extended Abstract:
Research shows that misinformation elicits strong negative sentiments, thereby boosting its traction and engagement on social media. However, data collection methods often sample subsets of news, such as fact-checked stories, thereby misrepresenting the broader spectrum of news shared on social media platforms. In addition, existing studies frequently fail to distinguish emotions within news from reactions to the news, a crucial distinction for understanding their role in engagement. Therefore, it is unclear whether observed dynamics are unique to misinformation, or if we are in fact measuring common causes like political orientation or emotions in the stimuli, for instance, in hateful topics. Here, we study 9M German Twitter (now X) discussions from the timeframe October 2020 to March 2022 that follow a post mentioning sources with varying trustworthiness levels (~22M posts). Hence, we operationalize misinformation as posts mentioning untrustworthy sources. To do so, we rely on continuous source trustworthiness (0-100) and political orientation (left/right) ratings by the organization NewsGuard. 
In the first step of the analysis, we used a nonparametric matching approach to categorize the discussions (with at least one reply) into trustworthy vs. untrustworthy and balance our dataset on a set of covariates to approximate causal inference (emotions in the initial post, political orientation, author following/follower count, word count, time difference between first and last reply in discussion). Using machine learning to infer eight distinct emotions and out-group references from text, we then analyzed the effects of posts mentioning sources with varying trustworthiness and different political orientations on the development of online discussions in a natural digital environment. Results showed that trustworthiness predicts more anger co-occurring with out-group references, both in emotions aggregated for the whole discussion and the first reply to the initial post only. Vice versa, high trustworthiness predicts more joy. An analysis of the covariates hints at the underlying processes for this effect: For every aggregated emotion in the discussion, the same emotion was shown to be the strongest predictor. 
Subsequently, without the matching and therefore including the initial posts that did not get a reply, we analyzed the posts starting a discussion and found that posts containing untrustworthy sources significantly showed more anger and out-group references. However, lower trustworthiness was not associated with higher engagement overall. Only retweeting was negatively correlated with lower trustworthiness.
In conclusion, using the whole spectrum of news source trustworthiness and relying on a matching strategy, this study shows evidence for the limited effects of misinformation on social media, here operationalized as information coming from untrustworthy sources. Synthesizing literature from political communication science, psychology, and computational social science, we aim to disentangle the causal effects of news trustworthiness on emotions, and online engagement. We plan to further test the robustness of our results by bootstrapping the heavy-tailed distributions and to characterize the full discussion trees. 

