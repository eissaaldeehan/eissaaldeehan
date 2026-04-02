### Hi there 👋, I'm Eissa Aldeehan

```ts
type Developer = {
    name: string;
    role: string;
    education: string;
    stack: {
        core: string[];
        framework: string[];
        backend: string[];
        cloud: string[];
    };
};

function createDeveloper(): Developer {
    return {
        name: "Eissa Aldeehan",
        role: "Software Engineer",
        education: "Abdullah Al Salem University",
        stack: {
            core: ["TypeScript"],
            framework: ["React", "Next.js"],
            backend: ["Nest.js"],
            cloud: ["Vercel", "AWS"],
        },
    };
}

const me = createDeveloper();

export default me;

```
