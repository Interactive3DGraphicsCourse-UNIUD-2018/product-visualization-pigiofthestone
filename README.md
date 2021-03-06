# Pixar Lamp

![Pixar Lamp](../master/images/Pixar-Lamp.jpg)

## Scelta del modello

Per il progetto ho scelto la famosa lampada della Pixar. Ho iniziato prendendo un modello della lampada trovato su Sketchfab ma poi l'ho abbandonato a causa della cattiva modellazione di alcune parti di esso. Di conseguenza ho fatto una rapida ricerca su Google e ho trovato un modello con licenza CC sul sito [3D Export](https://it.3dexport.com/free-3dmodel-pixar-lamp-41625.htm). Questo modello non mi ha dato nessun problema di caricamento; l'unica pecca è che le coordinate UV erano completamente "sbagliate", infatti al momento dell'applicazione delle texture queste presentavano alcuni difetti non trascurabili sul realismo della lampada. Ho ovviato il problema rimappando le coordinate di texture con il software di modellazione 3D 3D Studio Max (Licenza gratuita per un anno per studenti).

## Struttura del progetto
Il progetto consta di:
- file [Acme inc](../master/Acme inc.html) che è il file finale che contiene il sito web stile eCommerce e il codice di Three.js con tutti i vari shaders;
- la cartella [lib](../master/lib) che contiene tutte le librerie;
- la cartella [model](../master/(../master/model) che contiene i modelli della lampada utilizzata;
- la cartella [logo](../master/logo) che contiene il logo del sito;
- la cartella [texture](../master/texture) che contiene tutte le texture utilizzate per i vari materiali della lampada;
- la cartella [envMap](../master/envMap) che contiene la environment map;
- le cartelle [css](../master/css) e [js](../master/js) che contengono i vari fogli di stile e le librerie utilizzate da Bootstrap per la costruzione del sito web.

## Implementazione

Ho iniziato il progetto prendendo come modello l'esempio visto a lezione dello [shading with textures](https://github.com/Interactive3DGraphicsCourse-UNIUD-2018/example-code/blob/master/l16-shadingWithTextures.html), ho implementato il loader per la lampada e poi mi sono concentrato sugli shader per ottenere un risultato il più realistico possibile. Fatto ciò, mi focalizzato sulla modifica runtime del materiale. Infine ho costruito un sito web di contorno per rendere il tutto più realistico a ciò che potrei incontrare sul web. Per questa parte mi sono affidato a [Bootstrap](https://getbootstrap.com/), un framework per applicazioni web, che mi ha semplificato molto il lavoro per la costruzione del sito.
Per tutti i dettagli di implementazione vi consiglio di leggere il mio [journey](../master/journey.md) dove avete anche i vari problemi che ho riscontrato durante la realizzazione del progetto.

## Scelta delle texture 

Per le texture mi sono affidato al sito [Share Allegorithmic](https://share.allegorithmic.com/), una piattaforma di libero scambio di texture e materiali costruiti con Substance Designer o con Bitmap2Material. La mia scelta è ricaduta su tre materiali differenti:
- Legno: la base in bamboo e il resto della lampada in legno verniciato. L'ho scelto per le caratteristiche molto diffusive del materiale.
- Plastica: scelto per le caratteristiche diffusive ma con presenza di riflessioni importanti su alcuni angoli di incidenza.
- Fibra di carbonio: scelta perché presenta sia caratteristiche diffusive che speculari.

## Future implementazioni

Un'ultieriore implementazione che vorrei aggiungere al mio progetto è la possibilità di cambiare il colore alla plastica e di fare in modo che la lampadina si accenda.
