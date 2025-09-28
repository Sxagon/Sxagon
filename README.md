```js
import { Profile, Language } from '@sxagondev/identity';

export const Sxagon : Profile = {
  realName: "Michal",
  username: "Sxagon",
  programmingLanguages: [
    { language: "PHP", proficiency: "High" },
    { language: "TypeScript", proficiency: "Medium" },
    { language: "Java", proficiency: "Very low" },
    { language: "Python", proficiency: "Low" },
    { language: "C#", proficiency: "Low" },
    { language: "N", proficiency: "Low rider"}
  ],
  spokenLanguages: [
    Language.English, 
    Language.Czech, 
    Language.Slovakia,
    Language.Polish, // hmm, i am not sure about that...
    Language.Ukraine
  ],
  jobInfo: {
    role: "CEO",
    company: "Batlify Internet s.r.o."
  },
  contacts: [
    { type: "email", contact: "lipka.michal@batlify.com" },
    { type: "discord", contact: "sxagondev", description: "Yeah, my tag is gone" },
    { type: "instagram", contact: "@sxagondev" }
  ]
}
```
