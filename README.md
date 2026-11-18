# StatNex in Colab

Every worked example of the StatNex teaching guide as a notebook for Google Colab. The table is inside the notebook, and Colab has the libraries. Open one, choose **Copy to Drive** at the top, and in your copy choose **Runtime → Run all**. A copy is yours, so Colab runs it without its warning about notebooks from GitHub, and it keeps your changes.

Each notebook is the calculation StatNex runs, written out with pandas, SciPy and statsmodels. It does not use StatNex, and every number it prints was checked against the app's. Colab's library versions change over time, so a last digit can differ.

This repository is built by StatNex (`pipeline/build_colab_notebooks.py`); do not edit it by hand.

## Descriptive Statistics & Correlation

| Example | Method | Table |
|---|---|---|
| [Delivery times of three apps: 10% to 90% whiskers](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/box_plot_10_to_90.ipynb) | Box Plot | `01_basic/box_plot.csv` |
| [Delivery times of three apps: 5% to 95% whiskers](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/box_plot_5_to_95.ipynb) | Box Plot | `01_basic/box_plot.csv` |
| [Delivery times of three apps: mean ± SD, sorted](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/box_plot_mean_sd_sorted_by_mean.ipynb) | Box Plot | `01_basic/box_plot.csv` |
| [Delivery times of three apps: 1.5 x IQR whiskers](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/box_plot_q1_1_5_iqr.ipynb) | Box Plot | `01_basic/box_plot.csv` |
| [Delivery times of three apps: Tukey's hinges](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/box_plot_tukey_s_hinges.ipynb) | Box Plot | `01_basic/box_plot.csv` |
| [Beach kiosk sales and weather: correlations](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/correlation_matrix_correlations.ipynb) | Correlation and Partial Correlation Matrix | `01_basic/correlation_matrix.csv` |
| [Beach kiosk sales and weather: intervals and tests](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/correlation_matrix_intervals_and_tests.ipynb) | Correlation and Partial Correlation Matrix | `01_basic/correlation_matrix.csv` |
| [Beach kiosk: the raw variance-covariance matrix](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/covariance_matrix.ipynb) | Variance-Covariance Matrix | `01_basic/covariance_matrix.csv` |
| [A typical ZipEats order: mean, SD, SE and interval](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/descriptive_statistics.ipynb) | Descriptive Statistics | `01_basic/descriptive_statistics.csv` |
| [Every delivery time of three apps as a dot](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/dot_plot.ipynb) | Dot Plot | `01_basic/dot_plot.csv` |
| [Delivery times of three apps: classes 5 minutes wide](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/frequency_histogram_classes_5_minutes_wide.ipynb) | Frequency Distribution and Histogram | `01_basic/frequency_histogram.csv` |
| [Delivery times: service bands and a Pareto table](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/frequency_histogram_service_bands_and_pareto_table.ipynb) | Frequency Distribution and Histogram | `01_basic/frequency_histogram.csv` |
| [Delivery times: Sturges' classes and a normal fit test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/frequency_histogram_sturges_formula_and_goodness_of_fit.ipynb) | Frequency Distribution and Histogram | `01_basic/frequency_histogram.csv` |
| [Four judges score ten startup pitches: ICC](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/intraclass_correlation.ipynb) | Intraclass Correlation Coefficient | `01_basic/intraclass_correlation.csv` |
| [56 snacks, 13 attributes: what comes with a high price](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/kendall_correlation.ipynb) | Kendall's Rank Correlation Matrix | `01_basic/kendall_correlation.csv` |
| [Delivery times of three apps as smooth density curves](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/kernel_density.ipynb) | Kernel Density Estimation | `01_basic/kernel_density.csv` |
| [Mean delivery time per app, with error bars](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/mean_plot.ipynb) | Mean Plot with Error Bars | `01_basic/mean_plot.csv` |
| [Is it normal? Arrival minutes spread evenly](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/normal_probability_plot_arrival_minute.ipynb) | Normal Probability Plot and Normality Tests | `01_basic/normal_probability_plot.csv` |
| [Is it normal? One 118-second checkout breaks the line](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/normal_probability_plot_checkout_time_sec.ipynb) | Normal Probability Plot and Normality Tests | `01_basic/normal_probability_plot.csv` |
| [Is it normal? Cup weights follow the line](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/normal_probability_plot_cup_weight_g.ipynb) | Normal Probability Plot and Normality Tests | `01_basic/normal_probability_plot.csv` |
| [Is it normal? The logarithm of the spend](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/normal_probability_plot_logarithm_of_the_spend.ipynb) | Normal Probability Plot and Normality Tests | `01_basic/normal_probability_plot.csv` |
| [Cafe checkout times: Dixon's test on the 118 seconds](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/normal_probability_plot_outlier_test_dixon.ipynb) | Outlier Test (Smirnov-Grubbs) | `01_basic/normal_probability_plot.csv` |
| [Is it normal? A few big spenders skew the spend](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/normal_probability_plot_spend_per_customer.ipynb) | Normal Probability Plot and Normality Tests | `01_basic/normal_probability_plot.csv` |
| [Sneaker listings: Masuyama's rejection limits](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/outlier_test_masuyama_rejection_limits.ipynb) | Outlier Test (Smirnov-Grubbs) | `01_basic/outlier_test.csv` |
| [Sneaker listings: is $1,999 an outlier? Smirnov-Grubbs](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/outlier_test_smirnov_grubbs.ipynb) | Outlier Test (Smirnov-Grubbs) | `01_basic/outlier_test.csv` |
| [Sneaker listings: Thompson's test rejects three prices](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/outlier_test_thompson.ipynb) | Outlier Test (Smirnov-Grubbs) | `01_basic/outlier_test.csv` |
| [50 ZipEats orders: every pair of measures plotted](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/scatter_matrix.ipynb) | Scatter Plot Matrix | `01_basic/scatter_matrix.csv` |
| [47 creators: followers, engagement and sponsor income](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/spearman_correlation.ipynb) | Spearman's Rank Correlation Matrix | `01_basic/spearman_correlation.csv` |
| [Three apps from one database table: seven views at once](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/statistical_graphs.ipynb) | Statistical Graphs (Database Format) | `01_basic/statistical_graphs.csv` |
| [Delivery times of three apps: stem-and-leaf display](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/stem_and_leaf.ipynb) | Stem-and-Leaf Display | `01_basic/stem_and_leaf.csv` |
| [150 delivery orders: PCA on the correlation matrix](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/stratified_descriptives_pca_correlation_matrix.ipynb) | Principal Component Analysis | `01_basic/stratified_descriptives.csv` |
| [150 delivery orders: PCA on the covariance matrix](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/stratified_descriptives_pca_covariance_matrix.ipynb) | Principal Component Analysis | `01_basic/stratified_descriptives.csv` |
| [150 orders by app: group statistics and η²](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/01_basic/stratified_descriptives_stratified_statistics.ipynb) | Stratified Descriptive Statistics and Correlation Ratio | `01_basic/stratified_descriptives.csv` |

## One-Sample Estimation & Testing

| Example | Method | Table |
|---|---|---|
| [ZipEats pitch claims: mean intervals from 50 raw orders](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_mean_ci.ipynb) | Confidence Interval Estimation for the Mean | `02_one_sample/one_sample_mean_ci.csv` |
| [ZipEats pitch claims: mean intervals from a summary](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_mean_ci__summary.ipynb) | Confidence Interval Estimation for the Mean | `02_one_sample/one_sample_mean_ci__summary.csv` |
| [Advertised 20-hour battery life: t test on 30 phones](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_mean_test.ipynb) | One-Sample Test for the Mean | `02_one_sample/one_sample_mean_test.csv` |
| [Advertised 20-hour battery life: test from a summary](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_mean_test__summary.ipynb) | One-Sample Test for the Mean | `02_one_sample/one_sample_mean_test__summary.csv` |
| [Campus device ownership: Clopper-Pearson exact interval](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_proportion_ci_clopper_pearson_exact.ipynb) | Confidence Interval Estimation for the Population Proportion | `02_one_sample/one_sample_proportion_ci.csv` |
| [Campus device ownership: Wilson score interval](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_proportion_ci_wilson_score_interval.ipynb) | Confidence Interval Estimation for the Population Proportion | `02_one_sample/one_sample_proportion_ci.csv` |
| [Blind cola taste test: choices that exclude each other](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_proportion_diff__exclusive.ipynb) | Hypothesis Testing for the Difference of Population Proportions for 1 Sample | `02_one_sample/one_sample_proportion_diff__exclusive.csv` |
| [Social app use for an ad budget: choices that overlap](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_proportion_diff__overlap.ipynb) | Hypothesis Testing for the Difference of Population Proportions for 1 Sample | `02_one_sample/one_sample_proportion_diff__overlap.csv` |
| [New pricing page: conversion against the old 13%](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_proportion_test.ipynb) | One-Sample Test for a Proportion | `02_one_sample/one_sample_proportion_test.csv` |
| [ZipEats delivery spread: interval from 50 raw orders](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_variance_ci.ipynb) | Confidence Interval Estimation for the Variance | `02_one_sample/one_sample_variance_ci.csv` |
| [ZipEats delivery spread: interval from a summary](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_variance_ci__summary.ipynb) | Confidence Interval Estimation for the Variance | `02_one_sample/one_sample_variance_ci__summary.csv` |
| [Chip bag weights: each line against the 1 g rule](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_variance_test.ipynb) | Hypothesis Testing for the Variance | `02_one_sample/one_sample_variance_test.csv` |
| [Chip bag weights: the 1 g rule from a summary sheet](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/02_one_sample/one_sample_variance_test__summary.ipynb) | Hypothesis Testing for the Variance | `02_one_sample/one_sample_variance_test__summary.csv` |

## Two-Sample Comparison

| Example | Method | Table |
|---|---|---|
| [Chip packing lines: is Line B less consistent?](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/03_two_sample/homogeneity_of_variance.ipynb) | Test for Homogeneity of Variance | `03_two_sample/homogeneity_of_variance.csv` |
| [Chip packing lines: variance test from a shift report](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/03_two_sample/homogeneity_of_variance__summary.ipynb) | Test for Homogeneity of Variance | `03_two_sample/homogeneity_of_variance__summary.csv` |
| [Background music in nine stores: pooled basket lift](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/03_two_sample/mean_difference_meta_analysis.ipynb) | Meta-Analysis of the Difference between Means | `03_two_sample/mean_difference_meta_analysis.csv` |
| [Negotiation course: weekly sales before and after](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/03_two_sample/paired_mean_test.ipynb) | Paired Test for Means | `03_two_sample/paired_mean_test.csv` |
| [Chatbot or human agent: minutes to resolve a ticket](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/03_two_sample/two_sample_mean_database.ipynb) | Two-Sample Test for Means (Database Format) | `03_two_sample/two_sample_mean_database.csv` |
| [Chatbot or human agent: testing the logarithms of the minutes](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/03_two_sample/two_sample_mean_database_logarithm_of_the_minutes.ipynb) | Two-Sample Test for Means (Database Format) | `03_two_sample/two_sample_mean_database.csv` |
| [Chatbot desk vs human desk: tickets from raw weeks](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/03_two_sample/two_sample_mean_table.ipynb) | Two-Sample Test for Means (Table Format) | `03_two_sample/two_sample_mean_table.csv` |
| [Chatbot desk vs human desk: test from a board summary](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/03_two_sample/two_sample_mean_table__summary.ipynb) | Two-Sample Test for Means (Table Format) | `03_two_sample/two_sample_mean_table__summary.csv` |
| [Ad A vs Ad B: the large test, 24,000 visitors per ad](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/03_two_sample/two_sample_proportion_test.ipynb) | Hypothesis Testing for the Difference in the Population Proportions | `03_two_sample/two_sample_proportion_test.csv` |
| [Ad A vs Ad B: the pilot, 600 visitors per ad](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/03_two_sample/two_sample_proportion_test__pilot.ipynb) | Hypothesis Testing for the Difference in the Population Proportions | `03_two_sample/two_sample_proportion_test__pilot.csv` |

## Frequency & Contingency Tables

| Example | Method | Table |
|---|---|---|
| [Online shop orders: how customers pay](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/categorical_frequency.ipynb) | Frequency Distribution for Categorical Data | `04_crosstab/categorical_frequency.csv` |
| [Jacket discounts: Cochran-Armitage trend test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/cochran_armitage_cochran_armitage_trend_test.ipynb) | Cochran-Armitage Test for Trend | `04_crosstab/cochran_armitage.csv` |
| [Jacket discounts: Fisher's exact test on a 4 x 2 table](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/cochran_armitage_fisher_s_exact_test.ipynb) | Fisher's Exact Test | `04_crosstab/cochran_armitage.csv` |
| [Promo email by customer type: CMH test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/cochran_mantel_haenszel.ipynb) | Cochran-Mantel-Haenszel Test | `04_crosstab/cochran_mantel_haenszel.csv` |
| [Emoji reactions to posts: correspondence analysis of counts](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/correspondence_analysis__counts.ipynb) | Correspondence Analysis | `04_crosstab/correspondence_analysis__counts.csv` |
| [Phone brand ratings: correspondence analysis of means](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/correspondence_analysis__means.ipynb) | Correspondence Analysis | `04_crosstab/correspondence_analysis__means.csv` |
| [Sales channel by age group: row percentages](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/correspondence_analysis__row_percent.ipynb) | Correspondence Analysis | `04_crosstab/correspondence_analysis__row_percent.csv` |
| [Streaming plans and satisfaction: from counted rows](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/cross_tabulation__counts.ipynb) | Cross Tabulation and Analysis | `04_crosstab/cross_tabulation__counts.csv` |
| [Streaming plans and satisfaction: chi-square and residuals](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/cross_tabulation__raw_chi_square_and_residuals.ipynb) | Cross Tabulation and Analysis | `04_crosstab/cross_tabulation__raw.csv` |
| [Streaming plans and satisfaction: association measures](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/cross_tabulation__raw_plus_association_measures.ipynb) | Cross Tabulation and Analysis | `04_crosstab/cross_tabulation__raw.csv` |
| [Emoji reactions to posts: dual scaling](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/dual_scaling.ipynb) | Dual Scaling | `04_crosstab/dual_scaling.csv` |
| [Email frequency and unsubscribes: Mantel-extension test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/extended_mantel.ipynb) | Mantel-Extension Test | `04_crosstab/extended_mantel.csv` |
| [Free-sample pilot: Fisher's exact test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/fisher_exact_test.ipynb) | Fisher's Exact Test | `04_crosstab/fisher_exact_test.csv` |
| [Age and online shopping frequency: gamma](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/goodman_kruskal_gamma.ipynb) | Goodman-Kruskal's Gamma | `04_crosstab/goodman_kruskal_gamma.csv` |
| [Phone type and paying for app features: tau](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/goodman_kruskal_tau.ipynb) | Goodman-Kruskal's Tau | `04_crosstab/goodman_kruskal_tau.csv` |
| [T-shirt colours, week 3: planned stock as counts](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/goodness_of_fit__week3_expected_counts.ipynb) | Goodness-of-Fit Test | `04_crosstab/goodness_of_fit__week3.csv` |
| [T-shirt colours, week 3: planned proportions](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/goodness_of_fit__week3_expected_proportions.ipynb) | Goodness-of-Fit Test | `04_crosstab/goodness_of_fit__week3.csv` |
| [T-shirt colours, week 1: planned stock as counts](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/goodness_of_fit_expected_counts.ipynb) | Goodness-of-Fit Test | `04_crosstab/goodness_of_fit.csv` |
| [T-shirt colours, week 1: planned proportions](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/goodness_of_fit_expected_proportions.ipynb) | Goodness-of-Fit Test | `04_crosstab/goodness_of_fit.csv` |
| [Free-sample pilot: chi-square test on a 2 x 2 table](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/independence_test__2x2.ipynb) | Test of Independence | `04_crosstab/independence_test__2x2.csv` |
| [Streaming survey as a bare 3 x 5 table](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/independence_test__3x5.ipynb) | Test of Independence | `04_crosstab/independence_test__3x5.csv` |
| [Two staff labelling comments: Bowker and Stuart-Maxwell](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/kappa_coefficient_bowker_and_stuart_maxwell_tests.ipynb) | McNemar Test | `04_crosstab/kappa_coefficient.csv` |
| [Two staff labelling comments: kappa](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/kappa_coefficient_kappa.ipynb) | Kappa Coefficient | `04_crosstab/kappa_coefficient.csv` |
| [Smart speaker demo video: McNemar test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/mcnemar_test.ipynb) | McNemar Test | `04_crosstab/mcnemar_test.csv` |
| [Age and online shopping: residual analysis](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/residual_analysis.ipynb) | Residual Analysis of a Cross Tabulation | `04_crosstab/residual_analysis.csv` |
| [Free-sample pilot: risk ratio and odds ratio](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/04_crosstab/risk_ratio_odds_ratio.ipynb) | Risk Ratio and Odds Ratio | `04_crosstab/risk_ratio_odds_ratio.csv` |

## Analysis of Variance & Multiple Comparisons

| Example | Method | Table |
|---|---|---|
| [Promotions and foot traffic: adjusted means](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/ancova__adjusted.ipynb) | Analysis of Covariance | `05_anova/ancova__adjusted.csv` |
| [Promotions and foot traffic: testing parallel slopes](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/ancova__parallel.ipynb) | Analysis of Covariance | `05_anova/ancova__parallel.csv` |
| [Pizza taste test: crust, cheese and price tag](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/factorial_anova.ipynb) | Factorial Analysis of Variance | `05_anova/factorial_anova.csv` |
| [Chocolate price guesses: packaging, store and brand](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/factorial_anova_repeated.ipynb) | Factorial Repeated Measures Analysis of Variance | `05_anova/factorial_anova_repeated.csv` |
| [Store formats and seasons: four outcomes at once](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/manova.ipynb) | Multivariate Analysis of Variance | `05_anova/manova.csv` |
| [Checkout page redesigns: Dunnett's test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/one_way_anova__dunnett.ipynb) | One-Way Analysis of Variance | `05_anova/one_way_anova__dunnett.csv` |
| [Shelf positions for an energy drink: Tukey's test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/one_way_anova__tukey.ipynb) | One-Way Analysis of Variance | `05_anova/one_way_anova__tukey.csv` |
| [Shelf positions for an energy drink: Bonferroni](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/one_way_anova__tukey_bonferroni.ipynb) | One-Way Analysis of Variance | `05_anova/one_way_anova__tukey.csv` |
| [Shelf positions for an energy drink: Holm](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/one_way_anova__tukey_holm.ipynb) | One-Way Analysis of Variance | `05_anova/one_way_anova__tukey.csv` |
| [Three shelf positions: Fisher's LSD](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/one_way_anova__tukey_lsd_three_positions.ipynb) | One-Way Analysis of Variance | `05_anova/one_way_anova__tukey.csv` |
| [Shelf positions for an energy drink: Scheffé's test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/one_way_anova__tukey_scheffe.ipynb) | One-Way Analysis of Variance | `05_anova/one_way_anova__tukey.csv` |
| [Shelf positions for an energy drink: Šidák](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/one_way_anova__tukey_sidak.ipynb) | One-Way Analysis of Variance | `05_anova/one_way_anova__tukey.csv` |
| [Shelf positions and spread: Bartlett's and Levene's tests](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/one_way_anova__tukey_variance_tests.ipynb) | Test for Homogeneity of Variance | `05_anova/one_way_anova__tukey.csv` |
| [Sales training hours: Williams' test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/one_way_anova__williams.ipynb) | One-Way Analysis of Variance | `05_anova/one_way_anova__williams.csv` |
| [Burger recipes rated by the same customers](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/one_way_anova_repeated.ipynb) | One-way Repeated Measures Analysis of Variance | `05_anova/one_way_anova_repeated.csv` |
| [Email features in eight versions: which drive clicks](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/orthogonal_array_analysis.ipynb) | Orthogonal Arrays Testing (Taguchi Designs) | `05_anova/orthogonal_array_analysis.csv` |
| [Planning an email test: a 12-version orthogonal array](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/orthogonal_array_design.ipynb) | Design of Orthogonal Arrays (Taguchi Designs) | `05_anova/orthogonal_array_design.csv` |
| [Four logo designs: Scheffé's paired comparison](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/paired_comparison.ipynb) | Paired Comparison | `05_anova/paired_comparison.csv` |
| [Ad conversion on four channels: Marascuilo procedure](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/proportion_multiple_comparison.ipynb) | Comparing Multiple Proportions: The Marascuilo Procedure | `05_anova/proportion_multiple_comparison.csv` |
| [Product displays in five stores: a blocked plan](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/randomized_block_design.ipynb) | Randomized Block Design | `05_anova/randomized_block_design.csv` |
| [Coffee price by time of day: Holm's method](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/two_way_anova_holm.ipynb) | Two-Way Analysis of Variance | `05_anova/two_way_anova.csv` |
| [Fitness app onboarding: activity over four weeks](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/two_way_anova_repeated.ipynb) | Two-way Repeated Measures Analysis of Variance | `05_anova/two_way_anova_repeated.csv` |
| [Coffee price by time of day: Tukey's test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/05_anova/two_way_anova_tukey.ipynb) | Two-Way Analysis of Variance | `05_anova/two_way_anova.csv` |

## Nonparametric Tests

| Example | Method | Table |
|---|---|---|
| [Chatbot vs human agent tickets: Brunner-Munzel test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/brunner_munzel.ipynb) | Brunner-Munzel Test | `06_nonparametric/brunner_munzel.csv` |
| [Three checkout designs, ten shoppers: Cochran's Q test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/cochran_q.ipynb) | Cochran's Q Test | `06_nonparametric/cochran_q.csv` |
| [Four energy drink flavours: Friedman test finds no winner](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/friedman_test.ipynb) | Friedman Test | `06_nonparametric/friedman_test.csv` |
| [Sales by training hours: Jonckheere-Terpstra trend test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/jonckheere_terpstra.ipynb) | Jonckheere-Terpstra Test | `06_nonparametric/jonckheere_terpstra.csv` |
| [Listing photos and views: Dunn's comparisons](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/kruskal_wallis_dunn.ipynb) | Kruskal-Wallis Test with Multiple Comparisons | `06_nonparametric/kruskal_wallis.csv` |
| [Listing photos and views: Scheffé's comparisons](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/kruskal_wallis_scheffe.ipynb) | Kruskal-Wallis Test with Multiple Comparisons | `06_nonparametric/kruskal_wallis.csv` |
| [Listing photos and views: Shirley-Williams test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/kruskal_wallis_shirley_williams.ipynb) | Kruskal-Wallis Test with Multiple Comparisons | `06_nonparametric/kruskal_wallis.csv` |
| [Listing photos and views: Steel's test against 1 photo](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/kruskal_wallis_steel.ipynb) | Kruskal-Wallis Test with Multiple Comparisons | `06_nonparametric/kruskal_wallis.csv` |
| [Listing photos and views: Steel-Dwass comparisons](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/kruskal_wallis_steel_dwass.ipynb) | Kruskal-Wallis Test with Multiple Comparisons | `06_nonparametric/kruskal_wallis.csv` |
| [Listing photos and views: Williams test after ANOVA](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/kruskal_wallis_williams_one_way_anova.ipynb) | One-Way Analysis of Variance | `06_nonparametric/kruskal_wallis.csv` |
| [Chatbot vs human resolution times: Kolmogorov-Smirnov test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/ks_two_sample.ipynb) | Two-Sample Kolmogorov-Smirnov Test | `06_nonparametric/ks_two_sample.csv` |
| [Ticket counts by time band: Kolmogorov-Smirnov test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/ks_two_sample__grouped.ipynb) | Two-Sample Kolmogorov-Smirnov Test | `06_nonparametric/ks_two_sample__grouped.csv` |
| [Chatbot vs human agent tickets: Mann-Whitney U test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/mann_whitney_u.ipynb) | Mann-Whitney U Test | `06_nonparametric/mann_whitney_u.csv` |
| [Chatbot vs human agent tickets: median test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/median_test.ipynb) | Median Test | `06_nonparametric/median_test.csv` |
| [Pitch scores before and after coaching: sign test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/sign_test.ipynb) | Sign Test | `06_nonparametric/sign_test.csv` |
| [Store customers, week 1 vs week 2: zero difference excluded](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/wilcoxon_signed_rank_exclude_zero_differences.ipynb) | Wilcoxon Signed-Rank Test | `06_nonparametric/wilcoxon_signed_rank.csv` |
| [Store customers, week 1 vs week 2: Pratt's method](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/06_nonparametric/wilcoxon_signed_rank_pratt_s_method.ipynb) | Wilcoxon Signed-Rank Test | `06_nonparametric/wilcoxon_signed_rank.csv` |

## Survival & Hazard Analysis

| Example | Method | Table |
|---|---|---|
| [Meal-kit churn: forward stepwise selection](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/07_survival/cox_proportional_hazards__churn.ipynb) | Cox Proportional Hazard Model | `07_survival/cox_proportional_hazards__churn.csv` |
| [Employee turnover: all covariates in the model](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/07_survival/cox_proportional_hazards__turnover.ipynb) | Cox Proportional Hazard Model | `07_survival/cox_proportional_hazards__turnover.csv` |
| [Onboarding emails and cancellations: one row per customer](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/07_survival/kaplan_meier_database.ipynb) | Kaplan-Meier Method (Database Format) | `07_survival/kaplan_meier_database.csv` |
| [Onboarding emails and cancellations: table format](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/07_survival/kaplan_meier_table.ipynb) | Kaplan-Meier Method (Table Format) | `07_survival/kaplan_meier_table.csv` |

## Time Series & Curve Fitting

| Example | Method | Table |
|---|---|---|
| [Bakery flour orders: autocorrelation of a zigzag](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/autocorrelation.ipynb) | Autocorrelation | `08_time_series/autocorrelation.csv` |
| [Oil, fuel and tech share prices: cointegration test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/cointegration_test.ipynb) | Cointegration Test | `08_time_series/cointegration_test.csv` |
| [Ad spend and website visits: cross correlation by lag](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/cross_correlation.ipynb) | Cross Correlation | `08_time_series/cross_correlation.csv` |
| [Ice-cream sales trend: from a line to a quintic curve](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/curve_fitting.ipynb) | Finding Curve | `08_time_series/curve_fitting.csv` |
| [Ice-cream quarterly sales: EPA decomposition and forecast](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/epa_method.ipynb) | EPA Method | `08_time_series/epa_method.csv` |
| [Campus coffee sales: exponential smoothing forecast](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/exponential_smoothing.ipynb) | Exponential Smoothing Method | `08_time_series/exponential_smoothing.csv` |
| [Bubble-tea revenue: link relative seasonal indices](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/link_relative.ipynb) | Link Relative Method | `08_time_series/link_relative.csv` |
| [Campus coffee sales: 7-day moving average](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/moving_average.ipynb) | Moving-Average Method | `08_time_series/moving_average.csv` |
| [Bubble-tea quarterly revenue: seasonal average indices](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/period_average.ipynb) | Seasonal Average Method | `08_time_series/period_average.csv` |
| [Bubble-tea revenue as a quarter-by-year table](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/period_average__table.ipynb) | Seasonal Average Method | `08_time_series/period_average__table.csv` |
| [Share price and store visitors: unit root test](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/08_time_series/unit_root_test.ipynb) | Unit Root Test | `08_time_series/unit_root_test.csv` |

## Multivariate Analysis

| Example | Method | Table |
|---|---|---|
| [Job offers: internship and interview preparation](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/binary_logistic_regression.ipynb) | Binary Logistic Regression | `09_multivariate/binary_logistic_regression.csv` |
| [Employee attitudes and performance: two sets of measures](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/canonical_correlation.ipynb) | Canonical Correlation Analysis | `09_multivariate/canonical_correlation.csv` |
| [Seven phone models: hierarchical clustering, Ward's method](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/cluster_analysis__individuals.ipynb) | Cluster Analysis | `09_multivariate/cluster_analysis__individuals.csv` |
| [Snack market segments: k-means with four clusters](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/cluster_analysis__kmeans.ipynb) | Cluster Analysis | `09_multivariate/cluster_analysis__kmeans.csv` |
| [Beach kiosk figures: clustering the variables](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/cluster_analysis__variables.ipynb) | Cluster Analysis | `09_multivariate/cluster_analysis__variables.csv` |
| [Customer churn in matched signup-week sets](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/conditional_logistic_regression.ipynb) | Conditional Logistic Regression | `09_multivariate/conditional_logistic_regression.csv` |
| [Cafe service score: five items, one that does not belong](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/cronbach_alpha.ipynb) | Cronbach's Alpha | `09_multivariate/cronbach_alpha.csv` |
| [Loan defaults: two groups, debt-to-income and credit score](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/discriminant_analysis__2groups.ipynb) | Discriminant Analysis | `09_multivariate/discriminant_analysis__2groups.csv` |
| [Three delivery apps: forward stepwise selection](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/discriminant_analysis__3groups.ipynb) | Discriminant Analysis | `09_multivariate/discriminant_analysis__3groups.csv` |
| [Cafe survey of 12 items: three factors, varimax rotation](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/factor_analysis.ipynb) | Factor Analysis | `09_multivariate/factor_analysis.csv` |
| [Job satisfaction in 40 companies: fixed and random effects](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/linear_mixed_model.ipynb) | Linear Mixed Model | `09_multivariate/linear_mixed_model.csv` |
| [Fifteen drinks: a map from customer-group ratings](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/multidimensional_scaling.ipynb) | Multidimensional Scaling | `09_multivariate/multidimensional_scaling.csv` |
| [Seven European warehouses: rebuilding a map from distances](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/multidimensional_scaling_matrix.ipynb) | Multidimensional Scaling (Matrix Format) | `09_multivariate/multidimensional_scaling_matrix.csv` |
| [Card, mobile wallet or cash: payment choice by age](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/multinomial_logistic_regression.ipynb) | Multinomial Logistic Regression | `09_multivariate/multinomial_logistic_regression.csv` |
| [Coffee shop sales: 20 profiles counted as 30 shops](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/multiple_regression__frequency.ipynb) | Multiple Regression | `09_multivariate/multiple_regression__frequency.csv` |
| [Coffee shop sales: all variables, constant set to 0](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/multiple_regression_constant_set_to_0.ipynb) | Multiple Regression | `09_multivariate/multiple_regression.csv` |
| [Coffee shop sales: forward stepwise selection, 20 shops](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/multiple_regression_stepwise_selection.ipynb) | Multiple Regression | `09_multivariate/multiple_regression.csv` |
| [Likely to recommend: membership, app use and satisfaction](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/ordinal_logistic_regression.ipynb) | Ordinal Logistic Regression | `09_multivariate/ordinal_logistic_regression.csv` |
| [Snack market map: principal components of 13 attributes](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/principal_component_analysis.ipynb) | Principal Component Analysis | `09_multivariate/principal_component_analysis.csv` |
| [Discount levels and buying: the half-buy discount](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/probit_regression.ipynb) | Probit Regression | `09_multivariate/probit_regression.csv` |
| [Coffee spend by age group and gender: category scores](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/quantification_i_quantification_method_i.ipynb) | Hayashi's Quantification Method I | `09_multivariate/quantification_i.csv` |
| [Coffee spend by age and gender: Type I sums of squares](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/quantification_i_two_way_anova_type_i.ipynb) | Two-Way Analysis of Variance | `09_multivariate/quantification_i.csv` |
| [Coffee spend by age and gender: Type II sums of squares](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/quantification_i_two_way_anova_type_ii.ipynb) | Two-Way Analysis of Variance | `09_multivariate/quantification_i.csv` |
| [Coffee spend by age and gender: Type III sums of squares](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/quantification_i_two_way_anova_type_iii.ipynb) | Two-Way Analysis of Variance | `09_multivariate/quantification_i.csv` |
| [Premium plan subscribers: age, gender and device](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/quantification_ii__2groups.ipynb) | Hayashi's Quantification Method II | `09_multivariate/quantification_ii__2groups.csv` |
| [Spending tiers: three groups on two axes](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/quantification_ii__3groups.ipynb) | Hayashi's Quantification Method II | `09_multivariate/quantification_ii__3groups.csv` |
| [Subscription services: one lifestyle line](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/quantification_iii.ipynb) | Hayashi's Quantification Method III | `09_multivariate/quantification_iii.csv` |
| [Eight stores in a ring: testing the method on a known map](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/quantification_iv.ipynb) | Hayashi's Quantification Method IV | `09_multivariate/quantification_iv.csv` |
| [Six social platform types: a map from similarity ratings](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/09_multivariate/quantification_iv_matrix.ipynb) | Hayashi's Quantification Method IV (Matrix Format) | `09_multivariate/quantification_iv_matrix.csv` |

## Control Charts & ROC Curves

| Example | Method | Table |
|---|---|---|
| [App crash reports per day: c chart](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/10_control_chart/c_chart.ipynb) | c Control Chart | `10_control_chart/c_chart.csv` |
| [Burger patty weights: median and range chart](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/10_control_chart/median_r_chart.ipynb) | Median-R Control Chart | `10_control_chart/median_r_chart.csv` |
| [Faulty parcels in 200 checked: np chart, month 1](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/10_control_chart/np_chart.ipynb) | np Control Chart | `10_control_chart/np_chart.csv` |
| [Faulty parcels in 200 checked: np chart, month 2](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/10_control_chart/np_chart__month2.ipynb) | np Control Chart | `10_control_chart/np_chart__month2.csv` |
| [Daily return rate with changing order counts: p chart](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/10_control_chart/p_chart.ipynb) | p Control Chart | `10_control_chart/p_chart.csv` |
| [Two fraud-detection models: ROC curves compared](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/10_control_chart/roc_curve.ipynb) | ROC Curve | `10_control_chart/roc_curve.csv` |
| [Bugs per thousand lines by release: u chart](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/10_control_chart/u_chart.ipynb) | u Control Chart | `10_control_chart/u_chart.csv` |
| [Online orders per day and a campaign start: X-Rs chart](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/10_control_chart/x_rs_chart.ipynb) | X-Rs (Individuals and Moving Range) Control Chart | `10_control_chart/x_rs_chart.csv` |
| [Burger patty weights: mean and range chart](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/10_control_chart/xbar_r_chart.ipynb) | Xbar-R Control Chart | `10_control_chart/xbar_r_chart.csv` |
| [Burger patty weights: mean and standard deviation chart](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/10_control_chart/xbar_s_chart.ipynb) | Xbar-s Control Chart | `10_control_chart/xbar_s_chart.csv` |

## Specialised Charts

| Example | Method | Table |
|---|---|---|
| [Cafe stores: average ticket and rating by region](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/11_chart/labelled_scatter_plot.ipynb) | Labelled / Stratified Scatter Plot | `11_chart/labelled_scatter_plot.csv` |
| [Customer spending by decile: Lorenz curve](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/11_chart/lorenz_curve__deciles.ipynb) | Lorenz Curve and Gini Coefficient | `11_chart/lorenz_curve__deciles.csv` |
| [Sales at five price points: Lorenz curve](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/11_chart/lorenz_curve__prices.ipynb) | Lorenz Curve and Gini Coefficient | `11_chart/lorenz_curve__prices.csv` |
| [Streaming plans: satisfaction mosaic plot](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/11_chart/mosaic_plot.ipynb) | Mosaic Plot | `11_chart/mosaic_plot.csv` |
| [Theme park visitors by age and gender](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/11_chart/population_pyramid.ipynb) | Population Pyramid | `11_chart/population_pyramid.csv` |
| [Revenue mix of seven companies: ternary plot](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/11_chart/ternary_plot.ipynb) | Ternary Plot | `11_chart/ternary_plot.csv` |
| [Snack profiles by price tier across 13 attributes](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/11_chart/vertical_line_graph.ipynb) | Vertical Line Graph | `11_chart/vertical_line_graph.csv` |
| [Four coffee-shop drinks: sales index through the year](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/11_chart/vertical_line_graph_range.ipynb) | Vertical Line Graph - Changing the Data Range | `11_chart/vertical_line_graph_range.csv` |

## Utilities

| Example | Method | Table |
|---|---|---|
| [Review scores to classes: equal width of 20 points](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/categorical_conversion_equal_width_classes.ipynb) | Conversion to Categorical Variables | `12_utility/categorical_conversion.csv` |
| [Review scores to letter grades: cut points 60, 70, 80](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/categorical_conversion_grades_d_to_a_at_60_70_80.ipynb) | Conversion to Categorical Variables | `12_utility/categorical_conversion.csv` |
| [Sales rep measures: Box-Cox transformation as a warning](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/data_transformation_box_cox_transformation.ipynb) | Data Transformation | `12_utility/data_transformation.csv` |
| [Sales rep measures on one scale: z scores](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/data_transformation_z_scores.ipynb) | Data Transformation | `12_utility/data_transformation.csv` |
| [Survey answers to 0/1 columns: last category as base](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/dummy_variable_conversion_drop_the_last_category.ipynb) | Conversion to Dummy Variables | `12_utility/dummy_variable_conversion.csv` |
| [Survey answers to 0/1 columns: every category kept](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/dummy_variable_conversion_keep_every_category.ipynb) | Conversion to Dummy Variables | `12_utility/dummy_variable_conversion.csv` |
| [Five sales measures: eigenvalues of the correlations](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/eigen_decomposition.ipynb) | Eigenvalue Decomposition | `12_utility/eigen_decomposition.csv` |
| [Five sales measures: inverse of the correlation matrix](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/matrix_inverse_matrix_inversion.ipynb) | Matrix Inversion | `12_utility/matrix_inverse.csv` |
| [100 binomial draws, five times: sample against theory](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/matrix_inverse_random_binomial_draws.ipynb) | Random Number Generation | `12_utility/matrix_inverse.csv` |
| [200 simulated sales reps from a correlation matrix](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/matrix_inverse_random_multivariate_normal_draws.ipynb) | Random Number Generation | `12_utility/matrix_inverse.csv` |
| [Skipped survey questions: age, income, phone hours](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/missing_value_check.ipynb) | Missing Value Check | `12_utility/missing_value_check.csv` |
| [Did the influencer ad cause purchases? Matched pairs](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/12_utility/propensity_score_matching.ipynb) | Propensity Score Matching | `12_utility/propensity_score_matching.csv` |

## Sample Size & Power

| Example | Method | Table |
|---|---|---|
| [Planning a retention study: log-rank test sample size](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/13_sample_size/sample_size__effect_sizes_log_rank_test.ipynb) | Sample Size and Power Calculation | `13_sample_size/sample_size__effect_sizes.csv` |
| [Planning a before/after study: paired t test sample size](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/13_sample_size/sample_size__effect_sizes_paired_t_test.ipynb) | Sample Size and Power Calculation | `13_sample_size/sample_size__effect_sizes.csv` |
| [Sales training with 30 reps: power after the study](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/13_sample_size/sample_size__power.ipynb) | Sample Size and Power Calculation | `13_sample_size/sample_size__power.csv` |

## Bayesian Analysis

| Example | Method | Table |
|---|---|---|
| [Welcome offers: free delivery or 10% off, profit per order](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/14_bayesian/bayes_ab_means.ipynb) | Bayesian A/B Test for Two Means | `14_bayesian/bayes_ab_means.csv` |
| [Old or new checkout page: purchase rates](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/14_bayesian/bayes_ab_proportions.ipynb) | Bayesian A/B Test for Two Proportions | `14_bayesian/bayes_ab_proportions.csv` |
| [New courier's delivery time against a 72-hour promise](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/14_bayesian/bayes_mean.ipynb) | Bayesian Estimation of the Population Mean | `14_bayesian/bayes_mean.csv` |
| [New bottle-cap supplier: faulty rate against a 2% limit](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/14_bayesian/bayes_proportion.ipynb) | Bayesian Estimation of the Population Proportion | `14_bayesian/bayes_proportion.csv` |
| [Which ad channels pay back more than a dollar](https://colab.research.google.com/github/nguyen-yumot/statnex-colab/blob/main/notebooks/14_bayesian/bayes_regression.ipynb) | Bayesian Linear Regression | `14_bayesian/bayes_regression.csv` |
