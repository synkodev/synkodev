<img align="left" src="software-development-icon.png" width="200px" height="200px">
<p align="right">
  <a href="https://www.linkedin.com/in/walencar/" target="_blank"><img alt="Static Badge" src="https://github.com/synkodev/synkodev/assets/69865585/4679c433-5c8c-44c0-9916-5a5aefe813e1" width="32px" height="32px"></a>
</p>
<div>
  <h1>Weslley Alencar 🏳️‍🌈🎮</h1>
  <h4>Software Engineer 🧑‍💻| Teacher Assistant @ Le Wagon 👨‍🏫</h4>
</div>
<hr>
<h2>About me 📰</h2>

```javascript
class Profile {
  constructor(name, role, skills) {
    this._name = name;
    this._role = role;
    this._skills = skills;
  }
  get name() {
    return this._name;
  }
  get role() {
    return this._targetRole;
  }
  get skills () {
    return `I'm currently working with and learning the following set of languages: ${this._skills.join(', ')}.`;
  }
  addSkill(newSkill) {
    if (typeof newSkill === 'string') {
      this._skill.push(newSkill);
    }
  }
  greetVisitors() {
    console.log(`Hi, welcome to my GitHub profile! I'm ${this._name}, I'm a ${this._role.toLowerCase()} and ${this.skills}`);
  }
}

const skillsArray = ['JavaScript', 'Ruby on Rails', 'Git', 'React.js', 'PostgreSQL', 'Microsoft SQL Server'];
const synkoDev = new Profile('Weslley Alencar', 'Software Engineer', skillsArray);
synkoDev.greetVisitors();
```

<!-- Leaving the lines below for future inspo :)

Here are some ideas to get you started:
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 📫 How to reach me: ...
- ⚡ Fun fact: ...
-->
