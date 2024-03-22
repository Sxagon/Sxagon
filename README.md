<h1>Hello 👋</h1>
<h3 style="margin-top: -20px;">My name is Mike and I am a fullstack developer since 2019</h3>

<br>

```js
import { Profile, Language } from '@sxagondev/identity';

export const Sxagon : Profile = {
  name: "Michal",
  username: "Sxagon",
  programmingLanguages: [
    { language: "PHP", proficiency: "High", description: "Just laravel with inertia" },
    { language: "TypeScript", proficiency: "Medium" },
    { language: "Java", proficiency: "Very low" },
    { language: "Python", proficiency: "Medium" },
    { language: "C#", proficiency: "Low" }
  ],
  spokenLanguages: [
    Language.English, 
    Language.Czech, 
    Language.Slovakia,
    Language.Polish
  ],
  jobInfo: {
    role: "CEO & Developer",
    company: "BatCore.net"
  },
  contacts: [
    { type: "email", contact: "contact@sxagon.eu" },
    { type: "discord", contact: "sxagondev", description: "Yeah, my tag is gone" },
    { type: "instagram", contact: "@sxagondev" }
  ]
}
```
