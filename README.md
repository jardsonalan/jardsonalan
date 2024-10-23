<h1>Welcome to my repository! 👋🏼</h1>


```ts
abstract class Developer {
    private readonly id:number;
    protected name:string;
    protected stack:string;
  
    constructor(){
      this.id = 1;
      this.name = 'Jardson Alan';
      this.stack = 'Front-End';
    };
};

class Skills extends Developer {
    private languages:string[] = [];

    constructor(){
        super();
        this.languages=['HTML5', 'CSS3', 'JavaScript', 'TypeScript', 'Python', 'MySQL'];
    };
};
```

<h2>Skills</h2>
<div>
  <img src='https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white'>
  <img src='https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white'>
  <img src='https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black'>
  <img src='https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white'>
  <img src='https://img.shields.io/badge/Python-1572B6?style=for-the-badge&logo=python&logoColor=white'>
  <img src='https://img.shields.io/badge/MySQL-1572b6?style=for-the-badge&logo=mysql&logoColor=white'>
</div>

<h2>Activities</h2>
<div align='center'>
  <img src='https://github-readme-stats.vercel.app/api?username=jardsonalan&theme=github_dark&card_width=400'>
  <img src='https://github-readme-stats.vercel.app/api/top-langs/?username=jardsonalan&hide=html&layout=compact&theme=github_dark&card_width=400'>
</div>
