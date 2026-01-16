# Your README Content

## Về Tôi

```typescript
interface Developer {
  name: string;
  role: string;
  location: string;
  languages: string[];
  code: string[];
  askMeAbout: string[];
  technologies: {
    frontEnd: { js: string[]; css: string[] };
    backEnd: string[];
    mobileApp: string[];
    ai: string[];
    devOps: string[];
    databases: string[];
    misc: string[];
  };
  currentFocus: string;
  funFact: string;
  socialMedia: {
    facebook: string;
    linkedin: string;
    gitlab: string;
    github: string;
  };
}

const coDY: Developer = {
  name: "Võ Duy Bình",
  role: "Multi-talented Tech Professional",
  location: "Ho Chi Minh City, Vietnam 🇻🇳",
  languages: ["Vietnamese", "English"],
  code: ["JavaScript", "TypeScript", "Python", "Java", "C++", "Go"],
  askMeAbout: ["Web Dev", "AI/ML", "App Dev", "Digital Marketing", "Content Creation"],
  
  technologies: {
    frontEnd: {
      js: ["React", "Next.js", "Vue.js", "Angular", "Svelte"],
      css: ["Tailwind", "Bootstrap", "Material-UI", "Sass"]
    },
    backEnd: ["Node.js", "Express", "Django", "FastAPI", "Spring Boot"],
    mobileApp: ["React Native", "Flutter", "Swift", "Kotlin"],
    ai: ["TensorFlow", "PyTorch", "OpenAI", "LangChain", "Hugging Face"],
    devOps: ["Docker", "Kubernetes", "AWS", "Azure", "CI/CD", "Nginx"],
    databases: ["MongoDB", "PostgreSQL", "MySQL", "Redis", "Firebase"],
    misc: ["Git", "Figma", "Postman", "Selenium", "GraphQL"]
  },
  
  socialMedia: {
    facebook: "binhdzkosai18cm",
    linkedin: "bình-võ-duy-5a9891308",
    gitlab: "DYBInh2k5",
    github: "DYBInh2k5"
  },
  
  currentFocus: "Building AI-powered solutions & Growing my digital presence 🚀",
  funFact: "I turn coffee into code ☕ → 💻 → 🚀"
};
```
