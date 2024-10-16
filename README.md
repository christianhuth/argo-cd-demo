1. create project argocd-demo via UI

2. show namespace argocd-demo

```bash
kubectl get all -n argocd-demo
```

3. create application whoami via UI

4. show application and project via kubectl

```bash
kubectl get appproject,application -n argocd | grep argocd-demo
```

5. delete a resource via UI

6. delete application via UI

7. show application and project via kubectl

```bash
kubectl get appproject,application -n argocd | grep argocd-demo
```

8. deploy project using kubectl

```bash
kubectl apply -f project.yaml
```

9. analyze project using UI

https://argocd.knell.it/settings/projects/argocd-demo

10. deploy the application using kubectl

```bash
kubectl apply -f argocd/application.yaml
```

11. deploy the app-of-app application

```bash
kubectl apply -f app-of-app.yaml
```

12. show applications and applicationset in UI

13. delete a whole application

14. enabled the Promlens chart in the Git repository

15. update the Promlens version

16. disabled the Promlens chart again

16. delete the app-of-app application from the ui

17. show namespace argocd-demo

```bash
kubectl get all -n argocd-demo
```
