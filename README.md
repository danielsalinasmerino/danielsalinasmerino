<h2>Hi, I'm Dani! 👋</h2>
<img align='right' src="https://cdn.dribbble.com/users/2454048/screenshots/15340392/media/dd54aafd6e4ecf7aa325c94113a792f5.gif" style="width:160px; height:160px; border-radius:50%;" alt="Animated waves GIF">

<p>
  Software Developer at <em><a href="https://www.openbank.es/">Openbank</a></em> 
  <img src="https://media.tenor.com/Mi_aXRRAeaYAAAAM/money-donald-duck.gif" width="40" height="40" alt="Dancing lemon">
</p>

<p style="display: flex; align-items: center; gap: 10px; height: 50px;">
  <b>Let's connect!     </b>
  <a href="https://www.linkedin.com/in/danielsalinasmerino/">
    <img src="https://img.shields.io/badge/-danielsalinasmerino-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/danielsalinasmerino">
    <img src="https://img.shields.io/github/followers/danielsalinasmerino?label=follow&style=social" alt="GitHub Followers">
  </a> 
</p>

---

### About me...

I'm a software developer with a passion for crafting intuitive user experiences and scalable architectures. Outside of coding, you'll find me dancing, traveling, or making the best risotto in the galaxy! 😄👨🏻‍🍳

### Featured Projects

- 📽️ **My Own TMDB** (under construction 🏗️): A film discovery site inspired by [Letterbox](https://letterboxd.com/) and [Filmaffinity](https://www.filmaffinity.com/), providing detailed movie information. Built with data from [TMDB](https://www.themoviedb.org/). Check out the [GitHub Repo](https://github.com/danielsalinasmerino/movies-app).

---

### Profile

```typescript
// Developer profile
type Developer = {
  code: Array<string>; // Programming languages known
  tools: Array<string>; // Tools and frameworks used
  architectures: Array<string>; // Architectural patterns I'm comfortable with
  experienceYears?: number;
};

const daniDeveloper: Developer = {
  code: ["JavaScript", "TypeScript", "HTML", "CSS"],
  tools: [
    "React",
    "React Native",
    "Next.js",
    "React Query",
    "Axios",
    "CSS Modules",
    "Jest",
    "Lint",
  ],
  architectures: ["microservices", "hexagonal architecture", "atomic design"],
  experienceYears: 5,
};

// Personal details
type Person = {
  name: string;
  age?: number;
  gender?: "male" | "female" | "non-binary" | "other";
  hobbies?: Array<string>;
  skills?: Array<string>;
};

const daniPerson: Person = {
  name: "Daniel Salinas Merino",
  age: 30,
  gender: "male",
  hobbies: [
    "reading",
    "sports",
    "traveling",
    "dancing",
    "meditation",
    "cooking",
    "nature",
  ],
  skills: ["communication", "organization", "motivation", "problem solving"],
};

export const dani = { ...daniPerson, ...daniDeveloper };
```
