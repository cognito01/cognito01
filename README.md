```ts
class Cognito {
  name: string = "Cognito";
  role: string = "JS/TS Developer";
  mission: string = "Building to make things better";

  constructor() {
    console.log(`👋 Hi, I'm ${this.name}`);
  }

  build(): string {
    return "🚧 Work in progress...";
  }
}

const dev = new Cognito();
dev.build();
```
