![Eliana's Github Stats](https://github-readme-stats.vercel.app/api?username=cheese-curd&show_icons=true&theme=synthwave&count_private=true&custom_title=Eliana%27s%20Github%20Stats)
```hx
package Earth;

import Planets.Earth.Person;

class Eliana extends Person
{
	public static var _name = Person.setName("Eliana");
	public static var _pronouns = Person.setPronouns("She", "Her");
	public function new()
	{
		super.create();
		trace("Created Person named " + _name + " with prounouns " + _pronouns);
	}
}
```

```bash
09:14:33:919 Eliana.hx:12:,Created Person named Eliana with prounouns She/Her
 ```
