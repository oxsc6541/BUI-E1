***Maven- Gradle  Vergleich***

**Was einfacher war**: Maven lief bei mir viel besser als erwartet. Sobald das exec-maven-plugin drin war, gab es keine Überraschungen mehr!Ein Befehl, ein Ergebnis. Die XML-Syntax ist zwar geschwätzig, aber dafür gut strukturiert, man sieht sofort, wo was hingehört.

**Deutlich schwieriger**:Gradle hat mir spürbar mehr Steine in den Weg gelegt. Drei Fehler in Folge (gradle nicht gefunden → Wrapper nutzen, JAVA_HOME fehlt → Umgebungsvariable setzen, Task 'run' not found → Plugin ergänzen), bevor überhaupt etwas lief. 
Das lag aber nicht direkt an Gradle als Tool, sondern daran, dass IntelliJ beim automatischen Anlegen weniger vorkonfiguriert hat als bei Maven. 

Beide Systeme können von Haus aus nur kompilieren, nicht ausführen. Erst ein Plugin (exec-maven-plugin / application bei Gradle) macht aus "Code bauen" ein "Code starten".
