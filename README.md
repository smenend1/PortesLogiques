# Portes Lògiques Plus v4.2

Correcció específica de la impressió de fitxes docents.

## Canvi principal

- El botó **Imprimir fitxa / PDF** ja no depèn del `@media print` de tota la PWA.
- Ara obre una finestra nova amb només el contingut de la fitxa generada i un CSS mínim d'impressió.
- Això evita que la vista prèvia del PDF surti en blanc.

## Es manté de la v4.1

- Constructor avançat amb 4 entrades.
- 3 portes configurables.
- NOT configurables.
- Logigrama, taula de veritat i expressió automàtica.
- Mode docent i ajuda.

## GitHub Pages

Puja el contingut del ZIP al repositori: `index.html`, `manifest.json`, `sw.js`, `README.md` i la carpeta `assets/`.

Després de publicar, força actualització o esborra dades del lloc perquè el navegador no conservi versions anteriors.
