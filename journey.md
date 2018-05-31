# Journey - Pierluigi Della Pietra
## Venerdì 17 Maggio
- Iniziato il progetto
- Scelto il modello 3D
- Fatti degli aggiustamenti sul modello 3D con 3DS Max 2018(rimozione delle luci e dei muri)
- Impostata la pagina HTML dell'eCommerce
## Martedì 22 Maggio
>Modifiche
 - Aggiunto foglio di stile per il sito
 - Iniziata scrittura degli shader
 - Implementata il caricamento del modello 3D
>Problemi
 - Problemi di compilazione dello shader(RISOLTO)
 - Problema di caricamento del modello(RISOLTO)
## Mercoledì 23 Maggio
>Modifiche
- Scritto lo shader combinato con componente diffusiva e speculare
>Problemi
- Problemi di compilazione dello shader(RISOLTO)
- Problema sul modello: alcune parti sono in trasparenza da un lato e completamente opache dall'altro (in particolare base e parabola intorno alla lampadina
## Giovedì 24 Maggio
>Problemi
- Ricaricato il progetto di ieri, l'oggetto viene caricato ma non viene visualizzato (RISOLTO)
## Domenica 27 Maggio
>Modifiche
- Scelto un altro modello di lampada a causa della cattiva modellazione del precedente modello
- Modificato lo shader di partenza per includere la prima texture
>Problemi
- Problemi di compilazione dello shader(RISOLTO)
## Martedì 29 Maggio
>Modifiche
- Tentativo di implementare l'environment map con scarsi successi
>Problemi
- Lo shader non compila più a causa di un'estensione GL_OES_standard_derivatives (NON RISOLTO MA ABBANDONATO)
## Giovedì 31 Maggio
>Modifiche
- Diviso il modello in 3 parti: la base, la lampadina e il corpo
- Inserite due texture in legno una per la base(Bamboo) e una per il corpo(Legno classico)
- Creato uno nuovo shader per la base in bamboo
- Creato il materiale e l'envMap della lampadina per renderla trasparente
>Problemi
- Le texture sembrano troppo compresse (RISOLTO usando come valori di textureRepeat 0.01)
- La lampadina è effettivamente in trasparenza ma noto dei fenomeni di ombra che non riesco ad interpretare

