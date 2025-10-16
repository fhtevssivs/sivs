# Aufgabenstellungen 1 - Cryptography

Willkommen zum praktischen Teil des Moduls. In der IT-Sicherheit ist die praktische Anwendung von Wissen ebenso entscheidend wie das theoretische Verständnis.

Dieser Aufgabenkatalog wurde entwickelt, um die in den Unterrichtseinheiten behandelten Konzepte aktiv anzuwenden und Ihr erlerntes Wissen zu festigen. Jede Aufgabe gibt Ihnen die Möglichkeit, sich tiefgehend mit einem zentralen Thema der Kryptographie und Datensicherheit zu befassen.

Durch die Bearbeitung dieser Aufgaben schlagen Sie die Brücke von der Theorie zur Praxis und schärfen die Fähigkeiten, die für eine erfolgreiche Tätigkeit im Bereich der Cybersicherheit unerlässlich sind.

## Disclaimer
Bitte kreuzen Sie die Aufgaben an, die Sie bearbeitet haben und zu deren Lösung Sie bereit sind, eine Präsentation im Unterricht zu geben. Die Präsentation kann in beliebiger visueller oder audiovisueller Form erfolgen (z. B. PowerPoint, Flipchart, Demo, Codebeispiel oder Programm).
Wichtig ist, dass Sie die Lösung verständlich vermitteln können.

## Hinweise:

* Es muss mindestens eine Aufgabe pro Unterrichtseinheit ausgewählt werden. Andernfalls gilt die Teilnahme am Praxisteil als nicht erbracht.
* Durch das Ankreuzen stimmen Sie zu, eventuell zur Präsentation Ihrer Lösung aufgerufen zu werden. Sollte dies der Fall sein und Sie nicht in der Lage sein, die Lösung vorzustellen, wird dies als negativer Versuch gewertet.
* Mehr Informationen auf Moodle unter "Information zum Teil 'Aufgabenkatalog'"

---

## Aufgaben:

### 1. Steganographie

**Aufgabe:** Recherchieren und wählen Sie ein digitales Steganographie-Tool aus dem Internet. Demonstrieren Sie die Funktionsweise dieses Tools zur Einbettung und Extraktion versteckter Informationen in digitalen Dateien. Erörtern Sie darüber hinaus Methoden zur Erkennung versteckter Informationen und stellen Sie die Grundlagen der Steganographie, inklusive Vor- und Nachteile, dar.

---

### 2. Hash-Funktionen und Integrität

**Aufgabe:** Erläutern Sie die Bedeutung von Hash-Funktionen in der Kryptographie und wie sie zur Sicherstellung der Datenintegrität beitragen. Erstellen Sie ein Beispiel, in dem Sie mithilfe einer Hash-Funktion (z. B. SHA-256) die Integrität einer Datei oder Nachricht überprüfen.

---

### 3. Hashing mit Salting und Peppering

**Aufgabe:** Beschreiben Sie den Begriff „Kollision“ im Kontext des Hashings und erläutern Sie das Konzept der Rainbow-Tabellen. Wie können Kollisionen oder Rainbow-Tabellen für einen Angriff verwendet werden? Erklären Sie, wie Salting und Peppering den Schutz von Hash-Werten erhöhen. Implementieren Sie ein Hashing-Beispiel unter Verwendung von Salting und optional Peppering.

---

### 4. Symmetrische Verschlüsselung

**Aufgabe:** Wählen Sie einen modernen symmetrischen Verschlüsselungsalgorithmus und erstellen Sie ein Codebeispiel, das zeigt, wie eine Information verschlüsselt und anschließend entschlüsselt wird. Erklären Sie das Prinzip des gewählten Algorithmus und mögliche Angriffsszenarien. Gehen Sie abschließend auf die Unterschiede zur asymmetrischen Verschlüsselung ein.

---

### 5. Asymmetrische Verschlüsselung

**Aufgabe:** Wählen Sie einen aktuellen asymmetrischen Verschlüsselungsalgorithmus und entwickeln Sie ein Codebeispiel zur Verschlüsselung und Entschlüsselung einer Nachricht. Erklären Sie die Funktionsweise des Algorithmus und potenzielle Angriffsmethoden. Vergleichen Sie dieses Verfahren mit der symmetrischen Verschlüsselung und beleuchten Sie die Unterschiede in der Anwendung.

---

### 6. PGP (Pretty Good Privacy)

**Aufgabe:** Erläutern Sie die Funktionsweise von PGP und seine typischen Einsatzgebiete. Erstellen Sie ein Schlüsselpaar und demonstrieren Sie die Anwendung von PGP zur Verschlüsselung, Entschlüsselung und Signierung von Nachrichten. Erklären Sie, ob es sich bei PGP um ein symmetrisches oder asymmetrisches Verfahren handelt und welche Vorteile es in der Praxis bietet.

---

### 7. PKI und Zertifikate

**Aufgabe:** Beschreiben Sie die Rolle einer Public Key Infrastructure (PKI) in der IT-Sicherheit. Erstellen Sie ein Zertifikat (z. B. über "Let's Encrypt" oder als Self-Signed-Zertifikat) und erklären Sie die Anforderungen und die einzelnen Bestandteile des Zertifikats. Diskutieren Sie, welche Bedeutung die Zertifikatsbestandteile für die sichere Kommunikation haben.

---

### 8. TLS (Transport Layer Security)

**Aufgabe:** Erklären Sie die Funktionen und den Nutzen von TLS. Integrieren Sie TLS in eine Beispielanwendung und erstellen Sie dazu ein kleines Codebeispiel. Verwenden Sie für die TLS-Integration das in Aufgabe 7 erstellte Zertifikat. Beschreiben Sie die Anforderungen und die einzelnen Schritte zur Implementierung.

---

### 9. CIA-Confidentiality, Integrity, Availability

**Aufgabe:** Definieren Sie die CIA-Triade (Confidentiality, Integrity, Availability) im Kontext der IT-Sicherheit. Erläutern Sie, wie kryptografische Verfahren helfen können, diese Ziele zu erreichen, und geben Sie zu jedem Ziel zwei bis drei konkrete Beispiele aus der Praxis.

---

### 10. Abhören von Verbindungen

**Aufgabe:** Erklären Sie, einige Möglichkeiten die existieren, um unverschlüsselte Verbindungen abzuhören und einige Methoden für das Abhören verschlüsselter Verbindungen angewendet werden können. Beurteilen Sie die Aussage: „Ein geschlossenes Schloss in der Browserleiste bedeutet, dass die Verbindung sicher ist und die besuchte Domain authentisch ist.“