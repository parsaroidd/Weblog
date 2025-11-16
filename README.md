# Weblog
starting to make my own Weblog, a thing i wanted to do for a long time;
first i'm working on MyAnimeList section, where can i have my own!
```
\\ first thing i learned was this cool automation:

        const start = document.getElementById("start");
        const consider = document.getElementById("consider");
        const complete = document.getElementById("complete");
        const c = document.getElementById("c");
        const drop = document.getElementById("drop");
        const d = document.getElementById("d");
        const onn = document.getElementById("onn");
        const o = document.getElementById("o");
        const plan = document.getElementById("plan");
        const p = document.getElementById("p");
        const warns = document.getElementById("warns");
        const sbm = document.getElementById("sbm");

\\ all this can fit into three lines, and thats beautiful!!!

const ids = ["start", "consider", "complete", "c", "drop", "d", "onn", "o", "plan", "p", "warns", "sbm"];
const el = {};
ids.forEach(id => {el[id] = document.getElementById(id);});
