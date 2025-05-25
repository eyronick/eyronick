<div align="center">
  <pre>Hey, It's Nikhil, Software Developer from India.</pre>
  <a href="https://www.x.com/nickkcodee">Twitter</a>
  •
  <a href="mailto:25nikmehta@gmail.com">Email</a>
  •
  <a href="https://www.linkedin.com/in/nickkcode">Linkedin</a>
  •
  <a href="https://portfolio-smoky-chi-69.vercel.app/blog">Website</a>
</div>

<div>&nbsp;</div>

<div>
  <div align="left">
  
```javascript
const getData = () => {
  const name = "👨‍🚀 Nikhil Singh Mehta";
  const role = "Full Stack Dev";
  const loves = ["clean UI", "powerful APIs", "building cool stuff"];

  return {
    name,
    role,
    vibe: `🚀 ${role} who loves ${loves.join(", ")}`,
    location: "📍 Haldwani, India",
  };
};

const getSkills = () => {
  const skills = {
    frontend: ["⚛️ React", "💨 Tailwind", "🧠 Next.js", "🎞️ Framer Motion"],
    backend: ["🌐 Node.js", "🚪 Express", "🍃 MongoDB", "🐘 Postgres", "🔐 JWT"],
    tools: ["🐳 Docker", "📁 Git", "🧪 Postman", "🎨 Figma"]
  };

  Object.entries(skills).map(([area, stack]) => {
    console.log(`\n🔹 ${area.toUpperCase()}`);
    stack.forEach(skill => console.log(`  • ${skill}`));
  });

  return skills;
};

(() => {
  const { name, vibe } = getData();
  console.log(`\n✨ Hello, I'm ${name}`);
  console.log(vibe);

  getSkills();
})();


```
  </div>
  <div align="right" width="200">
    <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2R0djFsMmRwenZoaDg0bnV5Zjg2OWhvMzk0NTJxZmR0dnh1dm9sdyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/5TP5AzxgesmNsQvdXl/giphy.gif"/>
  </div>
</div>


<div align="right" width="200">
  <a href="https://portfolio-smoky-chi-69.vercel.app/blog">
    <i>~ nickkcode</i>
  </a>
</div>
