# Employee Sentiment Analysis Summary Report

## Executive Summary
This report presents the findings from an analysis of employee sentiment based on message data. The analysis employs natural language processing and machine learning techniques to identify patterns, trends, and potential flight risks among employees.

## Methodology

### Data Processing
- Messages were processed using TextBlob for sentiment analysis
- Sentiment scores were categorized as Positive (>0.1), Negative (<-0.1), or Neutral
- Time-based aggregation was performed on a monthly basis
- Rolling 30-day windows were used for flight risk detection

### Analysis Components
1. **Basic Sentiment Analysis**
   - Individual message sentiment scoring
   - Monthly aggregation of sentiment scores
   - Distribution analysis of sentiment categories

2. **Employee-Level Analysis**
   - Individual sentiment tracking
   - Monthly sentiment score calculation
   - Identification of consistently positive/negative patterns

3. **Flight Risk Detection System**
   - Identification of employees with ≥4 negative messages in 30 days
   - Temporal pattern analysis of negative sentiment
   - Trend analysis using linear regression

## Key Findings

### 1. Sentiment Distribution
- Messages were classified into three categories: Positive, Neutral, and Negative
- Distribution shows the overall sentiment climate in the organization

### 2. Top Performers
- Monthly rankings highlight consistently positive employees
- Temporal analysis shows stability/variability in positive sentiment

### 3. Flight Risk Indicators
- Employees with high frequency of negative messages identified
- Rolling window analysis reveals sustained negative patterns
- Linear regression models show sentiment trend trajectories

### 4. Trend Analysis
- Monthly sentiment patterns tracked over time
- Linear regression models provide predictive insights
- Performance metrics (MSE, R² scores) indicate prediction reliability

## Recommendations

1. **Immediate Action Required**
   - Direct attention to identified flight risk employees
   - Schedule one-on-one meetings with employees showing negative trends

2. **Monitoring Strategy**
   - Continue monthly sentiment tracking
   - Set up alerts for negative sentiment patterns
   - Regular review of sentiment trends

3. **Preventive Measures**
   - Implement early intervention for emerging negative patterns
   - Regular check-ins with employees showing sentiment volatility

## Technical Implementation
- Analysis conducted using Python and common data science libraries
- Automated pipeline for continuous monitoring
- Visualization tools for easy pattern recognition

## Limitations
- Sentiment analysis based on TextBlob may miss context nuances
- Limited to text-based communication only
- Historical data constraints may affect trend analysis

## Future Enhancements
1. Advanced NLP models for better sentiment accuracy
2. Integration with other employee data sources
3. Real-time monitoring and alert system
4. Enhanced visualization and reporting tools

---
*Note: This analysis is meant as a decision support tool and should be used in conjunction with other HR metrics and personal interaction with employees.*