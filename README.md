1. create project via UI

2. show namespace argocd-demo

```bash
kubectl get all -n argocd-demo
```

3. create application whoami via UI

4. show application and project via kubectl

```bash
kubectl get appproject,application -n argocd | grep argocd-demo
```

4. delete project and application via UI

5. show 