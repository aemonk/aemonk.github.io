---
Layout: Beitrag
title: "Das Mangata Playbook - Teil 3: Tokenomiks"
Datum: 2022-06-23
Bild: "2022-02-14-the-mangata-playbook-part-3-cover.png"
author: "Mangata Team"
author-image: "mangata-team.png"
excerpt: "<p>Dieser Beitrag stellt Ihnen die Mangata X Tokenomiks vor. Zuerst geben wir Ihnen eine Zusammenfassung, dann gehen wir in die Tiefe, um unsere Gedanken dahinter zu erklären.</p>"
---

![Das Mangata Playbook Teil 3 Cover](2022-02-14-the-mangata-playbook-part-3-cover.png)

In diesem Beitrag stellen wir Ihnen die Mangata X Tokenomiks vor. Zuerst geben wir Ihnen eine Zusammenfassung, dann gehen wir in die Tiefe, um unser unsere Überlegungen dahinter zu erklären.

Sehen Sie sich das Video zu diesem Artikel an:
<iframe width="560" height="315" src="https://www.youtube.com/embed/kHyF0lyllyg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Tokenomiks Zusammenfassung

### Kürzel, Anfangsbestand, Harte Obergrenze

Das Kürzel des nativen Tokens von **Mangata X** wird **$MGX** sein. Zum TGE wird es einen **Gesamtvorrat von 1 Mrd. MGX** geben. Die Belohnungen werden bis zu einer **Obergrenze von 4 Mrd. MGX** ausgegeben, die frühestens in 5 Jahren erreicht wird. 80 % des endgültigen Angebots an Token sind für die Gemeinschaft reserviert.

### Funktionen

Die wichtigsten Funktionen sind:

- Verwendung bei Proof-of-Liquidity
- Algorithmischer Kauf und Verbrennung
- Governance: Verwaltung der diversifizierten Schatzkammer, der DEX-eigenen Liquidität, Liquiditätsanreize und Proof-of-Liquidity Whitelisting.

### Börsenprovision & Gebühren

**Die Börsengebühr** für den Handel beträgt 0,3%, wovon

- 0,2% gehen an die Liquiditätsgeber,
- 0,05% an die Schatzkammer,
- 0,05% werden für algorithmische Käufe und Verkäufe verwendet.

### Token-Verteilung

**80 % aller Token sind für die Community** bestimmt, wobei die Hauptanteile für die Sicherung des Netzwerks und für die Bereitstellung von Liquidität verwendet werden. Der Rest des Community-Anteils wird für die Unterstützung des Netzwerks über Crowdloans und andere Aktivitäten vergeben.

![Ein Tortendiagramm, das die endgültige Verteilung zeigt](allgemeine-token-verteilung.png)

### Emissionszeitplan

Der Zeitplan für die Tokenausgabe wird **frühestens nach 5 Jahren die Obergrenze** erreichen. Algorithmisches kaufen & verbrennen kann dieses Ereignis in die Zukunft verschieben. 

Nachfolgend finden Sie eine Projektion des zirkulierenden Angebots bis zum Erreichen der harten Caps:

![Eine Tabelle mit dem Emissionsplan](2022-02-14-emission-schedule.png)

Dieses Diagramm zeigt die prognostizierte Umlaufmenge:

![Ein Diagramm, das den Emissionsplan zeigt](mgx-schedule-chart.png)

Dieses Diagramm zeigt den voraussichtlichen Verteilungsplan:

![Ein Diagramm, das den Verteilungsplan zeigt](mgx-distribution-schedule.png)

## Deep Dive

Wie bauen Sie Tokenomiks auf? Wen belohnen Sie? Was packen Sie in die Utilities? In diesem Beitrag werden wir ein wenig tiefer in die Logik eintauchen, wie gut abgerundete Tokenomiks erstellt werden.

### "Was ist die Utility?"

Das ist eine der meistgehörten Fragen, wenn ein neuer Token eingeführt wird. Und sie macht Sinn: Jedes Projekt, Protokoll und jede Parachain löst spezifische Probleme. Für eine Parachain ist ein Token wie ein Medium zur Belohnung von Verhalten, dass das Netzwerk langfristig unterstützt. Der grundlegende Wert, den ein Token hat, wird durch seinen Nutzen bestimmt: Die Probleme, die er uns zu lösen erlaubt.

### Welche Probleme löst Mangata?

Lassen Sie uns einen Blick auf unsere Lösungen werfen, um ein Verständnis für den Nutzen von MGX zu bekommen:

