---
name: Template für neues Kubernetes System
about: Describe this issue template's purpose here.
title: Template für neues Kubernetes System
labels: ''
assignees: ''

---

- [ ] Neuen Ordner in `instances/production` kopieren
- [ ] Hostname definieren
- [ ] Hostname = `37-1.avidoc-r.atacamablooms.com` 
- [ ] Production Sink auf At-Road stellen
- [ ] Hostnames in Keycloak eintragen!
- [ ] Neuen DocType in Keycloak eintragen `doctype_37`
- [ ] System in entsprechendes Gateway eintragen
- [ ] Preprocessor-Liste auf neuen Systemtag umstellen. Z.B.: `37-1`
- [ ] Dataloader der Preprocessoren um neuen Systemtag erweitern: Z.B.: `37-1` 
- [ ] (Optional) Existiert bereits Certificate für Dokumentenklasse? [Beispiel](https://github.com/atacama-blooms-gmbh-co-kg/k8s-config-avidoc-r/blob/main/clusters/production/certificates.yaml#L152)
- [ ] (Optional) Existiert bereits Gateway für Dokumentenklasse? [Beispiel](https://github.com/atacama-blooms-gmbh-co-kg/k8s-config-avidoc-r/blob/main/clusters/production/gateway.yaml#L88)
- [ ] (Optional) Bei neu erstelltem Hostname muss IT-Service informiert werden, um die Adresse manuell in Firewall einzutragen!
