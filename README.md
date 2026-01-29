# Practical_App3: Bank Marketing Classifier Comparison
Comparing Classifiers using dataset of "Bank Marketing" in UCI Machine Learning repository

## Overview
Comparison of machine learning classifiers to predict term deposit subscriptions.

## Key Findings
1. Random Forest performed best with 91.2% accuracy and 0.58 F1 score
2. Campaign timing (March, September-December) significantly impacts conversion
3. Students and retired individuals have highest conversion rates
4. CAMPAIGN TIMING OPTIMIZATION:
   - Focus telemarketing efforts on March, September, October
   - Reduce or reallocate resources from May-July campaigns
   - Consider economic indicators when planning campaign intensity
5. TARGET AUDIENCE PRIORITIZATION:
   - High Priority: Students, retired individuals, university graduates
   - Medium Priority: Admin staff, technicians, management
   - Low Priority: Blue-collar workers, entrepreneurs (consider different products)
6. CONTACT STRATEGY REFINEMENT:
   - Limit contacts to 3-5 per campaign per client
   - Optimal follow-up: 2-3 weeks between contacts
   - Prefer cellular over landline contacts
7. MODEL DEPLOYMENT:
   - Implement lead scoring system using the Random Forest model
   - Set probability threshold at 0.5 initially, adjust based on business needs
   - Monitor precision, recall, and business KPIs monthly
8. EXPECTED BUSINESS IMPACT:
   - Conversion rate improvement: +5-7 percentage points
   - Marketing cost reduction: 30-40% through better targeting
   - Annual revenue impact: €500K-€1M in additional deposits

## Recommendations
- Focus campaigns on high-conversion months
- Target student and retired segments
- Implement model for lead scoring

### Files
- `prompt_III.ipynb`: Complete analysis
- `metrics_20260128_211112.json`: Metrics 
- `preprocessor_20260128_211112`: Data preprocessing pipeline

### View the Jupyter Notebook
You can view the full analysis here:  
👉 [Open the Notebook on GitHub](https://github.com/robin8wang/Practical_App3/blob/main/prompt_III.ipynb)
