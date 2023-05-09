### **Erstelle ein Image**
```
docker build -t imagename .
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](Screenshots/Sichern1.png)

### **Erstelle ein Container**
```
docker run -p 8080:8080 imagename
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](Screenshots/Sichern2.png)

Schlussendlich sollte man unter http://127.0.0.1:8080 das hier sehen:
![Architecktur Docker](Screenshots/Sichern3.png)