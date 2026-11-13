# Demo de compres per a Daunis · v7

Prototip independent en català. Dades operatives fictícies, ERP i correu desconnectats. No s’envia cap correu ni es modifica cap sistema. Classificació i resposta predeterminades, sense model d’IA real. Persistència només al navegador.

## Quatre entrades

- **Avui:** cicle automàtic de reclamació, lectura de resposta, confirmació de data/preu/quantitat i tancament verificat. La comanda continua oberta fins a recepció física.
- **Bústia de compres:** 12 correus de mostra, classificació, vinculació i acció. Confirmacions, parcials, factures, documents, duplicats i excepcions.
- **Comandes:** cerca i filtres, línies, quantitats i recepcions, correu vinculat.
- **Més:** autonomia, límits, pausa, simulació de fallada ERP, registre d’accions, proveïdors, compres sota comanda i abast.

## Guió curt

1. A Avui, prémer **Simular cicle automàtic**. Es mostren els 6 passos sense aprovació d’enviament en mode automàtic.
2. Obrir **Veure correus i evidències**. Comparar abans/després i ACK simulat de l’ERP.
3. **Simular triaje de 12 correus**: amb les regles inicials, 7 casos segurs i 5 excepcions fictícies. No són resultats de Daunis.
4. Obrir el preu +7 %: el sistema no l’accepta i prepara una contraproposta editable.
5. A Més → Autonomia, provar observació, aprovació opcional, límit de dies i error de connector. Sense ACK no es tanca la reclamació; el reintent no reenvia el correu.

La demo pot il·lustrar un flux complet de compres, però la integració i l’autonomia real requereixen validar API de l’ERP, permisos, identitats, regles comercials i pilot mesurat. No és una promesa de precisió, estalvi ni viabilitat tècnica.

Logotip públic de daunis.es utilitzat només per a aquesta presentació. No és un producte oficial de Daunis. Pàgina pública amb noindex/nofollow, que no restringeix l’accés.
