# Week 2 — Distributed Tracing

I was able to complete all the required assessments without issue.

I added HoneyComb tracing and XRay. I comment the code of XRay, because of billing issues.


HoneyComb monitoring:
![HoneyComb Home page](assets/honeycomb-home.png)

Query:
![HoneyComb Qeury](assets/honeycomb-query.png)

XRay Group:
![XRay](assets/x-ray-group.png)

I was able to come up with a solution for XRay custom metadata:
![XRay Metadata](assets/xray-custom-metadata.png)

I added a rollbar to Backend:
![Rollbar](assets/rollbar.png)

I faced an issue of an error with 
```
@app.before_first_request
```
so I changed this line to a line provided by Rollbar directly:
```
with app.app_context():
```
