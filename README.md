<div align="center">

<h1>Hi <img src="images/Hi.gif" width="40px" />, I'm <a href="https://www.github.com/PaceSomesh">Pace</a>!</h1>
</div>

```java
  public class Schaefer extends Human implements Gamer, Developer {

	@Override
	public String getName() {
		return "Furkan";
	}
	
	@Override
	public List<String> getAliases() {
		return Arrays.asList("Schaefer", "My Name");
	}

        public Schaefer() {
        super("Schaefer", "Earth");

        this.addLanguage("Java", "Python", "Javascript", "Kotlin");
        this.addExperience("2 Years+(java)", "1year+(python)", "2months+(kotlin)", "1 year (js)");
     }
   }

	@Override
	public String aboutme() {
		return "I like to expose people lmao" +
		"\n" + "I like to code Java";
	}
    
	@Override
	public void codingStuff() {
		String[] learning = ["Java", "Node.js / Discord.js", "Python"];
		String tryingTo = "Coding unique plugins/clients and apps.";
	}
	
} 


public abstract class Human {

  @Getter private final String username;
  @Getter private final String country;

  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();

  public Human(String username, String placeilive) {
      this.name = username;
      this.country = placeilive;
  }

  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}
```

<!--START_SECTION:waka-->




<!--END_SECTION:waka-->
<div align="center">
	
[![schaefer's GitHub stats](https://github-readme-stats.vercel.app/api?username=schaeferrr&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&count_private=true)](https://github.com/schaeferrr) 
[![My used languages](https://github-readme-stats.vercel.app/api/top-langs/?username=schaeferrr&layout=compact&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&count_private=true&langs_count=6)](https://github.com/schaeferrr)
### Profile Visits 

![Visitors](https://komarev.com/ghpvc/?username=schaeferrr&color=blueviolet)
---

</details>

Discord: schaefer#0001

