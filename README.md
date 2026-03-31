<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=200&section=header&text=Suliman%20Yousef&fontSize=70&fontColor=FF2D20&animation=fadeIn&fontAlignY=35" alt="Header" />

<h3 align="center">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&duration=3000&pause=1000&color=FF2D20&center=true&vCenter=true&width=600&lines=Software+Engineer;Full+Stack+Developer;Laravel+Developer;Clean+Architecture" alt="Typing SVG" />
</h3>

<div align="center" style="margin-top: 20px;">
  <a href="https://suliamanyousef.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-1a202c?style=for-the-badge&logo=vercel&logoColor=FF2D20&labelColor=0d1117" height="30" />
  </a>
  <a href="https://github.com/Su03l" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-1a202c?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" height="30" />
  </a>
  <a href="https://www.linkedin.com/in/suliaman-yousef-36265a320" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-1a202c?style=for-the-badge&logo=linkedin&logoColor=0a66c2&labelColor=0d1117" height="30" />
  </a>
  <a href="https://twitter.com/Su05l" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1a202c?style=for-the-badge&logo=twitter&logoColor=1DA1F2&labelColor=0d1117" height="30" />
  </a>
</div>

</div>

<br/>

## 💻 Developer_Profile.php

```php
<?php

namespace App\Engineers;

class Suliman extends FullStackDeveloper
{
    public string $name = 'Suliman Yousef';
    public string $education = 'Taibah University (Honors)';
    
    public function getTechStack(): array
    {
        return [
            'frontend' => ['React', 'Next.js', 'TypeScript', 'Tailwind CSS'],
            'backend'  => ['Laravel', 'PHP', 'Spring Boot', 'Java'],
            'database' => ['PostgreSQL', 'MySQL', 'MongoDB'],
            'tools'    => ['Git', 'Docker', 'Postman', 'Linux']
        ];
    }

    public function getGoal(): string
    {
        return 'Seeking a Laravel Developer role to build robust and scalable applications.';
    }

    public function execute(): void
    {
        echo "Converting complex requirements into seamless digital experiences 🚀";
    }
}
