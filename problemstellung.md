# S235 Stahl vierkant Dokumentation

## Problemstellung

Die Problemstellung, die es in diesem Beispiel zu lösen gibt, ist wie folgt:

**Versandkostenregelung im OXID eShop für S235 Stahl vierkant**

Sie sind der Administrator eines OXID eShops und verkaufen S235 Stahl vierkant in verschiedenen Gewichtseinheiten. Sie möchten Versandarten und Versandkostenregeln für diese Produkte entsprechend den folgenden Vorgaben einrichten:

### Produkte

**S235 Stahl vierkant**

In den Gewichtseinheiten:
* 100 kg
* 200 kg
* 500 kg
* 1000 kg

Wählen Sie passende Preise selbst aus.

### Versandkostenregeln

**Standardversand innerhalb der EU:**
* Artikel < 1000 kg: 200 € Versandkosten pro Artikel
* Artikel = 1000 kg: 100 € Versandkosten pro Artikel
* Gesamter Warenkorb > 2000 kg: Keine Versandkosten

**Expressversand innerhalb der EU:**
* Pauschal: 300 € Versandkosten pro Artikel

**Standardversand weltweit:**
* Pauschal: 400 € Versandkosten pro Artikel
* Zusätzlich 1000 € Aufschlag auf den gesamten Warenkorb

### Schritte zur Umsetzung

**1. Erstellen der Produkte:**

Legen Sie die verschiedenen Gewichtseinheiten (100 kg, 200 kg, 500 kg, 1000 kg) des S235 Stahl vierkant im OXID eShop an. Bestimmen Sie die Preise zu den Gewichtseinheiten selbst, so dass diese Sinn ergeben.

**2. Einrichten der Versandarten:**

Richten Sie die notwendigen Versandarten ein.

**3. Definieren der Versandkostenregeln:**

Erstellen Sie Regeln für die Berechnung der Versandkosten basierend auf dem Gewicht und der Versandart. Stellen Sie sicher, dass Bestellungen über 1000 kg innerhalb der EU versandkostenfrei sind.

**4. Zusätzliche Kosten für den weltweiten Versand:**

Fügen Sie einen Aufpreis von 1000 € für alle weltweiten Sendungen hinzu.

[Zurück: Einleitung](README.md#einleitung) | [Inhaltsverzeichnis](README.md#inhaltsverzeichnis) | [Weiter: Artikel erstellen](artikel-erstellen.md)