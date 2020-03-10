---
title: Einführung
type: cookbook
order: 0
---

## Codebuch vs. Leitfaden

Was unterscheidet das Codebuch vom Leitvaden? Warum ist es notwendig?

* **Besserer Fokus**: Im Leitfaden erzählen wir im Wesentlichen eine Geschichte. Jeder Abschnitt baut auf dem Wissen aus dem vorhergehenden Abschnitt auf und setzt dieses voraus. Im Codebuch kann und sollte jede Anleitung für sich allein stehen. Das bedeutet, dass sich die Anleitungen auf einen bestimmten Aspekt von Vue konzentrieren können, anstatt einen allgemeinen Überblick geben zu müssen.

* **Mehr Tiefgang**: Um zu vermeiden, dass der Leitfaden zu lang wird, versuchen wir, nur die einfachsten möglichen Beispiele aufzunehmen, um Ihnen das Verständnis der einzelnen Funktionen zu erleichtern. Dann machen wir weiter. Ins Codebuch können wir auch komplexere Beispiele aufnehmen, die die Funktionalitäten auf interessante Weise kombinieren. Jede Anleitung kann auch so lang und detailliert sein, wie es nötig ist, um ihre Nische voll auszuschöpfen.

* **JavaScript beibringen**: Im Leitfaden gehen wir davon aus, dass Sie mindestens eine gewisse Vertrautheit mit ES5-JavaScript haben. Wir werden dort zum Beispiel nicht erklären, wie `Array.prototype.filter` in einer berechneten Eigenschaft, die eine Liste filtert, funktioniert. Im Codebuch können jedoch wesentliche JavaScript-Funktionen (einschließlich ES6/2015+) untersucht und erklärt werden, wie sie uns helfen, bessere Vue-Anwendungen zu erstellen.

* **Das Ökosystem erkunden**: For advanced features, we assume some ecosystem knowledge. For example, if you want to use single-file components in Webpack, we don't explain how to configure the non-Vue parts of the Webpack config. In the cookbook, we have the space to explore these ecosystem libraries in more depth - at least to the extent that is universally useful for Vue developers.

<p class="tip">Bei all diesen Unterschieden ist zu beachten, dass das Codebuch immer noch __keine__ Schritt-für-Schritt-Anleitung ist. Für den größten Teil seines Inhalts wird von dir erwartet, dass du ein grundlegendes Verständnis von Konzepten wie HTML, CSS, JavaScript, npm/yarn, etc. hast.</p>

## Beiträge zum Codebuch

### Wonach wir suchen

Das Codebuch gibt den Entwicklern Beispiele, die sowohl gängige oder interessante Anwendungsfälle abdecken, als auch nach und nach komplexere Details erklären. Unser Ziel ist es, über ein einfaches, einleitendes Beispiel hinauszugehen und Konzepte zu demonstrieren, die in größerem Umfang anwendbar sind, sowie einige Vorbehalte gegenüber dem Ansatz.

Wenn du daran interessiert bist, einen Beitrag zu leisten, initiiere bitte die Zusammenarbeit, indem du eine Ausgabe unter dem Tag **cookbook idea** mit deinem Konzept einreichst, damit wir dich zu einem erfolgreichen Pull-Request bringen können. Nachdem Ihre Idee angenommen wurde, folge bitte so weit wie möglich der untenstehenden Vorlage. Einige Abschnitte sind erforderlich, andere sind optional. Die Einhaltung der numerischen Reihenfolge wird dringend empfohlen, ist aber nicht erforderlich.

Anleitungen sollten generell:

> * ein konkretes, allgemeines Problem lösen
> * mit dem am einfachsten möglichen Beispiel beginnen
> * Komplexitäten nacheinander einbringen
> * auf andere Dokumente verlinken, anstatt Konzepte neu zu erklären
> * das Problem beschreiben, statt von Vertrautheit auszugehen
> * den Vorgang und nichtz nur das Endergebnis erklären
> * die Vor- und Nachteile Ihrer Strategie erklären, auch wann sie geeignet ist und wann nicht
> * gegebenenfalls andere Lösungen erwähnen, die eingehende Erklärung einer Anderen Anleitung überlassen

