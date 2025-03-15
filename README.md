![Cover](https://github.com/DIARY7/DIARY7/blob/main/img/giphy.gif)
# 💻 Developper fullStack 🌐 !

🚀 **Développeur Junior**  

💡 Toujours en quête d'apprentissage et d'innovation, exploration du monde du développement web tout en m'intéressant aux **technologies intelligentes**.  

---

## ⚛️ Frontend Profile 
```jsx
const frontendProfile = {
  name: "Tsiory Diary Luc",
  stack: ["React", "JavaScript", "HTML", "CSS","Angular"],
  tools: [ "Tailwind", "Next.js"],
  learning: ["Gsap.js", "GraphQL", "Three.js"],
  mobile : ["React Native 📱"]
};

const showProfile = () => {
  console.log(`🚀 ${frontendProfile.name} - Stack: ${frontendProfile.stack.join(", ")}`);
  console.log(`🛠️ Outils : ${frontendProfile.tools.join(", ")}`);
  console.log(`📚 Apprentissage : ${frontendProfile.learning.join(", ")}`);
};

showProfile();
```
## ☕ Backend Profile 
```java
public class BackendProfile {
    private String name = "Développeur Backend";
    private String[] stack = {"Spring Boot", "Node.js", "PHP"};
    private String[] databases = {"MongoDB", "MySQL", "Firestore"};
    private String[] tools = {"Docker", "JPA", "Hibernate"};

    public void showProfile() {
        System.out.println("🚀 " + name + " - Stack: " + String.join(", ", stack));
        System.out.println("🛢️ Bases de données : " + String.join(", ", databases));
        System.out.println("🛠️ Outils : " + String.join(", ", tools));
    }

    public static void main(String[] args) {
        BackendProfile profile = new BackendProfile();
        profile.showProfile();
    }
}

```

