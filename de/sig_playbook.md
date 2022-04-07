# SI playbook

## Umfang einer SIG

TensorFlow hostet *Special Interest Groups* (SIGs), um die Zusammenarbeit auf bestimmte Bereiche zu konzentrieren. SIGs tun ihre Arbeit in der Öffentlichkeit. Um beizutreten und einen Beitrag zu leisten, sehen Sie sich die Arbeit der Gruppe an und setzen Sie sich mit dem SIG-Leiter in Verbindung. Die Mitgliedschaftsrichtlinien variieren je nach SIG.

Der ideale Bereich für eine SIG trifft auf einen klar definierten Bereich, in dem die Mehrheit der Beteiligung aus der Community stammt. Darüber hinaus sollte es ausreichende Beweise dafür geben, dass es Mitglieder der Gemeinschaft gibt, die bereit sind, sich zu engagieren und einen Beitrag zu leisten, falls die Interessengruppe gegründet wird.

Nicht alle SIGs werden das gleiche Maß an Energie, Umfang oder Governance-Modellen haben, also erwarten Sie eine gewisse Variabilität.

Sehen Sie sich die vollständige Liste der [TensorFlow-SIGs an](https://github.com/tensorflow/community/tree/master/sigs) .

### Non-goals: What a SIG is *not*

SIGs sollen die Zusammenarbeit bei gemeinsamer Arbeit erleichtern. Ein SIG ist also:

- *Kein Support-Forum* : Eine Mailingliste und eine SIG sind nicht dasselbe.
- *Nicht sofort erforderlich* : Zu Beginn eines Projekts wissen Sie möglicherweise nicht, ob Sie gemeinsame Arbeit oder Mitarbeiter haben.
- *Nicht umsonst* : Energie wird benötigt, um die Arbeit gemeinsam zu wachsen und zu koordinieren.

Unser Ansatz zur SIG-Erstellung wird konservativ sein – dank der Einfachheit, Projekte auf GitHub zu starten, gibt es viele Möglichkeiten, wie die Zusammenarbeit ohne die Notwendigkeit einer SIG erfolgen kann.

## SIG-Lebenszyklus

### Forschung und Beratung

Antragsteller von Gruppen sollten Nachweise für die Genehmigung sammeln, wie unten angegeben. Einige mögliche Wege, die in Betracht gezogen werden sollten, sind:

- Ein gut definiertes Problem oder eine Reihe von Problemen, die die Gruppe lösen würde.
- Beratung mit Community-Mitgliedern, die davon profitieren würden, wobei sowohl der Nutzen als auch ihre Bereitschaft, sich zu engagieren, bewertet werden.
- Bei bestehenden Projekten Belege aus Issues und PRs, dass sich die Mitwirkenden um das Thema kümmern.
- Mögliche Ziele, die die Gruppe erreichen kann.
- Ressourcenanforderungen für den Betrieb der Gruppe.

Auch wenn die Notwendigkeit einer SIG selbstverständlich erscheint, sind Forschung und Beratung dennoch wichtig für den Erfolg der Gruppe.

### Erstellen der neuen Gruppe

Die neue Gruppe sollte dem unten stehenden Prozess für die Gründung folgen. Insbesondere muss sie nachweisen:

- Ein klarer Zweck und Nutzen für TensorFlow (entweder um ein Teilprojekt oder einen Anwendungsbereich herum)
- Zwei oder mehr Mitwirkende, die bereit sind, als Gruppenleiter zu fungieren, Existenz anderer Mitwirkender und Nachweis der Nachfrage für die Gruppe
- Ressourcen, die anfänglich benötigt werden (normalerweise Mailingliste und regelmäßiger VC-Anruf.)

Die Genehmigung für die Gruppe wird durch eine Entscheidung des TF-Community-Teams erteilt, das als Betreuer des Tensorflow-/Community-Projekts definiert ist. Das Team wird bei Bedarf andere Interessengruppen konsultieren.

Bevor Sie mit den formellen Teilen des Prozesses beginnen, ist es ratsam, sich mit dem TensorFlow-Community-Team, community-team@tensorflow.org, zu beraten. Es ist sehr wahrscheinlich, dass Konversation und Iteration erforderlich sind, bevor die SIG-Anfrage fertig ist.

Die formelle Anfrage für die neue Gruppe erfolgt durch Einreichen einer Charta als PR bei tensorflow/community und Einfügen der Anfrage in die Kommentare zur PR (siehe Vorlage unten). Nach der Genehmigung wird der PR für die Gruppe zusammengeführt und die erforderlichen Ressourcen erstellt.

### Vorlagenanforderung für neue SIG

Diese Vorlage wird im Community-Repo verfügbar sein: [SIG-request-template.md](https://github.com/tensorflow/community/blob/master/governance/SIG-request-template.md) .

### Chartern

Jede Gruppe wird mit einer Satzung gegründet und unterliegt dem TensorFlow-Verhaltenskodex. Archive der Gruppe werden öffentlich sein. Die Mitgliedschaft kann entweder allen ohne Genehmigung offen stehen oder auf Anfrage verfügbar sein, solange die Genehmigung des Gruppenadministrators aussteht.

Die Satzung muss einen Verwalter ernennen. Neben einem Administrator muss die Gruppe mindestens eine Person als Leiter enthalten (dies kann dieselbe Person sein), die als Kontaktstelle für die Abstimmung mit dem TensorFlow-Community-Team dient.

Diese Charta wird zunächst an die Mailingliste der Gruppe gesendet. Das Community-Repository in der TensorFlow-GitHub-Organisation archiviert solche Dokumente und Richtlinien ( [Beispiel von Kubernetes](https://github.com/kubernetes/community) ). Da jede Gruppe ihre Praktiken und Konventionen entwickelt, erwarten wir, dass sie diese im relevanten Teil des Community-Repositorys dokumentiert.

### Zusammenarbeit und Inklusion

Obwohl es nicht vorgeschrieben ist, sollte die Gruppe die Zusammenarbeit über geplante Telefonkonferenzen oder Chat-Kanäle nutzen, um Besprechungen durchzuführen. Alle derartigen Treffen sollten auf der Mailingliste angekündigt und anschließend Notizen an die Mailingliste gesendet werden. Regelmäßige Treffen tragen dazu bei, die Verantwortlichkeit und den Fortschritt in einer SIG voranzutreiben.

Die Mitglieder des TensorFlow-Community-Teams werden die Gruppe proaktiv überwachen und zu Diskussionen und angemessenen Maßnahmen anregen.

### Starten

Erforderliche Aktivitäten:

- Benachrichtigen von allgemeinen TensorFlow-Diskussionsgruppen ( Discussion [@](https://groups.google.com/a/tensorflow.org/forum/#!forum/discuss) , [Developers@](https://groups.google.com/a/tensorflow.org/forum/#!forum/developers) ).
- Hinzufügen von SIG zu den Community-Seiten auf der TensorFlow-Website.

Optionale Aktivitäten:

- Erstellen eines Blogbeitrags für die TensorFlow-Blog-Community.

### Gesundheit und Beendigung von SIGs

Das TensorFlow-Community-Team wird sich nach besten Kräften bemühen, die Integrität von SIGs sicherzustellen. Von Zeit zu Zeit fordert sie den SIG-Leiter auf, einen Bericht über die Arbeit der SIG vorzulegen, der verwendet wird, um die breitere TensorFlow-Community über die Aktivitäten der Gruppe zu informieren.

Wenn eine SIG keinen nützlichen Zweck oder keine interessierte Gemeinschaft mehr hat, kann sie archiviert werden und ihren Betrieb einstellen. Das TF-Community-Team behält sich das Recht vor, solche inaktiven SIGs zu archivieren, um die Gesundheit des Projekts insgesamt zu erhalten, obwohl dies ein weniger wünschenswertes Ergebnis ist. Eine SIG kann sich auch für die Auflösung entscheiden, wenn sie erkennt, dass sie das Ende ihrer Nutzungsdauer erreicht hat.
