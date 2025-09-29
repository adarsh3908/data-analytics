# Batting Intent Analysis - IPL Cricket Data

This project provides comprehensive analysis of batting intent patterns in IPL (Indian Premier League) cricket matches using ball-by-ball delivery data. The analysis reveals how different batsmen approach various phases of the game and their overall batting strategies.

## Files
- `Batting Intent Analysis.ipynb` - Main Jupyter notebook with detailed analysis and visualizations
- `ipl_match_1473461_deliveries.csv` - Dataset containing ball-by-ball IPL match data

## 🔹 Project Overview

### **Objective**
Analyze batting intent and strategies in cricket by examining strike rates, boundary percentages, and performance patterns across different match phases and player profiles.

### **Key Questions Answered**
- How do batsmen adapt their playing style across different match phases?
- Which players are most aggressive vs defensive in their approach?
- How do teams perform collectively in different phases?
- What is the relationship between scoring rate and wicket-taking patterns?

## 🔹 Detailed Analysis

### **1. Data Structure**
- **Source**: IPL ball-by-ball delivery data
- **Key Fields**:
  - `batter`: Name of the batsman
  - `runs_batter`: Runs scored by batsman on each ball
  - `over`: Over number in the match
  - `team`: Batting team
  - `player_out`: Player dismissed (if any)

### **2. Phase Classification**
Cricket matches are divided into strategic phases:
- **Powerplay (Overs 1-6)**: Fielding restrictions, aggressive batting opportunities
- **Middle Overs (Overs 7-15)**: Consolidation phase, steady accumulation
- **Death Overs (Overs 16-20)**: Final push, maximum aggression required

### **3. Key Metrics Analyzed**

#### **Strike Rate**
- Runs scored per 100 balls faced
- Primary measure of batting aggression
- Formula: `(Total Runs / Balls Faced) × 100`

#### **Boundary Percentage**
- Percentage of balls that result in boundaries (4s and 6s)
- Indicates aggressive shot selection
- Higher percentage = more attacking approach

#### **Dot Ball Percentage**
- Percentage of balls faced without scoring
- Indicates defensive play or struggle against bowling
- Lower percentage = better run-scoring ability

#### **Batting Average**
- Runs scored per dismissal
- Measure of consistency and reliability
- Formula: `Total Runs / Number of Dismissals`

### **4. Analysis Components**

#### **Individual Player Analysis**
- Strike rate comparison across match phases
- Personal batting style identification
- Consistency patterns over different overs

#### **Team Performance Analysis**
- Collective batting strategies by teams
- Phase-wise team aggression levels
- Comparative team analysis

#### **Ball Outcome Analysis**
- Distribution of dot balls, singles, and boundaries
- Relationship between aggression and success
- Risk-reward assessment

#### **Progressive Analysis**
- Over-by-over run accumulation patterns
- Acceleration/deceleration trends
- Top performer consistency tracking

#### **Match Dynamics**
- Correlation between runs scored and wickets fallen
- Pressure points in matches
- Optimal scoring periods

#### **Multi-Dimensional Profiling**
- Radar chart visualization of player profiles
- Comprehensive metric comparison
- Batting style fingerprinting

## 🔹 Key Findings

### **Batting Patterns**
- **Powerplay Strategy**: Most aggressive phase with highest strike rates
- **Middle Overs Approach**: Consolidation with selective aggression
- **Death Overs Intensity**: Maximum risk-taking with varied success rates

### **Player Insights**
- **Aggressive Players**: High boundary percentage, moderate dot ball rate
- **Defensive Players**: Lower strike rates but better averages
- **Consistent Performers**: Balanced metrics across all phases

### **Team Strategies**
- **Top-order Focus**: Teams rely heavily on early wicket partnerships
- **Phase Adaptation**: Successful teams adapt strategy to match situation
- **Risk Management**: Balance between aggression and wicket preservation

## 🔹 Visualizations

1. **Grouped Bar Charts**: Strike rate comparison across phases
2. **Team Comparison Charts**: Phase-wise team performance
3. **Outcome Distribution**: Boundary vs dot ball percentages
4. **Line Graphs**: Over-wise progression analysis
5. **Dual-Axis Plots**: Runs vs wickets relationship
6. **Radar Charts**: Multi-dimensional player profiling

## 🔹 Technical Requirements

### **Python Libraries**
- **pandas**: Data manipulation and analysis
- **matplotlib**: Basic plotting and visualization
- **seaborn**: Statistical data visualization
- **numpy**: Numerical operations and calculations

### **Additional Libraries**
- **math**: Mathematical operations for radar charts

## 🔹 Usage Instructions

### **Setup**
1. Ensure Python 3.7+ is installed
2. Install required libraries: `pip install pandas matplotlib seaborn numpy`
3. Place `ipl_match_1473461_deliveries.csv` in the same directory as the notebook

### **Running the Analysis**
1. Open `Batting Intent Analysis.ipynb` in Jupyter Notebook/Lab
2. Run cells sequentially for complete analysis
3. Each cell contains detailed comments explaining the analysis

### **Data Requirements**
- **Minimum Sample Size**: Players with at least 5-10 balls faced for statistical significance
- **Data Quality**: Clean ball-by-ball data with consistent formatting
- **File Format**: CSV with required columns (batter, runs_batter, over, team, player_out)

## 🔹 Insights and Applications

### **For Teams and Coaches**
- **Player Selection**: Identify players suitable for specific match situations
- **Strategy Planning**: Develop phase-specific batting strategies
- **Opposition Analysis**: Understand opponent batting patterns and weaknesses

### **For Data Analysts**
- **Performance Metrics**: Comprehensive batting evaluation framework
- **Predictive Modeling**: Foundation for batting performance predictions
- **Comparative Analysis**: Benchmarking players against peers

### **For Cricket Enthusiasts**
- **Player Understanding**: Deep insights into batting styles and approaches
- **Match Analysis**: Better appreciation of strategic decisions
- **Historical Trends**: Evolution of batting strategies in T20 cricket

## 🔹 Future Enhancements

### **Advanced Analytics**
- **Predictive Modeling**: Forecast batting performance in upcoming matches
- **Machine Learning**: Cluster players into batting style categories
- **Time Series Analysis**: Track performance evolution over seasons

### **Extended Metrics**
- **Pressure Index**: Performance under high-pressure situations
- **Matchup Analysis**: Batsman vs specific bowler types
- **Situational Performance**: Performance in run chases vs setting targets

### **Interactive Features**
- **Dynamic Dashboards**: Real-time analysis during live matches
- **Player Comparison Tools**: Side-by-side metric comparisons
- **Custom Filtering**: Analysis by specific conditions (venue, opposition, etc.)

---

**Note**: This analysis provides insights into batting intent based on historical IPL data. The findings can be used for strategic planning, player evaluation, and deeper understanding of cricket dynamics in T20 format.