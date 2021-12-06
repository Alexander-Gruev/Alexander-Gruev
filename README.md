### Hi there 👋

public class HelloGitHub {
   private String name = "Alexander Gruev";
   private int age = 21;
   private String city = "Sofia, Bulgaria";
  
   public Set<String> skills() {
    return Set.of("Web development", "OOP", "Design Patterns",
    "Communication", "Fast learning", "Attention to detail", "Hard working",
    "Strong academic background in mathematics", "Fluency in English");
   }
   
   public Set<String> technologies() {
    return Set.of("Java", "Spring", "MySQL", "Hibernate", "JavaScript");
   }
   
   public String education() {
    return "Java Web development | SoftUni | 2019-2021, " + 
    "Bachelor of Business Informatics and Communications | UNWE | 2019 – now";
   }
}
