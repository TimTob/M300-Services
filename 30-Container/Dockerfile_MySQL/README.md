### **Erstelle ein Image**
```
docker build -t my-mysql-server .
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](/Screenshots/Dockerfile1.png)

### **Erstelle ein Container**
```
docker run --name my-mysql-container -p 3306:3306 -d my-mysql-server
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](/Screenshots/Dockerfile2.png)

Schlussendlich sollte man unter Docker das hier sehen:
![Architecktur Docker](/Screenshots/Dockerfile3.png)