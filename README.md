# manipulation_du_dom
Manipulation du Dom 

Nous arrivons enfin au dernier chapitre d'apprentissage dans cette troisième partie consacrée au DOM ! C'en est d'ailleurs le cours le plus intéressant, mais aussi le plus long dans la mesure où il y a beaucoup de fonctions à retenir ; pas d'inquiétude à avoir cependant, car nous allons voir pas à pas comment manipuler le contenu, mais aussi la structure d'une page HTML !

Insertion de contenu
Enfin, nous y voilà ! Vous allez apprendre à insérer du contenu directement dans votre page web, grâce à jQuery. Petite note de vocabulaire, le faire d'insérer quoi que ce soit dans un document HTML se dit couramment "créer du contenu à la volée". Ne soyez donc pas étonné de voir cette expression lorsque l'on vous parle de jQuery ! :)

Nous allons voir comment insérer du contenu, ce qui est la base de la manipulation du code HTML. Sachez tout d'abord qu'il existe trois sortes de contenu :

le contenu textuel, ce qui correspond à du texte, tout simplement, sans fioritures telles que des balises ;

le contenu HTML, qui représente le contenu textuel avec les balises structurelles en plus ;

et le contenu des éléments de formulaire, qui est la valeur des différents champs de texte, de mot de passe, de textarea...

Ces différentes sortes de contenu ne se manipule pas tout à fait de la même manière, nous allons donc apprendre à utiliser les trois méthodes correspondantes, ainsi que quelques autres fonctions bien utiles, pour par exemple ajouter des éléments à une place bien précise.

Le contenu textuel
Commençons par le plus simple : le contenu textuel. Il n'est vraiment pas difficile de le manipuler, dans la mesure où il n'existe qu'une seule fonction pour le faire : text(). Cette méthode permet soit de récupérer le contenu textuel d'un élément s'il existe, soit de le modifier en donnant la nouvelle version en argument. Petite note à retenir, les balises données ne fonctionneront pas, car les chevrons (< et >) seront convertis automatiquement en entités HTML (respectivement &lt; et &gt;).

Rappel : en JavaScript, vous utilisez la propriété textContent pour le modifier.

Récupération du contenu
Pour récupérer le contenu d'un élément, il suffit d'utiliser la méthode text() tout simplement, ni plus ni moins. Elle ne retournera qu'une chaîne de caractère (string), qui contiendra le contenu textuel seulement : pas de balises ouvrantes ni fermantes, pas de chevrons HTML, juste du texte.

