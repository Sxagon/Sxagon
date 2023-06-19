```js
import { Profile, Language } from 'identity';

export const Naamloos : Profile = {
  name: "Mike",
  username: "Sxagon",
  programmingLanguages: [
    { language: "PHP", proficiency: "High", description: "Just laravel with inertia" },
    { language: "TypeScript/JavaScript", proficiency: "Medium" },
    { language: "Java", proficiency: "Medium" },
    { language: "Python", proficiency: "Medium" },
    { language: "C#", proficiency: "Low" },
  ],
  spokenLanguages: [
    Language.English, 
    Language.Czech, 
    Language.Slovakia
  ],
  jobInfo: {
    role: "Software Developer",
    company: "Seadragon.pro"
  }
}
```
