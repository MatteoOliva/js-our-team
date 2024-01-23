# TRACCIA
Viene fornito un file js in cui è definito un array di oggetti che rappresentano i membri del team.
Ogni membro ha le informazioni necessarie per stampare le relative informazioni: Nome, Ruolo e Foto.
- MILESTONE 1:
  - stampare su console le informazioni di nome, ruolo e la stringa della foto
- MILESTONE 2:
  - stampare le stesse informazioni su DOM sottoforma di stringhe

- Consigli del giorno:
  - Ragioniamo come sempre a step.
  - Prima la logica in italiano e poi traduciamo in codice.
  - console.log() è nostro amico.


## SVOLGIMENTO

  const team = [
  {
    name: 'Wayne Barnett',
    role: 'Founder & CEO',
    image: 'wayne-barnett-founder-ceo.jpg',
  },
  {
    name: 'Angela Caroll',
    role: 'Chief Editor',
    image: 'angela-caroll-chief-editor.jpg',
  },
  {
    name: 'Walter Gordon',
    role: 'Office Manager',
    image: 'walter-gordon-office-manager.jpg',
  },
  {
    name: 'Angela Lopez',
    role: 'Social Media Manager',
    image: 'angela-lopez-social-media-manager.jpg',
  },
  {
    name: 'Scott Estrada',
    role: 'Developer',
    image: 'scott-estrada-developer.jpg',
  },
  {
    name: 'Barbara Ramos',
    role: 'Graphic Designer',
    image: 'barbara-ramos-graphic-designer.jpg',
  },
];'
### Milestone 1
- Stampare su console ogni l array di oggetti con un ciclo for
 - utilizzare variabile of (array) come condizione del for
  - stampare la variabile

### Milestone 2
- assegnare una variabile e creare un elemento HTML <ul>
- aggiungere alla <ul> gli elementi <LI> contententi ciascuno un oggetto dell' array