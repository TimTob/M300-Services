### **Erstelle ein Image**
```
docker build -t mein-image .
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](/Screenshots/ApacheServer1.png)

### **Erstelle ein Container**
```
docker run -d --name mein-container -p 8080:80 mein-image
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](/Screenshots/ApacheServer2.png)

### **Wichtig!**
Die drei Dateien müssen sich im selben Verzeichnis befinden und der Benutzer muss im selben Verzeichnis sein, um die Befehle erfolgreich auszuführen.

Schlussendlich sollte man unter http://localhost:8080 das hier sehen:

![Architecktur Docker](/Screenshots/ApacheServer3.png)