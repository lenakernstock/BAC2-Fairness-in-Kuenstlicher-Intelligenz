# BAC2-Fairness-in-Kuenstlicher-Intelligenz

Dieses Notebook beinhaltet die empirische Untersuchung zu meiner Bachelorarbeit "Fairness in Künstlicher Intelligenz- Ursachen und Präventionsansätze für algorithmische Voreingenommenheit". <br>
Es wird ein möglicher Workflow für das Minimieren von Voreingenommenheiten in einem binären Klassifikator demonstriert, der vorhersagen soll, ob das jährliche Einkommen einer Person 50.000$ übersteigen wird. Das zu entwickelnde Model wird mit dem "Census Income" Datensatz trainiert und auf Voreingenommenheiten bezüglich des Geschlechtes untersucht.
Dazu wird zunächst der verwendete Datensatz bezüglich seiner Fairness analysiert und damit ein voreingenommener Klassifikator trainiert. Im Anschluss werden vier Methoden zur Mitigations von algorithmischer Voreíngenommenheit angewendet und deren Wirkung evaluiert: 
- Fairness durch Unbewusstsein (Pre-Processing)
- Reweighing (Pre-Processing)
- Adversarial Debiasing (In-Processing)
- Reject Option Classification (Post-Processing)

Der Einsatz verschiedener Fairnessmetriken und der wiederholte Vergleich mit den „rohen“ Ergebnissen des Baseline Models halfen bei der Beurteilung der Wirksamkeit der jeweiligen Methode. Die letzten drei Mitigationsmethoden und einige Fairnessmetriken wurden mittels der AI Fairness 360 Bibliothek implementiert.
