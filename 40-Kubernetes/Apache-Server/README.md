### **Erstelle Kubernetes Apache-Server**
```
kubectl apply -f Apache.yaml
```

So sollte es aussehen nachdem ausführen von "kubectl apply -f Apache.yaml":
![Architecktur Docker](/Screenshots/KuberApache1.png)

### **Lösche denn erstellten Apache-Server**
```
kubectl delete -f Apache.yaml
```

### **Info**
Nachdem ausführen des Befehls "kubectl apply -f Apache.yaml" kann man automatisch nach einigen Sekunden auf http://localhost:30080 zugreifen

Unter http://localhost:30080 findet man nun dies:

![Architecktur Docker](/Screenshots/KuberApache2.png)