# m169

**Einfache Erklärung Docker:**--
Stell dir vor, du möchtest eine Anwendung auf deinem Computer ausführen, aber diese benötigt bestimmte Einstellungen oder Programme, die nicht auf deinem Computer installiert sind. Du könntest diese Dinge manuell installieren, aber das könnte zeitaufwendig sein und zu Konflikten mit anderen Anwendungen führen.

Hier kommt ein Docker-Container ins Spiel. Ein Docker-Container ist eine Art virtuelle Umgebung, in der du eine Anwendung ausführen kannst, ohne dass du sie auf deinem Computer installieren musst. Diese virtuelle Umgebung enthält alles, was die Anwendung benötigt, um ordnungsgemäß ausgeführt zu werden, einschließlich aller notwendigen Einstellungen und Programme.

Der Container ist wie ein kleines Paket, das alle erforderlichen Komponenten enthält und das einfach auf deinem Computer ausgeführt werden kann. Du musst nicht darüber nachdenken, ob das Programm mit anderen Programmen auf deinem Computer kompatibel ist, da es in seinem eigenen Container ausgeführt wird, der isoliert ist und keine Auswirkungen auf das Host-System hat.

Mit Docker-Containern kannst du schnell und einfach Anwendungen ausführen, testen und deployen, ohne dass du dich um die Installation oder Kompatibilität kümmern musst. Sie sind auch sehr flexibel und können auf verschiedenen Systemen und Plattformen ausgeführt werden, was sie ideal für Entwickler und IT-Teams macht, die Anwendungen auf verschiedenen Umgebungen bereitstellen müssen

**Erklärung Container**
Ein Container ist eine Art virtuelle Maschine, die Anwendungen in einer isolierten Umgebung ausführt. Container teilen sich den Kernel des Host-Betriebssystems, was bedeutet, dass sie weniger Ressourcen benötigen als traditionelle virtuelle Maschinen und schneller gestartet werden können. Container sind eine wichtige Technologie in der Anwendungsbereitstellung und DevOps-Infrastruktur, da sie die Portabilität und Skalierbarkeit von Anwendungen verbessern.

**Erklärung Docker-Image**
Ein Docker-Image ist ein Paket mit allem, was benötigt wird, um eine Anwendung in einem Container auszuführen. Es enthält den Anwendungscode, alle Abhängigkeiten und Konfigurationsdateien. Docker-Images werden mit einem Dockerfile erstellt, das die Anweisungen enthält, die Docker verwenden soll, um das Image zu erstellen.

**Erklärung Dockerfile**
Ein Dockerfile ist eine Textdatei, die die Anweisungen enthält, die Docker verwenden soll, um ein Docker-Image zu erstellen. Es enthält Anweisungen wie "FROM", "RUN", "COPY" und "CMD", die Docker dazu anweisen, Abhängigkeiten herunterzuladen, Anwendungscode hinzuzufügen und den Container zu konfigurieren.

*Erklärung Docker-Container**
Ein Docker-Container ist eine laufende Instanz eines Docker-Images. Ein Docker-Container enthält den Anwendungscode und alle Abhängigkeiten, die im Docker-Image definiert sind. Docker-Container sind in der Regel kurzlebig, was bedeutet, dass sie erstellt, ausgeführt und dann verworfen werden können.

**Erklärung Docker-Registry**
Eine Docker-Registry ist ein zentraler Speicherort für Docker-Images. Es ist ein Ort, an dem Entwickler Docker-Images hochladen und herunterladen können. Die am häufigsten verwendete Docker-Registry ist Docker Hub, aber es gibt auch andere öffentliche und private Registries, die verwendet werden können.
 

**Unterschied Virtualisierung und Cloud**
Virtualisierung ist das Bereitstellen von Leistung eines physischen Servers zu mehreren virtuellen Servern. (Virtuelle Maschinen)

Cloud-Computing umfasst auch Dienste wie Software as a Service (SaaS), Platform as a Service (PaaS) und Infrastructure as a Service (IaaS) und der physische Server steht beim Anbieter. (Speicher, Rechenleistung, Anwendungen)

**Vorteile von Containern**
Konsistenz: Container ermöglichen es, dass Anwendungen in einer konsistenten Umgebung ausgeführt werden können, unabhängig davon, auf welchem System sie ausgeführt werden. Dies stellt sicher, dass Anwendungen immer in der gleichen Umgebung ausgeführt werden, was Probleme mit der Kompatibilität und Stabilität vermeiden kann.

**Effizienz:** Container sind sehr leichtgewichtig und benötigen nur minimale Ressourcen, um ausgeführt zu werden. Dadurch können Anwendungen in Containern sehr effizient ausgeführt werden und der Bedarf an Ressourcen und Infrastruktur wird minimiert.

**Flexibilität:** Container sind sehr flexibel und können schnell und einfach erstellt, geändert und gelöscht werden. Dadurch können Entwickler und IT-Teams Anwendungen schnell anpassen und aktualisieren, um auf neue Anforderungen zu reagieren.


**Docker Website erreichbar machen:**
Ein Beispiel dafür, wie eine Container-Webseite erreichbar sein kann, ist die Verwendung von Docker-Containern in Verbindung mit einem Cloud-Hosting-Service wie Amazon Web Services (AWS). 

**Container löschen**
docker rm <Container-ID oder Container-Name>
  
**Docker NW:**
docker network create mynetwork
docker run -d --name mycontainer --network mynetwork myimage
docker network inspect mynetwork


