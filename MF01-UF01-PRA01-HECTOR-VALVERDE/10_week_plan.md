# My 10-Week Plan

## Introduction

This is my **10-week plan** for the upcoming *SCRUM sprints*.

### Key Points:

1. Focus on **learning and improving** over the next 10 weeks.  
2. Read and learn from **books and online resources** about the SCRUM methodology.  
3. Check daily on **progress and goals**, adjusting as needed.  

> "Transcendence. Great teams have a purpose that is greater than the individual."  
> — *Jeff Sutherland, "Scrum: The Art of Doing Twice the Work in Half the Time"*

---

## Sprint Schedule

| Sprint | Start Date  | End Date    | Main Goal                                                                           |
|--------|-------------|-------------|-------------------------------------------------------------------------------------|
| 1      | 01-07-2025  | 01-11-2025  | Practice and understand all React exercises. Create a React Vite App.               |
| 2      | 01-13-2025  | 01-18-2025  | Form a workgroup and implement the SCRUM/Agile methodology.                         |
| 3      | 01-20-2025  | 01-25-2025  | Work on Spring Boot and create a Maven project.                                     |
| 4      | 01-27-2025  | 02-01-2025  | Review Java skills and complete all course requirements.                            |
| 5      | 02-03-2025  | 02-08-2025  | Commit skills to Git to ensure no work is missed.                                   |
| 6      | 02-10-2025  | 02-15-2025  | Revisit SCRUM methodology and apply it in projects.                                 |
| 7      | 02-17-2025  | 02-22-2025  | Continue learning React and document knowledge.                                     |
| 8      | 02-24-2025  | 03-01-2025  | Dedicate the week to Spring Boot development.                                       |
| 9      | 03-03-2025  | 03-08-2025  | Review Java skills and update progress on MOOC.                                     |
| 10     | 03-10-2025  | 03-15-2025  | Finalize Git workflows and organize the next sprints and milestones.                |


---

## Project Roadmap

### Milestones

1. **React.js**: Fully understand the basics from the React.js documentation and implement a simple React.js application.  
2. **SCRUM/Agile**: Read and understand the SCRUM/Agile methodology. Memorize the 4 pillars of SCRUM: Roles, Artifacts, Events, and Rules.  
3. **Java**: Learn the basics of Java, including variables, data types, operators, control structures, functions, and object-oriented programming concepts.  
4. **Team Project**: Create and develop an idea for a team project that incorporates the skills learned in previous sprints.  
5. **Final Review**: Evaluate progress and prepare for all of the tests.

---

### Sample Code Block

```javascript
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
          <b>Awards:</b> {awards.length} ({awards.join(', ')})
        </li>
        <li>
          <b>Discovered:</b> {discovery}
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
        imageId="YfeOqp2"
        name="Katsuko Saruhashi"
        profession="geochemist"
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

### Useful Links

- [React Exercises](https://react.dev/learn/)
- [Java Documentation & Exercises](https://www.w3schools.com/java)
- [Revision & Correction by CHATGPT](https://chatgpt.com/)

### Additional Notes
- Ensure weekly commits to GitHub to showcase progress.
- Document learning and codebase using **Markdown** and **Quarto**.
