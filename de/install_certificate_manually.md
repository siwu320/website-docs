---
title: "Manuelles Installieren des Zertifikates"
old_id: 12
---
Falls du Probleme hast, dich mit Akatsuki zu verbinden oder der Switcher installiert das Zertifikat nicht richtig, dann kannst du versuchen es manuell zu installieren.

### Anleitung
- Zuerst, lade das Zertifikat herunter, indem du [hierauf klickst](https://old.akatsuki.pw/akatsuki.crt)
- Dann öffne **certificate.cer**
- Klicke auf **Install certificate...**
- Klicke auf **Next**
- Wähle **Place all certificates in the following store** (Zweite Option)aus und klicke dann auf **Browse...**
- Ein neues Fenster wird sich öffnen. Wähle **Trusted root certification authorities** aus und klicke auf **Ok**
- Klicke auf **Next**
- Klicke auf **Finish**

### Falls alles andere fehlschlägt...
...kannst du versuchen alle Zertifikate von Akatsuki zu entfernen und wieder das Zertifikat zu installieren. Folge diesen Schritten:

- Drücke **Win+R**
- Tippe `mmc certmgr.msc` in die Box und drücke **enter** um Zertifikaten-Manager zu öffnen
- Wähle links **Trusted root certification authorities** aus
- Wähle rechts **Certificates** aus
- Nun müsstest du **[Akatsuki](https://onii-chan-please.come-inside.me/2020-05-05_10-02-46.png)** und ein paar **\*.ppy.sh** Eintrage in der Liste sehen. Wähle alle aus, **klicke die rechte Maustaste und klicke auf **Delete**
- Wähle alle positiven Optionen aus (Ok/Yes etc)
- Starte den Switcher erneut, klicke auf **Inspect** und wähle dann **Install certificate** aus. Klicke dann auf **Yes**
- Klicke auf **Test Akatsuki connection**. Du müsstest "OK" für jede Domain sehen.
**Falls das Inspect-Dialog in Ordnung ist, du dich jedoch nicht mit Akatsuki verbinden kannst, versuche osu! als Administrator zu starten**
