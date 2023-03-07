![Eliana's Github Stats](https://github-readme-stats.vercel.app/api?username=cheese-curd&show_icons=true&theme=synthwave&count_private=true&custom_title=Eliana%27s%20Github%20Stats)
```hx
package Planets.Earth;

import Planets.Earth.Person;

class Eliana extends Person
{
	public static var name = Person.setName("Eliana");
	public static var pronouns = Person.setPronouns(["She", "Her"]);
	public function new()
	{
		super();
		trace("Created Person named " + name + " with prounouns " + pronouns);
	}
}
```

```bash
09:14:33:919 Eliana.hx:12:,Created Person named Eliana with prounouns She/Her
 ```
