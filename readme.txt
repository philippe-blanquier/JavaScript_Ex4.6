Traduire cette fonction fléchée en fonction nommée.


(name) => {
  `Bonjour, ${name} ! Comment vas-tu ?`;
}

Réponse:
-------
function hello(name)
{
  let answer = confirm(`Bonjour, ${name} ! Comment vas-tu ?`);
}