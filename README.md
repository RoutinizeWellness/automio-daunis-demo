# Demo de compres per a Daunis · v11

Prototip independent en català. Dades fictícies. Sense connexió amb correu, ERP, Microsoft o IA reals. Cap enviament a Internet ni canvi en sistemes. Sense dependències de pagament.

## Novetat v11: Autopilot que arrenca sol

En obrir la demo s’inicia una simulació de 26 passos, uns 65 segons en velocitat normal. Arriben 10 correus ficticis, es vinculen, contrasten i deixen el resultat visible. Una confirmació rutinària produeix ACK i relectura ERP ficticis i una resposta simulada idempotent. Vuit excepcions deixen un esborrany i esperen una persona; un duplicat queda bloquejat. No s’executen cancel·lacions, substitucions, pagaments, recepcions ni canvis comercials fora de regla.

El panel Autopilot i Outlook comparteixen els mateixos missatges, esborranys, enviats simulats i traça. Es pot entrar a Outlook mentre el procés continua. Pausa i velocitat són opcionals; no cal tocar res per veure el recorregut. El final queda estable. Recarregar conserva l’estat i no duplica la resposta; “Tornar a veure-ho” reinicia amb confirmació. Aquest worker és una simulació dins del navegador, no un procés de servidor en producció.

## Novetat v10 conservada: una bústia completa de treball

Outlook passa de dos mini recorreguts a una bústia interactiva amb tres zones en PC i llista/detall en mòbil. 12 fils ficticis inicials: 10 a entrada, 1 a arxiu i 1 enviat simulat. Carpetes Entrada, Esborranys, Enviats simulats, Arxiu; vistes Seguiment, Revisió i Documents. Cerca dins de la carpeta per correu, comanda, article o document. Filtres de no llegits/adjunts, marcar llegit, seguiment, arxivar i restaurar.

Cada correu conserva l’original i mostra context de compra, evidència literal, línies contrastades, responsable i traça local. Vista representada d’adjunts ficticis, no PDFs realment llegits. Editor de resposta amb destinatari, assumpte i text editables; desar i reobrir a Esborranys; previsualització i confirmació explícita abans de registrar un enviament **només local** a Enviats. Crear un missatge nou també és només una simulació.

Casos: albarà parcial (80 demanades, 60 documentals, 20 pendents), confirmació rutinària dins de regla, canvi de preu +7,01 % i data, retard de 21 dies amb client aturat, factura amb 42 € de transport no previst, alternativa tècnica no aprovada, albarà sense comanda segura, duplicat, cancel·lació sense condicions confirmades, tarifa informativa, certificat pendent i resposta històrica simulada.

La confirmació rutinària pot simular regla, ACK i relectura en aquesta mostra. La resta bloqueja acceptacions automàtiques quan falta evidència. Un albarà no acredita recepció; no canvia estoc, no aprova factura ni pagament. Cap substitució, preu, data o cancel·lació real executats. Les assignacions no notifiquen persones.

## Guió curt de 5-7 minuts

1. Avisar: simulació independent, no una integració feta. **Autopilot arrenca sol**: deixar córrer el minut inicial, veure la rutina verificada i les excepcions. No cal prémer botons.
2. **Outlook → Albarà parcial**: obrir document, Línies, contrastar, preparar resposta i desar.
3. **Esborranys**: reobrir, editar, previsualitzar i confirmar la simulació. Veure-la a **Enviats simulats**.
4. Entrada: comparar **preu fora de regla**, **duplicat** i **sense comanda**. Mirar la traça i assignació de mostra.
5. **Recorreguts guiats v9**: conserva Confirmació rutinària i Albarà parcial, amb Reproduir o Següent pas.
6. **Avui → Reproduir els 5 casos**: conserva procés autònom, bloqueig de preu, duplicat, error ERP amb reintent i albarà parcial.

El PDF de la reunió ja lliurat continua sent vàlid: els dos recorreguts v9 són accessibles al botó “Recorreguts guiats v9”. La bústia v10 és una ampliació opcional del guió, no una connexió nova.

## Límits

Els conjunts d’Avui, Bústia de compres i Outlook són mostres independents; no comparteixen una base ERP. Els canvis d’Outlook es desen només al navegador (localStorage). Reiniciar la bústia reinicia també l’Autopilot perquè comparteixen estat; els altres casos d’Avui no es toquen. Reiniciar demo també reinicia la bústia i l’Autopilot. No publicar dades privades en aquest repositori públic.

Outlook és el client. La connexió real requereix validar tipus de bústia, Microsoft 365/Exchange, Microsoft Graph, permisos i consentiment amb IT. Mail.Read, Mail.ReadWrite i Mail.Send són permisos diferents. L’abast, la identitat d’enviament i el model delegat/d’aplicació no estan decidits. No s’ha concedit cap permís real.

Motor de processos i regles primer; IA com a complement. Les dades, toleràncies, resultats i indicadors no són dades de Daunis ni promeses de precisió, estalvi o viabilitat. Eines gratuïtes en aquesta demo no implica producció gratuïta. Logotip públic només per a la presentació; no és un producte oficial de Daunis. noindex/nofollow no restringeix accés.
