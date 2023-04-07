# Quizoodle

Wenn man die App startet, wird schon die erste Frage angezeigt. Nun muss man eine Antwort auswählen, man kann nicht zur nächsten Frage, ohne eine Antwort zu wählen. Wenn man die Frage beantwortet hat, erfährt man noch nicht, ob man korrekt war oder nicht. Man wird also einfach zur nächsten Frage geleitet. Als letzte Frage wird noch eine knifflige Freitextantwort gezeigt. Auch bei dieser Frage habe ich Fehleingaben berücksichtigt, denn man kann nur Zahlen in das Textfeld eingeben. Sobald man diese Frage beantwortet hat, werden einem die Resultate angezeigt: Der Score wird als Zahl angezeigt und es wird ein prozentualer Anteil der richtigen Fragen errechnet. Wenn man nochmal spielen will, kann man einfach auf den Button «Try Again» klicken und die Seite wird neu geladen.

Um einen Button-Klick zu erkennen, habe ich EventListeners verwendet. Ein Beispiel dazu ist Folgendes:

submitButton.addEventListener("click", function)
 
Dieser EventListener führt bei einem Klick auf den Button die Funktion «results» aus
