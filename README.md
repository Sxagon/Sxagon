<h1>Hello 👋</h1>
<h3 style="margin-top: -20px;">My name is Michal btw.</h3>

<br>

```js
import { Profile, Language } from '@sxagondev/identity';

export const Sxagon : Profile = {
  name: "Michal",
  username: "Sxagon",
  programmingLanguages: [
    { language: "PHP", proficiency: "High", description: "Just laravel with inertia, omg" },
    { language: "TypeScript", proficiency: "Medium" },
    { language: "Java", proficiency: "Very low" },
    { language: "Python", proficiency: "Low" },
    { language: "C#", proficiency: "Low" }
  ],
  spokenLanguages: [
    Language.English, 
    Language.Czech, 
    Language.Slovakia,
    Language.Polish // hmm, i am not sure about that...
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
