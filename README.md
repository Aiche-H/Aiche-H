# **Henrikki Gren**

**Web Development Maverick From Finland**

<details>
<summary><strong>Expand to see how i make a project awesome</strong></summary>
  
```javascript
class HenrikkiGren {
  constructor() {
    this.skills = {
      javascript: 'Crafting interactive experiences',
      html: 'Building the foundation',
      css: 'Styling with flair',
      sql: 'Querying the data'
    }
  }

  makeProjectAwesome(project) {
    project.isAwesome = true;
    console.log(`With my skills, I'm making ${project.name} an awesome project!`);
  }
}

class Project {
  constructor(name) {
    this.name = name;
    this.isAwesome = false;
  }

  addContributor(contributor) {
    if (contributor instanceof HenrikkiGren) {
      contributor.makeProjectAwesome(this);
    }
  }

  getStatus() {
    console.log(`${this.name} is ${this.isAwesome ? 'now an awesome' : 'still not an awesome'} project.`);
  }
}

const myProject = new Project('the Project');
const henrikki = new HenrikkiGren();
myProject.addContributor(henrikki);
myProject.getStatus();
```
</details>

**Projects:**

  * I have my creativity captured in: [Github projects](https://github.com/Aiche-H?tab=repositories)

**Portfolio:**

  * Witness my web magic: [Here](https://aiche-h.github.io/Portfolio/)

**Contact:**

  * Ignite the collaboration spark: Reach out via my portfolio\!

**STATS**

![Aiche-H's GitHub stats](https://github-readme-stats.vercel.app/api?username=Aiche-H&show_icons=true&theme=tokyonight)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Aiche-H&show_icons=true&theme=tokyonight)
