# arcgis-charts
Default charts for arcgis

# development

After making changes to the charts AND changing the version, run
```
Endre Chart version i Chart.yaml
helm package arcgis-charts
helm repo index .
git commit
git push
```

# test

