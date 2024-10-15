**Follow me on GitHub\!**

<a href="https://github.com/Aiche-H" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Follow%20on%20GitHub-21C699?style=for-the-badge&logo=GitHub" alt="Follow on GitHub Badge">
</a>

## **Henrikki Gren**

**Web Development Maverick**

```javascript
class HenrikkiGren {
  constructor() {
    this.skills = {
      javascript: 'Crafting interactive experiences',
      html: 'Building the foundation',
      css: 'Styling with flair',
      sql: 'Querying the data'
    };
  }

  makeProjectAwesome(project) {
    console.log(`With my skills, I'm making ${project.name} an awesome project!`);
  }
}

class Project {
  constructor(name) {
    this.name = name;
    this.contributors = [];
    this.isAwesome = false;
  }

  addContributor(contributor) {
    this.contributors.push(contributor);
    if (contributor instanceof HenrikkiGren) {
      contributor.makeProjectAwesome(this);
      this.isAwesome = true;
    }
  }

  getStatus() {
    if (this.isAwesome) {
      console.log(`${this.name} is now an awesome project!`);
    } else {
      console.log(`${this.name} is still not awesome.`);
    }
  }
}

// Create a new project
const myProject = new Project('My Awesome Project');

// Create a new HenrikkiGren
const henrikki = new HenrikkiGren();

// Add Henrikki to the project
myProject.addContributor(henrikki);

// Check the status of the project
myProject.getStatus();
````

* **Projects:**

  * I have my creativity captured in: [Github projects](https://github.com/Aiche-H?tab=repositories)

* **Portfolio:**

  * Witness my web magic: [Here](https://aiche-h.github.io/Portfolio/)

**Contact:**

  * Ignite the collaboration spark: Reach out via my portfolio\!

**Skills:**

| Skill | Level (out of 5) |
|---|---|
| ![HTML5 Badge](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) | ⭐⭐⭐⭐ |
| ![CSS3 Badge](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) | ⭐⭐⭐⭐ |
| ![JavaScript Badge](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) | ⭐⭐⭐ |
| ![MySQL Badge](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white) | ⭐⭐ |
