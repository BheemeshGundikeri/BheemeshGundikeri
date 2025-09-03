<!-- Profile Banner -->
<p align="center">
  <img src="./banner.png" alt="Bheemesh Gundikeri Banner" width="100%" />
</p>

<h1 align="center">Hi 👋, I'm Bheemesh Gundikeri</h1>
<h3 align="center">A passionate Software Developer</h3>

<!-- Snake Animation -->
![GitHub Snake Light](dist/snake.svg#gh-light-mode-only)
![GitHub Snake Dark](dist/snake.svg#gh-dark-mode-only)

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=bheemeshgundikeri&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

---

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=BheemeshGundikeri&theme=algolia&no-frame=false&no-bg=false&margin-w=4)

---

### 🌱 Currently Learning & Working On
- 🌱 I’m currently learning AI Skills   
- 🛠️ Working on client development project!  
- 📚 Learning Advanced SQL queries.  
- 🐍 Debugging Python scripts for ADAS.  
- 🌱 Exploring front-end development trends.  
- 💻 Developing small scale AI chat bots.
- 👨‍💻 All of my projects are available at [My Portfolio](https://bheemesh-portfolio.netlify.app/)  
- 📫 How to reach me: **bheemesh.gundikeri24@gmail.com**  

---

## 💻 Tech Stack
<style>
  #skills-sphere {
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    /* Tooltip near sphere */
    #tooltip {
      position: absolute;
      background: rgba(0, 0, 0, 0.8);
      color: #0ef;
      padding: 8px 12px;
      border-radius: 8px;
      pointer-events: none;
      white-space: nowrap;
      font-size: 14px;
      display: none;
    }
    .progress-bar {
      background: #333;
      border-radius: 8px;
      height: 10px;
      margin-top: 6px;
      overflow: hidden;
    }
    .progress-fill {
      background: #0ef;
      height: 100%;
      width: 0%;
    }
  </style>
 <section id="skills-sphere">
    <script src="https://cdn.jsdelivr.net/npm/three@0.152.2/build/three.min.js"></script>
    <div id="tooltip"></div>
</section>

---

### 📚 Useful Resources
- [PHP Documentation](https://www.php.net/docs.php)  
- [jQuery Documentation](https://api.jquery.com/)  
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)

---

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=BheemeshGundikeri&limit=5&theme=neon&combine_all_yearly_contributions=true)

---

## 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api/top-langs/?username=BheemeshGundikeri&theme=neon&hide_border=false&include_all_commits=false&count_private=false&layout=compact)  
![](https://github-readme-stats.vercel.app/api?username=BheemeshGundikeri&theme=neon&hide_border=false&include_all_commits=false&count_private=false)  
![](https://nirzak-streak-stats.vercel.app/?user=BheemeshGundikeri&theme=neon&hide_border=false)

---

### 🌐 Connect with me
<p align="left">
<a href="https://www.linkedin.com/in/bheemesh-g" target="blank">
  <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
</a>
<a href="https://www.hackerrank.com/bheemesh_gundik1" target="blank">
  <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="HackerRank" height="30" width="40" />
</a>
</p>

---

### ✍️ Dev Quote of the Day
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)



<script>
  const scene = new THREE.Scene();
    const camera = new THREE.PerspectiveCamera(75, window.innerWidth/window.innerHeight, 0.1, 1000);
    const renderer = new THREE.WebGLRenderer({ antialias: true, alpha: true });
    renderer.setSize(window.innerWidth, window.innerHeight);
    document.getElementById("skills-sphere").prepend(renderer.domElement);

    const sphereGroup = new THREE.Group();
    scene.add(sphereGroup);

    const skills = [
      { name: "HTML", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg", history: "Portfolio, Library, Namma Raita", percent: 90 },
      { name: "CSS", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg", history: "Animations, Responsive UI", percent: 85 },
      { name: "JavaScript", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg", history: "Dynamic UI, Calculator", percent: 80 },
      { name: "React", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg", history: "Library Management System", percent: 70 },
      { name: "Java", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg", history: "Hospital Management System", percent: 75 },
      { name: "MySQL", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg", history: "Library DB, Hospital DB", percent: 88 },
      { name: "PHP", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg", history: "Personal projects", percent: 65 },
      { name: "Angular", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg", history: "Web applications", percent: 60 },
      { name: "jQuery", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg", history: "Dynamic UI, API calls", percent: 70 },
      { name: "Bootstrap", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg", history: "Responsive design", percent: 85 },
      { name: "MongoDB", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg", history: "Database management", percent: 55 },
      { name: "Node.js", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg", history: "Backend development", percent: 70 },
      { name: "Hibernate", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/hibernate/hibernate-original.svg", history: "Java ORM", percent: 60 },
      { name: "Oracle SQL", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg", history: "Database queries", percent: 75 },
      { name: "Express.js", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg", history: "Node.js framework", percent: 68 },
      { name: "Spring Boot", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/springboot/springboot-original.svg", history: "Java microservices", percent: 65 },
      { name: "Python", logo: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg", history: "Scripting, Automation", percent: 80 }
    ];
    
    const radius = 5, logoSize = 1.3;
    const loader = new THREE.TextureLoader();
    const sprites = [];

    skills.forEach((skill, i) => {
      loader.load(skill.logo, (texture) => {
        const material = new THREE.SpriteMaterial({ map: texture });
        const sprite = new THREE.Sprite(material);
        sprite.scale.set(logoSize, logoSize, 1);
        sprite.userData = skill;

        const phi = Math.acos(-1 + (2 * i) / skills.length);
        const theta = Math.sqrt(skills.length * Math.PI) * phi;
        sprite.position.setFromSphericalCoords(radius, phi, theta);

        sphereGroup.add(sprite);
        sprites.push(sprite);
      });
    });

    camera.position.z = 12;

    // Hover interaction
    const raycaster = new THREE.Raycaster();
    const mouse = new THREE.Vector2();
    const tooltip = document.getElementById("tooltip");
    let rotating = true;

    function onMouseMove(event) {
      mouse.x = (event.clientX / window.innerWidth) * 2 - 1;
      mouse.y = -(event.clientY / window.innerHeight) * 2 + 1;
      raycaster.setFromCamera(mouse, camera);
      const intersects = raycaster.intersectObjects(sprites);

      if (intersects.length > 0) {
        const skill = intersects[0].object.userData;
        showTooltip(skill, event.clientX, event.clientY);
        rotating = false;
      } else {
        hideTooltip();
        rotating = true;
      }
    }

    function showTooltip(skill, x, y) {
      tooltip.style.left = x + 15 + "px";
      tooltip.style.top = y + 15 + "px";
      tooltip.innerHTML = `
        <strong>${skill.name}</strong><br>
        ${skill.history}<br>
        <div class="progress-bar"><div class="progress-fill" style="width:${skill.percent}%"></div></div>
      `;
      tooltip.style.display = "block";
    }

    function hideTooltip() {
      tooltip.style.display = "none";
    }

    window.addEventListener("mousemove", onMouseMove);

    // Animation
   function animate() {
        requestAnimationFrame(animate);
        if (rotating) {
            sphereGroup.rotation.y += 0.0025; // Horizontal rotation
            sphereGroup.rotation.x += 0.0015; // Vertical rotation (slower for a more stable look)
        }
        renderer.render(scene, camera);
    }
    animate();

    window.addEventListener("resize", () => {
      camera.aspect = window.innerWidth / window.innerHeight;
      camera.updateProjectionMatrix();
      renderer.setSize(window.innerWidth, window.innerHeight);
    });

</script>