# Kaplan-Meier_Plotly

Create Kaplan-Meier survival rate plots with Plotly

Interactive example:
https://nbviewer.jupyter.org/github/Ashafix/Kaplan-Meier_Plotly/blob/master/KaplanMeier_Plotly.ipynb

Usage
=====

```
plot = csv_to_kaplan_meier_plot('http://www-eio.upc.edu/~pau/cms/rdata/csv/survival/colon.csv', 'time', 'status', 'rx')
plotly.offline.iplot(plot)
```

![Link Text](https://raw.githubusercontent.com/Ashafix/Kaplan-Meier_Plotly/master/images/Colon.png)

```
plot = csv_to_kaplan_meier_plot('http://www-eio.upc.edu/~pau/cms/rdata/csv/survival/lung.csv', 'time', 'status', 'sex', translations={1: "male", 2: 'female'})`
plotly.offline.iplot(plot)
```

![Link Text](https://raw.githubusercontent.com/Ashafix/Kaplan-Meier_Plotly/master/images/Lung.png)




