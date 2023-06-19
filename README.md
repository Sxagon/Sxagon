# I am a Software Developer
## Since 2019 

```js
import { Profile, Language, Contacts } from 'identity';

export const Sxagon : Profile = {
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
  },
  contacts: [
    { type: "email", contact: "contact@sxagon.eu" },
    { type: "discord", contact: "sxagondev", description: "Yeah, my tag is gone" },
    { type: "instagram", contact: "@sxagondev" }
  ]
}
```