Wir bitten dich, der untenstehenden Vorlage zu folgen. Wir verstehen jedoch, dass es Situationen gibt, in denen du aus Gründen der Klarheit oder des Flusses zwangsläufig davon abweichen musst. So oder so sollten alle Anleitungen irgendwann die Feinheiten der nach diesem Muster getroffenen Wahl diskutieren, vorzugsweise in Form des Abschnitts über alternative Muster.

### Basisbeispiel

_notwendig_

1.  Formuliere das Problem in ein oder zwei Sätzen.
2.  Erkläre die einfachste mögliche Lösung in ein bis zwei Sätzen.
3.  Zeige ein kleines Codebeispiel.
4.  Erklären in einem Satz, was damit bewirkt wird.

### Einzelheiten über den Nutzen

_notwendig_

1.  Gehe auf häufige Fragen ein, die man beim Betrachten des Beispiels haben könnte. (Blockzitate eignen sich hervorragend dafür)
2.  Zeige Beispiele für häufige Fehler und wie sie vermieden werden können.
3.  Zeige sehr einfache Code-Beispiele von guten und schlechten Beispielen.
4.  Diskutiere, warum dies ein überzeugendes Beispiel sein kann. Links zur Referenz sind nicht erforderlich, aber erwünscht.

### Beispiele aus der Praxis

_notwendig_

Demonstriere den Code, mit dem ein gängiger oder interessanter Anwendungsfall möglich ist, entweder durch:

1.  ein paar wenige Beispiele für die Einrichtung, oder
2.  ein Codepen/JSFiddle Beispiel

Wenn du dich für Letzteres entscheiden, solltest du trotzdem durchgehen, was es ist und was es tut.

### Zusätzlicher Zusammenhang

_optional_

Es ist äußerst hilfreich, ein wenig über dieses Beispiel zu schreiben, wo es sonst noch Anwendung findet, warum es gut funktioniert, und dabei ein wenig Code durchzugehen oder den Lesern hier weiteres Lesematerial zu geben.

### Wann dieses Beispiel zu vermeiden ist

_optional_

Dieser Abschnitt ist nicht notwendig, aber sehr empfohlen. Er würde für etwas sehr simples, wie das Umschalten von Klassen aufgrund von  Zustandsänderungen, keinen Sinn ergeben, aber für fortgeschrittenere Beispiele wie Mixins ist er unerlässlich.

Die Antwort auf die meisten Fragen zu Softwareentwicklung lautet ["Es kommt drauf an!"](https://codepen.io/rachsmith/pen/YweZbG), dieser Abschnitt greift dies auf. Hier werden wir uns ehrlich überlegen, wann das Beispiel nützlich ist und wann es vermieden werden sollte oder wann ein anderes sinnvoller ist.

### Alternative Beispiele

_notwendig_

Dieser Abschnitt ist erforderlich, wenn du den obigen Abschnitt über die Vermeidung bereitgestellt hast. Es ist wichtig, andere Methoden zu erforschen, damit die Leser, denen gesagt wird, dass in bestimmten Situationen etwas ein Gegenmuster ist, nicht im Unklaren gelassen werden. Beachte dabei, dass das Web ein großes Gebilde ist und dass viele Menschen unterschiedliche Codebasisstrukturen haben und unterschiedliche Ziele lösen. Ist die Anwendung groß oder klein? Integrieren sie Vue in ein bestehendes Projekt, oder bauen sie von Grund auf neu auf? Versuchen ihre Benutzer nur ein Ziel zu erreichen oder viele? Gibt es viele asynchrone Daten? All diese Bedenken werden sich auf alternative Implementierungen auswirken. Eine gute Codebuchanleitung gibt Entwicklern diesen Kontext.

## Danke

Es braucht Zeit, einen Beitrag zur Dokumentation zu leisten, und wenn du dir die Zeit nimmst, einen PR für diesen Abschnitt unserer Dokumentation einzureichen, dann tust du dies mit unserer Dankbarkeit.
