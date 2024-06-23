---
marp: true
theme: default
paginate: true
footer: "Überblick über Geräte, BIOS, Partitionen, Betriebssysteme"
---

# Überblick über Geräte, BIOS, Partitionen, Betriebssysteme

## Einführung

Willkommen zu unserem Überblick über wichtige Konzepte rund um Computer und Betriebssysteme. Diese Präsentation richtet sich an Aktivist*innen mit unterschiedlicher technischer Vorbildung.

---

## BIOS

**Basic Input/Output System**

- Wird beim Starten des Computers geladen
- Startet den Bootloader des Betriebssystems
- BIOS-Einstellungen werden gewöhnlicherweise mit einer Tastenkombination beim Start erreicht.

- Image von BIOS-Settings

---

## UEFI

**Unified Extensible Firmware Interface**

- Der Nachfolger von BIOS
- Bietet eine grafische Benutzeroberfläche
- Bietet erweiterte Sicherheitsfunktionen wie Secure Boot
- Die allermeisten Computer der letzten 10 Jahre haben UEFI.
- Relevant: Manche Betriebssysteme benötigen LEGACY-BOOT (BIOS-Kompatibilität)

> **Grafik:** Bild von UEFI-Settings

---

## Partition

**Partitionierung von Festplatten**

- Unterteilung einer Festplatte in mehrere Abschnitte
- Ermöglicht die Installation mehrerer Betriebssysteme auf derselben Festplatte
- Beim Start des Systems wird zuerst die 1. Partition, die Boot-Partition geladen.

> **Grafik:** Beispiel einer Festplatte mit verschiedenen Partitionen: eine für das Betriebssystem, eine für Daten, eine für Backups.

---

## Betriebssystem

**Headline**

- Steuert die Hardware und führt Anwendungen aus
- Beispiele: Windows, macOS, Linux

---

## Bootprozess

**Vom Einschalten bis zum Betriebssystem**

1. **Power-On Self-Test (POST)**
2. **BIOS/UEFI Initialisierung**
3. **Bootloader laden (z.B. GRUB)**
4. **Betriebssystemkern starten**
5. **Systemdienste und Benutzeroberfläche laden**

> **Grafik:** Ein Flussdiagramm des Bootprozesses mit den einzelnen Schritten.

---

## Linux

**Ein freies und Open-Source-Betriebssystem**

- Beliebt bei Entwicklern und für Server
- Open-Source, Sicherheit kann nachvollzogen werden
- Verschiedene Distributionen wie Ubuntu, Fedora, Debian

> **Grafik:** Linux-Logo und Logos einiger populärer Distributionen (Ubuntu, Fedora, Debian).

---

## TPM

**Trusted Platform Module**

- Ein Sicherheitschip auf dem Mainboard
- Speichert kryptographische Schlüssel
- Unterstützt Funktionen wie Festplattenverschlüsselung und sichere Bootprozesse

> **Grafik:** Ein Bild eines TPM-Chips auf einem Mainboard und ein Diagramm, das die Nutzung von TPM für die Festplattenverschlüsselung zeigt.

---

## Q&A?