# Build

install the pack CLI and build the app.

For details, see https://paketo.io/docs/


```bash
pack build demo-app 
```

Then check the app for CVEs:

```bash
trivy image demo-app:latest # --format template --template "@contrib/html.tpl" -o report.html 
```
