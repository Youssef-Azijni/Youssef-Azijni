```
public class Youssef-Azijni extends GitHubUser {

  public GekkeGlenn() {
    super("Youssef-Azijni", "Netherlands");

    this.addTopLanguages("PHP", "Java")
    this.addLanguage("html", "css", "javascript", "nodejs");
    this.AddFrameWorks("Laravel", "Tailwindcss");
  }
}

public abstract class GitHubUser {

  private final String name;
  private final String country;

  private ArrayList<String> topLanguages = new ArrayList<>();
  private ArrayList<String> languages = new ArrayList<>();
  private ArrayList<String> frameWorks = new ArrayList<>();

  public GitHubUser(String name, String country) {
      this.name = name;
      this.country = country;
  }

  public void addTopLanguages(String... topLanguages) {
    this.topLanguages.addAll(topLanguages);
  }

  public void addLanguage(String... language) {
    this.languages.addAll(language);
  }

  public void addFrameWorks(String... frameWorks) {
    this.frameWorks.addAll(frameWorks);
  }
```
