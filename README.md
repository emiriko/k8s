# Kubernetes

## Difference between Rolling Update and Recreate deployment strategy
The difference between the Rolling Update and Recreate Deployment strategies lies in the approach of both strategies in managing application updates. In Recreate Deployment, all pods from the previous version of the application are stopped simultaneously before new pods with the latest version are created. This means there is a period of downtime where the application is not available while the update process is in progress. Meanwhile, the Rolling Update strategy adopts a smoother approach by updating applications in stages. New pods with the latest version are created one by one while the old pods remain operational. This way, the application can still be accessed without any significant downtime.

