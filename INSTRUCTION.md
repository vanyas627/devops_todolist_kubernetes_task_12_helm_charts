# 1) How to validate the changes:

**Install dependency:**
     
    helm dependency update ./helm-chart/todoapp

**Install release:**

    helm upgrade --install todoapp ./helm-chart/todoapp

**Check the changes:**

    kubectl get all,cm,secret,ing -A
