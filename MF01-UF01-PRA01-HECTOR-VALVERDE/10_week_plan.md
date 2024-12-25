```markdown
# My 10-Week plan

## Introduction

This is my **10-week plan** for the upcoming *SCRUM sprints*.

### Key Points:

1. Focus over the next 10 weeks on **learning and improving**.
2. Read and learn from **books and online resources**. SCRUM methodology.
3. Everyday check upon **progress and goals**. Adjust as needed.

> "Transcendence. Great teams have a purpose that is greater than the individual" - <i>Jeff Sutherland in "Scrum: The Art of Doing Twice the Work in Half the Time"</i>

Sample code block:

```

import { getImageUrl } from './utils.js';

function Profile({
  imageId,
  name,
  profession,
  awards,
  discovery,
  imageSize = 70
}) {
  return (
    <section className="profile">
      <h2>{name}</h2>
      <img
        className="avatar"
        src={getImageUrl(imageId)}
        alt={name}
        width={imageSize}
        height={imageSize}
      />
      <ul>
        <li><b>Profession:</b> {profession}</li>
        <li>
          <b>Awards: {awards.length} </b>
          ({awards.join(', ')})
        </li>
        <li>
          <b>Discovered: </b>
          {discovery}
        </li>
      </ul>
    </section>
  );
}

export default function Gallery() {
  return (
    <div>
      <h1>Notable Scientists</h1>
      <Profile
        imageId="szV5sdG"
        name="Maria Skłodowska-Curie"
        profession="physicist and chemist"
        discovery="polonium (chemical element)"
        awards={[
          'Nobel Prize in Physics',
          'Nobel Prize in Chemistry',
          'Davy Medal',
          'Matteucci Medal'
        ]}
      />
      <Profile
        imageId='YfeOqp2'
        name='Katsuko Saruhashi'
        profession='geochemist'
        discovery="a method for measuring carbon dioxide in seawater"
        awards={[
          'Miyake Prize for geochemistry',
          'Tanaka Prize'
        ]}
      />
    </div>
  );
}

```
| Sprint | Start Date |  End Date  | Main Goal |
|--------|------------|------------|-----------|
| 1      | 1-7-2025   | 1-11-2025  |
| 2      | 1-13-2025  | 1-18-2025  |
| 3      | 1-20-2025  | 1-25-2025  |
| 4      | 1-27-2025  | 2-1-2025   |
| 5      | 2-3-2025   | 2-8-2025   |
| 6      | 2-10-2025  | 2-15-2025  |
| 7      | 2-17-2025  | 2-22-2025  |
| 8      | 2-24-2025  | 3-1-2025   |
| 9      | 3-3-2025   | 3-8-2025   |
| 10     | 3-10-2025  | 3-15-2025  |

```
Project Roadmap
### Milestones
1. **React.js**: Fully understand all basics from React.js documentation and implement a simple React.js application.
2. **SCRUM/Agile**: Read and understand the SCRUM/Agile methodology. Memo the 4 pillars of SCRUM: Roles, Artifacts, Events, and Rules.
3. **Java**: Learn the basics of Java, including variables, data types, operators, control structures, functions, and object-oriented programming concepts.
4. **Team Project**: Create and develop an idea for a team project that incorporates the skills learned in the previous sprints.
5. **.**
