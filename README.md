# Wahlmodul: Internet of Things (IoT)

_Vorlesung zum fachwissenschaftlichen Modul **Internet of Things** im [Bachelorstudiengang Informatik](https://www.th-rosenheim.de/technik/informatik-mathematik/) an der [Hochschule Rosenheim](https://www.th-rosenheim.de)._				

## Empfohlene Literatur

- Perry Lea:  [Internet of Things for Architects: Architecting IoT solutions by implementing sensors, communication infrastructure, edge computing, analytics, and security](https://www.amazon.de/Internet-Things-Architects-communication-infrastructure/dp/1788470591/) (Englisch Edition)

- Andrew Minteer: [Analytics for the Internet of Things (IoT): Intelligent analytics for your intelligent devices](https://www.amazon.de/Analytics-Internet-Things-IoT-Intelligent/dp/1787120732/) (Englisch Edition)

## Inhalt

- **Einführung in das Internet der Dinge** ([Skript](/assets/00-einfuehrung/00-Einfuehrung.pdf), [Übung](https://github.com/hsro-inf-iot/00_uebung))

	Wir starten diese Vorlesung ganz klassisch. Zunächst klären wir alles Organisatorische, vor allem wie das PStA ablaufen wird. Danach geht es mit einen Überblick und Scope der Vorlesung weiter. Gerne erzähle ich etwas zur Geschichte vom Internet der Dinge (Internet of Things; IoT). Möchte gerne motivieren, warum das Internet der Dinge so hip ist, welche Beziehungen zum Industrial IoT oder auch zur Industrie 4.0 bestehen. Danach schauen wir uns im Detail ein paar Szenarien aus verschiedenen Bereichen an.

     In der Übung schauen wir, ob Azure-Cloud Zugriffe funktionieren. 

- **IoT Architekturen** ([Skript](/assets/01-vorlesung/01-Vorlesung.pdf), [Übung](https://github.com/hsro-inf-iot/01_uebung))

     Hier steigen wir nun ein in das Thema IoT. Wie ist IoT überhaupt definiert? Welche Elemente von IoT gibt es? Welche IoT Topologien  (Edge/Fog/Cloud) gibt es und wie genau unterscheiden sich diese?

     In der Übung werden wir versuchen ein IoT Entwickler Board ([MXChip](https://microsoft.github.io/azure-iot-developer-kit/)) zu verbinden.

- **Things und  Sensoren** ([Skript](/assets/02-vorlesung/02-Vorlesung.pdf), [Übung](https://github.com/hsro-inf-iot/01_uebung))

     Nachdem wir sehr high-level IoT Architekturen und Topologien betrachtet haben, tauchen wir hier tiefer in die Themen _Things_ (Dinge) und Sensoren ein. Dazu versuchen eine Kategorisierung zu erstellen.
     
     Als Übung beschäftigen wir uns nochmal mit der Übung aus der Vorwoche.

- **From Device to Cloud** ([Skript](/assets/03-vorlesung/03-Vorlesung.pdf), [Übung](https://github.com/hsro-inf-iot/03_uebung))

     Wir schauen darauf, wie Things kommunizieren und welche Protokolle es gibt, z.B. Bluetooth, BLE, ZigBee,6LowPan, LORA. Ausserdem schauen wir uns an, wie via IP/TCP Verbindungen vom Ding mit der Cloud kommuniziert werden kann, z.B. HTTP/ Rest, MQTT und CoAP.

     Wenn Zeit bleibt, müssen wir uns auch etwas mit dem Thema _Security_ beschäftigen.

     In der Übung lassen wir unseren MXChip mal via MQTT mit einem anderen Service kommunizieren.

- **IoT Analytics** ([Skript](/assets/04-vorlesung/04-Vorlesung.pdf), [Übung](https://github.com/hsro-inf-iot/04_uebung))

     Im nächsten Block geht es Richtung Analyse von Daten. Denn IoT ist schließlich mehr als nur Dinge, die verbunden sind. Denn was nützen uns die Dinge, wenn wir mit den Daten nichts machen. Also müssen wir uns dem Themen Big Data, Data Storage und Datenverarbeitung Konzepten beschäftigen.

     In der Übung arbeiten mit den Daten, die uns ein Python Skript und evtl. ein RPi liefert. Den wir auch noch so nebenbei aufsetzen.

- **Big Data in IoT** ([Skript RPi](/assets/05-vorlesung/src/README.md), [Übung](https://github.com/hsro-inf-iot/05_uebung))

     Wir schauen mal das Thema Big Data etwas genauer an. Es sollte jeder verstehen, was _Map-and-Reduce_ ist. In diesem Zusammenhang betrachten wir auch Data Ingest, Lamda Architekturen und Stream Processing.

     In der Übung werden wir uns definitiv noch etwas mit dem RPi beschäftigen.
     

- **Data Exploration** ([Skript](/assets/06-vorlesung/06-Vorlesung.pdf), [Übung](https://github.com/hsro-inf-iot/06_uebung))

    Nachdem wir nun gelernt haben, welche Möglichkeiten wir zum Verarbeiten von großen Datenmengen haben. Bietet es sich an, zu verstehen, wonach man in den Daten überhaupt sucht und was man erkennen kann (z.B. Muster, Anomalien, etc). Also Data Exploration und Visualisierung wird ein Thema sein. Ebenso Dashboard BI und Time Series Daten

     Zum Arbeiten mit Daten wurde ein [Jupyter Notebook](/assets/06-vorlesung/Data-Analytics%20with%20Python.ipynb) verwendet.

     In der Übung werden wir mal wieder den RPi hernehmen.

- **IoT Platformen** ([Skript](/assets/07-vorlesung/07-Vorlesung.pdf), [Übung](https://github.com/hsro-inf-iot/07_uebung))

     Wir starten diese Vorlesung mit einen Überblick über existierende IoT Cloud Platformen.
     Im 2. Teil der Vorlesung beschäftigen wir uns mit dem Design einer IoT Lösung. Hierzu nehmen wir exemplarisch Anforderungen auf und entwerfen eine IoT Lösungs-Architektur.

     In der Übung würde ich gerne in Gruppenarbeit das Thema Anforderungen und Architektur angehen.

- **Entwicklung einer IoT Lösung** ([Skript](/assets/08-vorlesung/08-Vorlesung.pdf), [Übung](https://github.com/hsro-inf-iot/08_uebung))

     Wir machen weiter mit der Entwicklung unserer IoT Lösung. In dem nächsten Schritt bauen wir eine Datenpipeline auf und schauen uns evtl. das Thema _Provisioning_ an.

     In der Übung geht es weiter mit der Gruppenarbeit.

- **Gastvortrag - Digitalisierung** ([Skript](/assets/09-vorlesung/09-Vorlesung.pdf), [Übung](https://github.com/hsro-inf-iot/09_uebung))

     Die Idee ist, dass wir uns anschauen, was das Thema _Digitaliserung_ für Firmen bedeutet.

- **Data Science in IoT** ([Skript](/assets/10-vorlesung/10-Vorlesung.pdf), [Übung](https://github.com/hsro-inf-iot/10_uebung))

     In dieser Vorlesung schauen wir uns die Daten mit der Data Science-Brille mal genauer an und wie wir die Analysieren und daraus lernen können, also: Maschinelles Lernen (ML) und relevante Themen, z.B. Feature Engineering, Missing Data, Metrics (ROC, Recall, …), Bias,.

     In der Übung nehmen wir uns Daten her und wenden darauf ein paar ML Ansätze an.

- **Intelligente Cloud und intelligente Edge** ([Skript](/assets/11-vorlesung/11-Vorlesung.pdf), [Übung](https://github.com/hsro-inf-iot/11_uebung))

     In der Vorlesung werden wir uns ein weiteres relevantes Thema ansehen: Wie werden Analysen verteilt? Was soll in der Cloud laufen, was kann man auf die Edge packen?
     Natürlich kommen wir hier am Thema Docker nicht vorbei. Also machen wir ganz geschwind eine kurze Einführung in Docker.

     In der Übung machen wir ein bischen Docker und so.

- **PStA Abschlusspraesentationen**

     PStA Praesentationen.



## Interessante Links:

- [IoT Geschichte kurz erklärt](https://www.youtube.com/watch?v=PYH27AnSiUU)
