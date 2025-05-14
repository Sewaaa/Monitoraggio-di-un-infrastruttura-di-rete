# Monitoraggio-di-un-infrastruttura-di-rete

Progetto sviluppato come tesi di laurea triennale in Informatica presso l'Università degli Studi di Salerno, in collaborazione con System Management S.p.A.

## 🎯 Obiettivo

Progettare e realizzare un'infrastruttura di rete con sistema di monitoraggio centralizzato, in grado di:
- Rilevare in tempo reale malfunzionamenti su host e servizi (HTTP, FTP)
- Fornire metriche dettagliate su CPU, RAM e disco
- Inviare notifiche automatiche via email in caso di criticità

## 🛠️ Tecnologie utilizzate

- **Nagios Core** – monitoraggio di host e servizi
- **NSClient++** – raccolta metriche su macchine Windows
- **Postfix** – invio notifiche via email
- **GNS3** – simulazione topologia di rete
- **FortiGate** – gestione firewall e segmentazione VLAN
- **Cisco Switch & Router** – configurazione trunk/VLAN/routing
- **VMware** – creazione di endpoint virtualizzati
- **MobaXterm** – gestione dispositivi via SSH

## 🧪 Architettura del progetto

1. **Fase di simulazione**: topologia testata in ambiente GNS3
2. **Implementazione fisica**: realizzata su dispositivi reali (switch/router/firewall)
3. **Servizi configurati**:
   - Server HTTP (IIS)
   - Server FTP (FileZilla Server)
4. **Monitoraggio attivo**: Nagios + NSClient++ + Postfix
5. **Testing**: simulazione di errori per validare le notifiche automatiche

## 📄 Contenuti del repository

- `Tesi.pdf`: documento completo della tesi

## 📬 Autore

**Samuele Sparno**  
Anno Accademico 2024/2025  
Università degli Studi di Salerno – Dipartimento di Informatica

--
