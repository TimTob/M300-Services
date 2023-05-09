### **Erstelle ein Image**
```
docker build -t mein-image .
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](/Screenshots/Protokoll1.png)

### **Erstelle ein Container**
```
docker run -p 8080:8080 mein-image
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](/Screenshots/Protokoll2.png)

Schlussendlich sollte man unter http://localhost:8080/containers das hier sehen:
![Architecktur Docker](/Screenshots/Protokoll3.png)