**Web Development Maverick From Finland**

<details>
<summary><strong>Expand to see how i make a project awesome</strong></summary>
  
```javascript
class HG {
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
    if (contributor instanceof HG) {
      contributor.makeProjectAwesome(this);
    }
  }

  getStatus() {
    console.log(`${this.name} is ${this.isAwesome ? 'now an awesome' : 'still not an awesome'} project.`);
  }
}

const myProject = new Project('the Project');
const me = new HG();
myProject.addContributor(me);
myProject.getStatus();
```
</details>

**Projects:**

  * I have my creativity captured in: [Github projects](https://github.com/Aiche-H?tab=repositories)
