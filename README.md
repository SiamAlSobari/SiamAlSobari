## 👨‍💻 `SiamAlSobari.ts`

```typescript
class Developer {
  private readonly name: string;
  private readonly role: string;

  constructor() {
    this.name = "Siam Al Sobari";
    this.role = "Software Engineer";
  }

  public getProfile() {
    return {
      name: this.name,
      role: this.role,
      mission: "Crafting modern, scalable, and impactful applications. 🚀",
      techStack: {
        backend: ["NestJS", "Hono", "Node.js"],
        frontend: ["Vue.js", "TanStack Query", "TailwindCSS"],
        mobile: ["Flutter", "Dart"],
        database: ["PostgreSQL", "MySQL", "MongoDB"],
      },
      currentFocus: "Building clean architecture and optimizing performance.",
    };
  }

  public sayHi(): void {
    console.log(`Hello world! I'm ${this.name}.`);
    console.log("Feel free to check out my repositories below!");
  }
}

const me = new Developer();
me.sayHi();
console.table(me.getProfile());
```
