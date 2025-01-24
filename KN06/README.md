# KN 06

## A) Installation App (50%)

![swagger](media/swagger.png)

![GetProducts](media/GetProducts.png)

![Collections](media/Collections.png)

### Reverse Proxy

Ein Reverse Proxy liegt vor mehreren Servern. Er nimmt die Pakete an inspektiert diese und leitet diese dann an den richtigen Server.

### Cloud-Init Probleme

Man sollte die Benutzerdaten für das Login nicht im Klartext ins File einfügen.

Unnötig dass das Proxy File zuerst im Home erstellt wird und danach kopiert wird.

## B) Vertikale Skalierung  (10%)

### Vorher

![Instance-typevorher](media/Instance-typevorher.png)

![storagevorher](media/storagevorher.png)

### Erklärung

In der Instanz unter Storage, findet man die aktuelle Disk.

Auf die Disk klicken.

![storage](media/storage.png)

Dann oben rechts unter Actions > Modify Volume kann man die Disk Grösse erhöhen

![Modifyvolume](media/Modifyvolume.png)

![changesize](media/changesize.png)

Um den Instanz Typ zu ändern muss man zuerst die Instanz stoppen.

Dann unter "Actions > Instance Settings > Change Instance Type" kann man den neuen Instanztyp auswählen.

![Instancesettings](media/Instancesettings.png)

![Changeinstancetype](media/Changeinstancetype.png)

### Nacher

![Storagenacher](media/Storagenacher.png)

![Instance-typenacher](media/Instance-typenacher.png)

## C) Horizontale Skalierung (20%)

Um die Webserver mit der URL ```app.tbz-m346.ch``` zu erreichen, müsste man einen CNAME RECORD erstellen und dort die bestehende URL von aws einfügen.

Hier sieht man noch, dass der Load Balancer funktioniert.

![Loadbalancer-working](media/Loadbalancer-working.png)
