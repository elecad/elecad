<h2 align="center">About Me</h2>

```javascript
import {Human} from World
import {Developer} from Professions

const ElecAD: Human<Developer> = {
    life: {
        name: "Anton",
        telegram: "@gg_ad",
        age: 23,
        langs: ["Russian", "English", "German"]
    },
    coding: {
        langs: ["JavaScript", "TypeScript"],
        skills: {
            frontend: [Vue, React],
            backend: [ExpressJS, NestJS, PostgreSQL, TypeORM]
        },
        specialities: ["fullstack"],
        IDE: ["WebStorm", "VSCode"],
        device: [
            {
                name: "Honor D16 R5 5600H",
                type: "laptop",
            },
            {
                name: "Pixel 6",
                type: "phone",
            }
        ]

    }
}
```