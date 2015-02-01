# Table of Contents
* RStudio
* BMI
* 偏差値
* 
* 
* 
* 
* 
* 
* 
* 
* 
* 
* 
* 
* 



* R Libraries x
* R Functions xi
* Preface xvi
* Introduction 1
## 0.1 Overview and rationale for this book 1  
* 0.1.1 Motivation for the book 1
* 0.1.2 Why R? 2
* 0.1.3 Other reading for R 2
## 0.2 What methods are covered in the book? 3
## 0.3 Structure of the book 4
## 0.4 Using R 5
* 0.4.1 Entering data 6
* 0.4.2 Dates 8
* 0.4.3 Exporting data 10
## 0.5 Further notes 11
## 0.6 A brief introduction to rprogs charts and figures 11
0.6.1 What if there is no date column? 18
## 0.7 Appendix menus 20
0.7.1 IMenu() 20
0.7.2 CCMenu() 21
# 1 Introduction to analysis of binary and proportion data 24
## 1.1 Single proportion, samples and population 24
1.1.1 Calculating the confidence interval 26
1.1.2 Comparison with an expected rate 27
## 1.2 Likelihood ratio (Bayes factor) & supported range 29
## 1.3 Confidence intervals for a series of proportions 30
## 1.4 Difference between two proportions 33
1.4.1 Confidence intervals 33
1.4.2 Hypothesis test 35
1.4.3 The twoproportions function 37
## 1.5 Introducing a Bayesian approach 39
## 1.6 When the data are not just one or two independent samples 39
1.6.1 More than two independent proportions 40
1.6.2 Example 1, yearly data 40
1.6.3 Example 2, hospital data 43
1.6.4 Prop test and small samples 47
## 1.7 Summarising stratified proportion data 48
## 1.8 Stratified proportion data, differences between rates 50
1.8.1 Yearly data 52
1.8.2 Hospital data 54
## 1.9 Mantel-Haenszel, homogeneity and trend tests 54
1.9.1 Yearly data 56
1.9.2 Data stratified by hospital 59
## 1.10 Stratified rates and overdispersion 63
# 2 The analysis of aggregated binary data 67
## 2.1 Risk-adjustment 68
2.1.1 Using stratification 68
2.1.2 Using logistic regression 70
## 2.2 Discrimination and calibration 71
## 2.3 Using 2005–06 data 76
2.3.1 Displaying and analysing data from multiple institutions 77
2.3.2 Tabulations 78
2.3.3 Funnel plot and plot of multiple confidence intervals 83
## 2.4 When the Es are not fixed 99
## 2.5 Complex Surgical Site Infections 102
2.5.1 Funnel plot analysis 102
2.5.2 Shrinkage analysis 104
## 2.6 Complex SSI risk-adjustment discrimination 106
## 2.7 Appendix 1 – Further tabulation methods 106
## 2.8 Appendix 2 – SMR CIs and tests, further scripts. Hospital expected values from other hospitals in group 109
# 3 Sequential binary data 116
3.1 CUSUM and related charts for binary data 117
3.2 Cumulative Observed-Expected (O-E) chart and combined CUSUM and O-E chart 120
3.3 Cumulative funnel plot and combined CUSUM and funnel plot 120
3.4 Example 121
3.5 Including risk adjustment 124
3.6 CUSUM chart 125
3.7 Cumulative observed minus expected (O-E) chart 125
3.8 Funnel plot 127
3.9 Discrimination and calibration of risk adjustment 128
3.10 Shewhart P chart and EWMA chart 132
3.11 Note on the Run-sum chart 135
3.12 The EWMA chart 135
3.13 Plotting the expected values 138
3.14 Using a spline or generalised additive model (GAM) chart 139
3.15 When there are few time periods 141
3.16 Charts for quarterly data and data without a first date column 143
3.17 Charts for composite measures 146
3.18 Additional tabulations 146
3.19 The issue of under-reporting 151
3.20 New CUSUM and EWMA charts, low-rate data 151
3.20.1 The risk-adjusted Bernoulli CUSUM 153
3.20.2 The EWMA 156
3.20.3 Quarterly rates 157
3.21 Intervals between uncommon binary adverse events 159
3.22 Appendix, proposed EWMA for low rate data 164
4 Introduction to analysis of count and rate data 168
4.1 Introduction 168
4.2 Rate and count data 169
4.3 Single count or rate 169
4.3.1 Confidence interval 170
4.3.2 Significance test 171
4.4 Confidence limits for columns of counts and rates 173
4.5 Two independent rates 175
4.5.1 Confidence interval 175
4.5.2 Hypothesis test 176
4.5.3 Bayesian approach 177
4.6 Chi-squared and trend tests for count and rate data 177
4.7 Stratified count and rate data 180
4.7.1 Obtaining a summary rate 180
4.7.2 Stratified count and rate data, two sets of rates 181
4.7.3 Indirect standardisation 182
4.7.4 Direct standardisation 184
4.8 Mantel-Haenszel, homogeneity and trend tests 187
4.8.1 Fixed effects analysis, stratification by years 187
4.8.2 Random effects analysis, stratification by hospitals 190
4.9 Illustration of dealing with overdispersed rates 193
4.10 The importance of count data variation 196
4.11 Complex systems, networks and variation 201
5 Tables and charts for aggregated count data 203
5.1 Introduction, data, limitations of aggregated count data analysis 203
5.2 Confidence intervals for Staphylococcus aureus bacteraemia SMR data 206
5.3 Funnel plots for Staphylococcus aureus bacteraemia SMR data 212
5.4 Tabulations and Z-scores 219
5.5 More on overdispersion, false discovery, very small expected counts 221
5.5.1 Proposal for Benjamini-Hochberg modified funnel plot 223
5.6 Bayesian shrinkage plot 227
5.6.1 Using OpenBUGS 228
5.6.2 Using empirical Bayes methods 229
5.7 Performing further tabulations in R 231
5.8 Adjusting hospital levels for MRSA bacteraemia 234
5.9 Bacteraemia risk adjustment 237
6 Sequential count and rate data 242
6.1 Grouping data 243
6.2 Means and variances, predictability 243
6.3 Tabulations 244
6.4 Denominators 246
6.5 Shewhart, EWMA and GAM control charts without denominators 247
6.5.1 Shewhart/EWMA charts 257
6.6 Shewhart, EWMA and GAM control charts with denominators 264
6.6.1 Overdispersed data 273
6.7 Charts for quarterly data and data without a first date column 280
6.8 When there are few time periods 282
6.9 Cross-tabulation in wide format 286
6.10 Uncommon count data AEs 291
6.11 Additional scripts for tabulations and charts 297
6.12 Intervals between uncommon count data events 300
6.13 Note on calculation of negative binomial parameters for control charts when denominators vary 303
6.13.1 Simple weighted variance 303
6.13.2 Linear approximation (Bissell) 303
6.13.3 Comparison of simple weighted variance and Bissell’s linear approximation 304
7 Miscellaneous AEs 307
7.1 MRO prevalence 308
7.2 Antibiotic usage 315
7.3 Spurious proportions, some blood culture data 316
7.4 RIDIT charts, ECG data 321
7.5 Numerical data – theatre utilisation 326
7.6 Length of stay (LOS) data 329
7.7 Changepoint 339
7.8 Assessing agreement 346
7.8.1 Numerical data agreement 348
7.9 Making decisions (decision analysis) 350
7.10 Investigating outbreaks, further analysis of stratified data 352
7.10.1 Reviewing stratified data analysis 355
7.10.2 Outbreak investigation example 361
8 Hospital safety and adverse event prevention 374
8.1 Introduction 374
8.2 An overview of hospital quality improvement, five pillars 375
8.2.1 The Customer, the first pillar 375
8.2.2 The Practitioner, the second pillar 375
8.2.3 The System, the third and main pillar 375
8.3 Medical error 376
8.3.1 Background of medical error (Vincent, Taylor-Adams & Vincent) 376
8.4 Improving the system 377
8.4.1 Evidence-based systems 377
8.4.2 The role of bundles and checklists 377
8.5 Error-proofing systems 379
8.6 Discipline and accountability 379
8.7 Limitations of imposing quality 380
8.8 Performance and predictable variation 380
8.9 The keys to a good system 381
8.10 Analysing and implementing evidence-based systems 381
8.11 The role of patient-care staff 382
8.12 The role of central authority 382
8.13 Change management, the fourth pillar 383
8.14 Feedback loops, the fifth pillar 383
8.15 Implementation of the Quality Improvement Process 384
8.15.1 Implementation 384
8.15.2 Obtaining data 386
8.15.3 Special issues with QI studies 386
8.16 The hospital as a network 389
References 391
Index 399

