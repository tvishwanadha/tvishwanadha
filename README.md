```javascript
/**
 * @module teja.vishwanadha
 */

import { SoftwareEngineer } from "humans";

const me = new SoftwareEngineer({
    name: "Teja Vishwanadha",
    location: "Los Angeles, CA",
    pronouns: "he" | "him",
    recentTools: ["Python", "Docker", "Javascript"],
    // changing the following is left as an exercise for the reader
    works: {
        at: "Tempo",
        as: "Senior Staff Engineer",
        doing: [
            "technical strategy",
            "platform lead",
            "mentoring",
        ],
    },
});

export { me as default };
```