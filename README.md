- Hi, I’m the gobbler
- 👀 I’m interested in crypto and canucks hockey
- ⚡ Fun fact: crypto is neato
- here's a poem:
class CodeGobbler {
    username: string = "the_gobbler";

    constructor(public appetite: string) {
        console.log("Ready to gobble code!");
    }

    gobbleCode(codeSnippets: string[]): void {
        codeSnippets.forEach(snippet => {
            console.log(`Gobbling up this tasty code: ${snippet}`);
        });
    }

    celebrate(): void {
        console.log("All the code has been gobbled!");
    }
}

// Create an instance of CodeGobbler
let gobbler = new CodeGobbler("insatiable");

// Gobble up some code snippets
gobbler.gobbleCode([
    "console.log('Hello, world!');",
    "function add(a: number, b: number): number { return a + b; }",
    "let result: number = add(5, 3);"
]);

// Celebrate the feast!
gobbler.celebrate();