- **Front-Running und MEV:** Dies sind einige der grundlegendsten Probleme, die wir lösen und die Mangata eine einzigartige Position in der Kryptowelt verschaffen. Wir haben eine funktionierende Lösung, die sofort einsatzbereit ist: [**Themis Protocol**](https://blog.mangata.finance/blog/2021-10-10-themis-protocol/)
- **Eigene Token, die im Staking gesperrt sind:** Dies ist ein Problem für jede Blockchain, aber für eine DeFi-orientierte Blockchain wäre es noch größer. Aus diesem Grund nutzen wir einen revolutionären Mechanismus, um Kapital für den Einsatz freizusetzen: [**Proof-of-Liquidity**](https://blog.mangata.finance/blog/2021-11-08-proof-of-liquidity/)
- **Liquiditätsmangel:** ein Problem, das jede DEX zu lösen hat und das mit **Liquidity Mining** zu einem großen Teil abgedeckt werden kann
- **Liquiditätsabwanderung:** Liquidität, die zwischen verschiedenen Pools hin- und hergeschoben wird oder die DEX ganz verlässt, ist ein häufiges Problem bei DEXes mit Anreizen. Um der Liquidität einen Grund zu geben, ruhiger zu bleiben, führen wir **Zeitanreize für Liquidity Mining und DEX-eigene Liquidität** ein
- **Inflation durch Anreizbelohnungen:** Viele Projekte leiden unter einer unklaren Inflationsstrategie. Bei Mangata erhalten Sie Vorhersehbarkeit: Wir führen eine **harte Obergrenze für das Token-Angebot** ein.
- **Negative Effekte durch abnehmende Anreize:** Eine harte Deckelung des Angebots führt in der Regel dazu, dass die Anreize abnehmen und das Kapital zum nächsten Problem abwandert. Da wir weiterhin Anreize für die Sicherung des Netzwerks im Proof-of-Liquidity benötigen, führen wir **algorithmisches kaufen & verbrennen ein, um kontinuierlich deflationären Druck aufzubauen**.

### MGX Utilities

Aus diesen Problemen und Lösungen ergeben sich die MGX-Utilities:

- **Verwendung im Proof-of-Liquidity Staking zur Absicherung des Netzwerks:** da diese Aktivität auch incentiviert wird, wird es eine starke Nachfrage geben, Liquidität für Collator Nodes bereitzustellen.
- **Liquiditätsbasisschicht:** Da sich viel Liquidität um MGX konzentriert, wird dies viele kurze Handelswege durch MGX bieten und eine Basisliquiditätsschicht schaffen.
- **algorithmisches kaufen & verbrenne:** um kontinuierlich Validierungsbelohnungen anzubieten und das Netzwerk gegen Frontrunner abzusichern, nehmen wir einen kleinen Teil der Börsenprovision, um MGX zu kaufen und zu verbrennen.
- **Governance:** Die Verwaltung der diversifizierten Schatzkammer und der DEX-eigenen Liquidität sowie der Anreize zum Liquiditätsabbau und der Validierungsbelohnungen wird eine politische Aufgabe sein, die eine Nachfrage nach liquiden MGX schafft.

### Verteilungstabellen: Die von Mangata geförderten Aktivitäten

Unser Token-Verteilungsdiagramm zeigt, welche Art von Aktivitäten wir im Netzwerk sehen wollen. Nach 5 Jahren werden 80% des endgültigen Angebots in den Händen der Gemeinschaft sein.

- **LP-Anreize:** Da Händler die wichtigste Interessengruppe sind, brauchen vor allem sie eine hohe Liquidität, um hohe Handelsvolumina zu erzielen. Aus diesem Grund bieten wir Anreize für die Bereitstellung von Liquidität in Höhe von 37,5% an.
- **Validation Rewards:** Die Absicherung des Netzwerks gegen Front-Running und MEV ist eines unserer wichtigsten Versprechen. Um sicherzustellen, dass es eine Menge Wettbewerb um diese Aktivität gibt, werden 30% der Token an Kollatoren und Delegierer gehen.
- **Crowdloan-Belohnungen:** Um uns zu helfen, einen Platz im Ökosystem zu sichern, erhalten Crowdloan-Belohnungen während der ersten 4 Slot-Perioden 8,25% des endgültigen Angebots
- **Ecosystem Development Fund:** Als Anreiz für alle möglichen Aktivitäten, die die Community zur Unterstützung des Netzwerks unternehmen kann, erhält der Ecosystem Development Fund 4,25% der Token, um Aktivitäten der Community zu belohnen.
- **Team:** Um die weitere Entwicklung der Parachain zu unterstützen, haben wir 11,5% für das Team reserviert.
- **Geldgeber:** Die frühen Unterstützer des Netzwerks werden 8,5% des endgültigen Angebots erhalten.


![Möge der Airwhale dich mit unendlichen Belohnungen segnen!](airwhale.jpg)

Möge der Airwhale dich mit unendlichen Belohnungen segnen!

---

[Original Artikel auf Englisch](https://blog.mangata.finance/blog/2022-02-13-the-mangata-playbook-part-3-tokenomics/)