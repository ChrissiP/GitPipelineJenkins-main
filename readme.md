# GitPipelineJenkins

Das `GitPipelineJenkins`-Repository enthält eine Jenkins-Pipeline, die verschiedene Stufen und Aktionen für CI/CD-Demonstrationszwecke durchführt.

## Übersicht

Die Pipeline führt die folgenden Hauptaktionen durch:

1. Code aus dem Repository auschecken.
2. "Version 1" in der Konsole ausgeben.
3. Simulierte Tests ausführen (aktuell nur ein Platzhalter).
4. "Version 2" in der Konsole ausgeben.
5. Einen Fehler in einer der Stufen simulieren.

## Voraussetzungen

- Jenkins-Server mit einem Agenten, der das Label "docker-agent" (oder ein entsprechendes Label, das Sie in Ihrem Jenkinsfile festgelegt haben) hat.
- Git-SCM-Plugin in Jenkins für das Polling des Repos.

## Installation und Verwendung

1. Klone dieses Repository auf Ihren Jenkins-Server oder einen anderen Ort, der von Jenkins aus erreichbar ist.
2. Erstellen Sie in Jenkins einen neuen Pipeline-Job.
3. Verweisen Sie in den Job-Einstellungen auf das Jenkinsfile in diesem Repository.
4. Konfigurieren Sie ggf. weitere Einstellungen wie SCM, Triggers usw.
5. Führen Sie den Job aus und überwachen Sie die Ausgabe.

