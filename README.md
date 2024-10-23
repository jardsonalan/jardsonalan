<h1>Welcome to my repository! 👋🏼</h1>


```ts
abstract class Developer {
    private readonly id:number;
    protected nome:string;
    protected area:string;
  
    constructor(){
      this.id = 1;
      this.nome = 'Jardson Alan';
      this.area = 'Front-End';
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

<h1>Skills</h1>
<div>
  <img src='https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white'>
  <img src='https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white'>
  <img src='https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black'>
  <img src='https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white'>
  <img src='https://img.shields.io/badge/Python-1572B6?style=for-the-badge&logo=python&logoColor=white'>
  <img src='https://img.shields.io/badge/MySQL-1572b6?style=for-the-badge&logo=mysql&logoColor=white'>
</div>

<h1>Activities</h1>
<div>
  <img src='https://github-readme-stats.vercel.app/api?username=jardsonalan&theme=github_dark&card_width=450'>
  <img align='right' src='https://github-readme-stats.vercel.app/api/top-langs/?username=jardsonalan&hide=html&layout=compact&theme=github_dark'>
</div>
