### **Erstelle ein Image**
```
docker build -t my-mysql-image .
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](Screenshots/Volume1.png)

### **Erstelle des MySQL Container**
```
docker run --name my-mysql-container -p 3306:3306 -d my-mysql-image
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](Screenshots/Volume2.png)

### **Testen ob man sich mit dem Volume verbinden kann**
```
docker exec -it my-mysql-container mysql -u myuser -pmypassword mydatabase
```

Nachdem ausführen des Befehls:
![Architecktur Docker](Screenshots/Volume3.png)

### **Info**
Wenn du erfolgreich mit der Datenbank verbunden bist, bedeutet das, dass das Volume korrekt erstellt wurde und funktioniert.