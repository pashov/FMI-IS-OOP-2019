## Task - Melody

Създайте следната йерархия:

**Melody** - което представлява мелодия, която пази в себе си само име string name;
**Song** - песен която имплементира Melody =- float duration; string author;
**Mix** - имплементира Melody, с данни : vector<Melody*> tree; string frontCover;

Реализирайте сериализация и десериализация. В клас Микс създайте функции за добавяне на песен или микс
