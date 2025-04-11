# WSCT-Analysis-Matlab
Using Matlab to analyse WSCT data

指标说明
1. TC (Total Correct)
含义：总正确次数。
解释：在所有试次中，被试正确匹配卡片的次数。这反映了被试在任务中的整体表现。
2. TE (Total Errors)
含义：总错误次数。
解释：在所有试次中，被试错误匹配卡片的次数。这是通过总试次数减去总正确次数得到的。
3. PR (Perseverative Responses)
含义：持续反应次数。
解释：被试收到错误的提醒之后，仍然坚持在错误的维度上持续作出反应的次数。PR 反映了被试在任务中的认知灵活性和适应能力。
4. PE (Perseverative Errors)
含义：持续错误次数。
解释：PR 中错误的反应次数。PE 是 PR 的子集，即所有 PE 都是 PR，但并非所有 PR 都是 PE。PE 反映了被试在错误的维度上持续作出错误反应的次数，通常用于评估认知僵化程度。由于我们实验不包含ambiguous的trial，所以在我们的实验中PE 和PR相等。因为所有的PR都是错的，都是PE。
5. NPE (Non-Perseverative Errors)
含义：非持续错误次数。
解释：被试在非持续反应中错误匹配卡片的次数。这些错误不是由于持续反应引起的，而是由于其他原因（如随机猜测或注意力不集中）。
6. CLR (Conceptual Level Responses)
含义：概念水平反应次数。
解释：被试在正确分类规则下作出的反应次数。这反映了被试对任务规则的理解和应用能力。
7. CC (Categories Completed)
含义：完成的分类数量。
解释：被试成功完成的分类数量。每个分类通常需要连续正确匹配10次。CC 反映了被试在任务中的整体表现和认知灵活性。
8. T1C (Trials to Complete First Category)
含义：完成第一个分类所需的试次数。
解释：被试完成第一个分类所需的试次数。这反映了被试在任务初期的学习能力和适应能力。
9. FMS (Failure to Maintain Set)
含义：保持分类失败次数。
解释：被试在完成一个分类后，未能保持正确分类规则的次数。这反映了被试在任务中的注意力和保持能力。用于测量注意力分散，而不是认知灵活性 (Figueroa & Youmans, 2013)。
10. LL (Learning to Learn)
含义：学习能力。
解释：被试在任务中的学习能力，通常通过比较不同阶段的错误次数来评估。LL 反映了被试在任务中的学习和适应能力。TC，TE, PR, PE, NPE, CLR, CC, T1C, FMS, LL,
11.GS (Global Score) (Laiacona et al., 2000)
解释：表示WCST 性能的总体指标，Global Score = n of trials – [n of achieved categories × 5]，表示被试用了多少次尝试，是以下四种指标的结合：number of categories completed, number of trials administered, percent conceptual level responses and total number of errors.
