# Automated Analysis Report for Happiness.csv

## Summary
{'columns': ['Country name', 'year', 'Life Ladder', 'Log GDP per capita', 'Social support', 'Healthy life expectancy at birth', 'Freedom to make life choices', 'Generosity', 'Perceptions of corruption', 'Positive affect', 'Negative affect'], 'data_types': {'Country name': dtype('O'), 'year': dtype('int64'), 'Life Ladder': dtype('float64'), 'Log GDP per capita': dtype('float64'), 'Social support': dtype('float64'), 'Healthy life expectancy at birth': dtype('float64'), 'Freedom to make life choices': dtype('float64'), 'Generosity': dtype('float64'), 'Perceptions of corruption': dtype('float64'), 'Positive affect': dtype('float64'), 'Negative affect': dtype('float64')}, 'missing_values': {'Country name': 0, 'year': 0, 'Life Ladder': 0, 'Log GDP per capita': 28, 'Social support': 13, 'Healthy life expectancy at birth': 63, 'Freedom to make life choices': 36, 'Generosity': 81, 'Perceptions of corruption': 125, 'Positive affect': 24, 'Negative affect': 16}, 'summary_stats': {'Country name': {'count': 2363, 'unique': 165, 'top': 'Argentina', 'freq': 18, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'year': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 2014.7638595006347, 'std': 5.059436468192795, 'min': 2005.0, '25%': 2011.0, '50%': 2015.0, '75%': 2019.0, 'max': 2023.0}, 'Life Ladder': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 5.483565806178587, 'std': 1.1255215132391925, 'min': 1.281, '25%': 4.647, '50%': 5.449, '75%': 6.3235, 'max': 8.019}, 'Log GDP per capita': {'count': 2335.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.399671092077089, 'std': 1.1520694444710216, 'min': 5.527, '25%': 8.506499999999999, '50%': 9.503, '75%': 10.3925, 'max': 11.676}, 'Social support': {'count': 2350.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.8093693617021277, 'std': 0.12121176420299144, 'min': 0.228, '25%': 0.744, '50%': 0.8345, '75%': 0.904, 'max': 0.987}, 'Healthy life expectancy at birth': {'count': 2300.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 63.40182826086957, 'std': 6.842644351828009, 'min': 6.72, '25%': 59.195, '50%': 65.1, '75%': 68.5525, 'max': 74.6}, 'Freedom to make life choices': {'count': 2327.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.750281908036098, 'std': 0.13935703459253465, 'min': 0.228, '25%': 0.661, '50%': 0.771, '75%': 0.862, 'max': 0.985}, 'Generosity': {'count': 2282.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.772129710780206e-05, 'std': 0.16138760312630687, 'min': -0.34, '25%': -0.112, '50%': -0.022, '75%': 0.09375, 'max': 0.7}, 'Perceptions of corruption': {'count': 2238.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.7439709562109026, 'std': 0.1848654805936834, 'min': 0.035, '25%': 0.687, '50%': 0.7985, '75%': 0.86775, 'max': 0.983}, 'Positive affect': {'count': 2339.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.6518820008550662, 'std': 0.10623970474397627, 'min': 0.179, '25%': 0.572, '50%': 0.663, '75%': 0.737, 'max': 0.884}, 'Negative affect': {'count': 2347.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.27315083084789094, 'std': 0.08713107245795021, 'min': 0.083, '25%': 0.209, '50%': 0.262, '75%': 0.326, 'max': 0.705}}}

## Story
The dataset 'Happiness.csv' provides a comprehensive view of various factors influencing the happiness and wellbeing of individuals across different countries, spanning the years 2005 to 2023. The dataset includes 2,363 records, covering 165 unique countries, showcasing the complexity and diversity of happiness metrics worldwide.

### Key Features of the Dataset

- **Country Representation**: The dataset captures information from a range of countries, with Argentina being the most frequently represented, appearing 18 times.

- **Temporal Range**: The data spans from 2005 to 2023, with a mean year of approximately 2014. The distribution of years indicates regular data collection and amounts to a diverse temporal perspective on happiness trends.

- **Happiness Indicator (Life Ladder)**: The primary measure of happiness in this dataset is indicated by the 'Life Ladder' score, which has a range from 1.281 to 8.019. The average score across all countries stands at 5.48, with a standard deviation of around 1.13, suggesting a moderate variation in reported happiness levels.

### Socioeconomic Factors Analyzed

1. **Log GDP per Capita**: The average log GDP per capita is 9.40, indicating a generally high economic performance among the surveyed countries. However, gaps in data highlight the need for careful interpretation, especially where missing values are significant (28 missing entries).

2. **Social Support**: An essential component of happiness, social support shows an average score of 0.81, reflecting the importance of community and relationships in enhancing wellbeing. 

3. **Healthy Life Expectancy**: The mean healthy life expectancy stands at 63.4 years, indicating variability in health outcomes across countries, potentially correlating with both happiness and economic factors.

4. **Freedom to Make Life Choices**: This metric averages 0.75, suggesting that many individuals feel they have significant freedom in making choices that affect their lives.

5. **Generosity and Perceptions of Corruption**: The low average of generosity (0.0001) may indicate economic constraints or cultural factors affecting willingness to give. Conversely, the perceptions of corruption average at 0.74, implies a moderate level of trust in governmental and institutional integrity.

6. **Affective States**: Positive affect scores average at 0.65, while negative affect scores average at 0.27, suggesting that individuals tend to report more positive experiences than negative, contributing positively to the overall happiness metrics.

### Missing Values and Their Implications

The dataset presents several missing values across key variables such as 'Log GDP per capita', 'Social support', and 'Healthy life expectancy'. Specifically:
- Healthy life expectancy has 63 missing entries, and generosity is notably missing data in 81 instances.
- The presence of these missing values must be considered when analyzing trends, as they could skew results if countries with extreme values are underrepresented.

### Conclusion

Overall, the dataset paints a revealing picture of the multifaceted nature of happiness. While economic indicators such as GDP and social factors, including support and personal freedom, play significant roles, the impact of perceived corruption and individual affective states cannot be overlooked. The presence of missing values cautions against drawing definitive conclusions without further investigation. Future analyses could focus on filling these gaps or employing imputation methods to enhance the robustness of the findings. 

This narrative forms a foundation for understanding and exploring the intricate relationships between various determinants of happiness, paving the way for more in-depth studies that could drive policy changes and improvements in global wellbeing strategies.

## Visualizations
![Visualization](Happiness\heatmap.png)
