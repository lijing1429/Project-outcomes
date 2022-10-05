# NSS report

## Summary

- **Implement time**: 2022.09.13 - 2022.10.05 (**12** working days)
- **Tools**: Python (pandas,matplotlib, plotly), PowerBi, Excel
- **Requirements**: Display the concerns on each course
    * Beyond/below the benchmark 
    * Increase/decrease comparing with the prior year
    * The problem in each course
- **Challenges**
    * **Process data**: how to extract raw data from formatting excel sheets to the csv via **Pandas**
        * extract data from the row where 'Mearsure' located
        * compare data with different year and benchmark
    * **Data visualisation**: how to display the charts without signing in PowerBi, Excel
        * Download from [APP](https://appsource.microsoft.com/en-us/marketplace/apps?product=power-bi-visuals) and import into Powerbi 
        * Create the charts via [**matplotlib**](https://matplotlib.org/stable/tutorials/introductory/pyplot.html) then import to Powerbi
        * Completely create the chart via [**plotly**](https://plotly.com/python/)
        * Use the excel formula ([**Maxifs**](https://support.microsoft.com/en-us/office/maxifs-function-dfd611e6-da2c-488a-919b-9b6376b28883), [**Countifs**](https://support.microsoft.com/en-us/office/maxifs-function-dfd611e6-da2c-488a-919b-9b6376b28883))  to display the dynamic charts 
    
## Improvement
* More familiar with Pandas, PowerBi and excel formulas
* Learning with the data visualisation packages in Python, like matplotlib, plotly

## Outcomes
* Powerbi version
![Powerbi](/2022/Appendix/NSS-1.png)
![Powerbi](/2022/Appendix/NSS-2.png)

* Excel version
![Excel](/2022/Appendix/NSS-3.png)