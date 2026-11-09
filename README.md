# Premortem-Skill für Claude Code

Bevor du baust, lass Claude erzählen, woran deine Idee gescheitert ist.

Du beschreibst Claude deine Idee für einen Kurs, ein Angebot, eine App oder ein Tool. Claude tut so, als wäre sie 12 Monate nach dem Start schon gescheitert, sammelt alle Gründe dafür und macht mit dir daraus einen stärkeren Plan, solange du noch alles ändern kannst.

Ein Skill ist eine fertige Anleitung, die Claude Code von selbst befolgt, sobald sie zu deiner Anfrage passt.

Inspiriert von der Premortem-Methode des Psychologen Gary Klein (Gary Klein, „Performing a Project Premortem“, Harvard Business Review, 2007).

Ich bin Kerstin Schumacher von Sichtbar Unique und arbeite ohne Programmierkenntnisse nur mit Claude Code. Diesen Skill teile ich, weil er bei meiner eigenen Idee genau die Punkte aufgedeckt hat, an die ich gar nicht gedacht hatte.

## Was du bekommst

Claude geht mit dir 7 Schritte durch:

1. **Zuerst klärt Claude 4 Punkte:** was entstehen soll, für wen, bis wann und woran du merkst, dass es geklappt hat. Fehlt etwas Wichtiges, stellt dir Claude höchstens 2 Fragen. Alles andere nimmt Claude an und schreibt die Annahmen offen dazu.
2. **Das Scheitern in 2 bis 3 Sätzen:** wie es 12 Monate nach deinem Start aussieht, konkret und ohne Beschönigung, als wäre es schon passiert.
3. **Zuerst deine eigenen Gründe:** Du nimmst dir 2 bis 3 Minuten und schreibst auf, was dir selbst einfällt, auch das Unangenehme. Erst danach kommt Claude mit eigenen Gründen, damit deine Gedanken zuerst auf dem Tisch liegen. Willst du das überspringen, schreib einfach „überspringen“.
4. **Mindestens 12 Gründe,** jeder als kurze Geschichte in 1 bis 2 Sätzen. Claude schaut dabei überall hin: zu deinen Kund*innen, zu deiner Zeit und Energie, zu Geld und Preis, zu Technik und Plattformen und zu allem von außen wie Konkurrenz, neuen Werkzeugen oder Gesetzen. Hast du eigene Gründe aufgeschrieben, sind sie markiert.
5. **Eine Tabelle:** wie wahrscheinlich jeder Grund ist und wie schwer er wiegen würde. Daraus nennt Claude die 3 wichtigsten.
6. **Für jeden dieser 3 Gründe:**
   - eine Änderung, mit der du morgen anfangen kannst
   - ein Frühwarnzeichen, an dem du früh merkst, dass genau dieser Grund gerade eintritt
   - ein kleiner Test, mit dem du in höchstens 7 Tagen und mit wenig Geld prüfst, ob an dem Grund etwas dran ist
7. **Zum Schluss die eine Frage,** die nach allem am meisten zählt. Die beantwortest du, bevor du baust.

Das Ergebnis ist ein Denkanstoß, keine Beratung und keine Vorhersage. Entscheiden musst du selbst.

## So war es bei mir

Am 04.11.2026 habe ich den Skill auf meine eigene Idee angewendet. Ich wollte ein eigenes Tool für automatische DMs bauen und es mit einem Tarif für 0 € anbieten. An Server, Support, die Freigabe durch Meta für automatische Nachrichten und die DSGVO hatte ich gar nicht gedacht und auch nicht daran, dass Meta die Funktion selbst einbauen kann.

Und was kam dabei raus? Eine bessere Idee, nämlich kein eigenes Tool, sondern ein Claude-Skill auf bestehenden Tools.

Was bei deiner Idee rauskommt, siehst du erst, wenn du es ausprobierst.

## Wann du ihn nutzt

Immer bevor du baust, am besten genau dann, wenn du begeistert bist und am liebsten sofort loslegen würdest. Dann kannst du noch etwas ändern, solange es wenig kostet.

Normalerweise spielt Claude durch, wie es 12 Monate nach deinem Start aussieht. Willst du wissen, ob deine Idee auch in 5 oder 10 Jahren noch funktioniert, sag das einfach dazu, dann nimmt Claude diesen Zeitraum.

## So installierst du ihn

1. Klick oben auf den grünen Knopf „Code“ und dann auf „Download ZIP“. Entpack die Datei. Im entpackten Ordner `premortem-skill-main` liegt der Ordner `premortem`.
2. Leg den Ordner `premortem` in deinen Skill-Ordner. Im Zweifel nimmst du den für alle Projekte:
   - für alle Projekte: am Mac `~/.claude/skills/premortem/`, unter Windows `C:\Users\<dein Name>\.claude\skills\premortem\`
   - nur für ein Projekt: `<dein Projekt>/.claude/skills/premortem/`

   Das Zeichen `~` steht für deinen Benutzerordner. Am Mac ist der Ordner `.claude` versteckt, im Finder holst du ihn mit Cmd + Shift + Punkt hervor. Gibt es darin noch keinen Ordner `skills`, legst du einen neuen Ordner mit genau diesem Namen an. Die Datei `SKILL.md` muss direkt im Ordner `premortem` liegen.

   Einfacher geht es so: Lade die ZIP herunter und bitte Claude Code, den Ordner `premortem` daraus in deinen Skill-Ordner zu legen.
3. Schließ Claude Code und öffne es neu. Ab jetzt nimmt Claude den Skill von selbst, sobald du eine Idee prüfen lassen willst, zum Beispiel mit „prüf meine Idee“ oder „was könnte schiefgehen“. Du kannst ihn auch direkt rufen:

   „Mach ein Premortem zu meiner Idee: Ich will einen Kurs anbieten, in dem Yoga-Lehrer*innen ihre eigenen Reels erstellen.“

## Warum Claude so tut, als wäre es schon passiert

Bei der Frage „Was könnte schiefgehen?“ beschützt man seine Idee meistens, weil man sie ja gut findet. Ist die Idee aber schon gescheitert, muss sie niemand mehr verteidigen und es geht nur noch um die Frage, warum.

Premortem heißt wörtlich „vor dem Tod“. Du schaust dir also an, woran deine Idee gestorben ist, solange sie noch lebt.

## Lizenz

MIT. Nimm dir, was dir hilft. Du darfst den Skill auch an deine eigene Arbeit anpassen.

---

Claude und Claude Code sind Marken von Anthropic. Dieses Repo hat keine Verbindung zu Anthropic und ist nicht von Anthropic unterstützt.

[Impressum](https://sichtbarunique.com/impressum) · [Datenschutz](https://sichtbarunique.com/datenschutz)
