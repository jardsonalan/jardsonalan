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
        this.languages=['HTML5', 'CSS3', 'Vue.js', 'JavaScript', 'TypeScript', 'Python', 'MySQL'];
    };
};
```

<h2>Skills</h2>
<div>
    <img src="https://skillicons.dev/icons?i=vue,vuetify,ts,js,py,html,css,mysql,vscode,figma,git,github,linux,windows" />
</div>

<h2>Activities</h2>
<div align='center'>
    <img src='https://github-readme-stats.vercel.app/api?username=jardsonalan&theme=github_dark&card_width=400'>
    <img src='https://github-readme-stats.vercel.app/api/top-langs/?username=jardsonalan&hide=html&layout=compact&theme=github_dark&card_width=400'>
</div>
