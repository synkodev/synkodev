<img align="left" src="software-development-icon.png" width="128px" height="128px">
<div>
  <h1>Weslley Alencar</h1>
  <a href="https://www.linkedin.com/in/walencar/" target="_blank"><img align="right" alt="Static Badge" src="https://img.shields.io/badge/linkedin-blue?style=for-the-badge&logo=linkedin"></a>
  <h4>Software Enginner | Teacher Assistant @ Le Wagon</h4>
</div>
<hr>
<h2>About me</h2>

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
    console.log(`Hi, welcome to my GitHub profile! I'm ${this._name}, I'm a ${this._role} and ${this.skills}`);
  }
}

const skillsArray = ['JavaScript', 'Ruby on Rails', 'Git', 'React.js', 'PostgreSQL', 'Microsoft SQL Server'];
const synkoDev = new Profile('Weslley Alencar', 'Software Enginner', skillsArray);
synkoDev.greetVisitors();
```

<!--
**synkodev/synkodev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
