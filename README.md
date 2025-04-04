# Milestone 1: Mostrare la lista dei prodotti

1. Parti dall’array products fornito:
const products = [
  { name: 'Mela', price: 0.5 },
  { name: 'Pane', price: 1.2 },
  { name: 'Latte', price: 1.0 },
  { name: 'Pasta', price: 0.7 },
];

2. Crea un componente che mostra la lista dei prodotti.

3. Per ogni prodotto, mostra:
- Nome
- Prezzo

Obiettivo: Vedere un elenco leggibile di tutti i prodotti con nome e prezzo.

# Milestone 2: Aggiungere prodotti al carrello

1. Aggiungi uno stato locale addedProducts (inizialmente un array vuoto) per rappresentare i prodotti nel carrello.

2. Per ogni prodotto della lista, aggiungi un bottone "Aggiungi al carrello":
- Al click del bottone, usa una funzione addToCart per: aggiungere il prodotto al carrello se non è già presente, con una proprietà quantity = 1.
- Se il prodotto è già nel carrello, ignora l’azione.

3. Sotto alla lista dei prodotti, mostra una lista dei prodotti nel carrello se addedProducts contiene almeno un elemento.
Per ogni prodotto nel carrello, mostra:
- Nome
- Prezzo
- Quantità

Obiettivo: L’utente può aggiungere prodotti al carrello e vedere una lista dei prodotti aggiunti.