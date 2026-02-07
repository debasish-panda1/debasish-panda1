# debasis-panda1
<h1 align="center">Hi 👋, I'm Debasish Panda</h1>
<h3 align="center">MERN Stack Developer | Full-Stack Learner</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&center=true&vCenter=true&width=650&lines=MERN+Stack+Developer;Learning+Full+Stack+Development;Building+Real+World+Projects;Focused+on+Internships+%26+Growth" />
</p>

---

## 🚀 About Me
- 🎓 B.Tech CSE student  
- 💻 Learning **MERN Stack** (MongoDB, Express, React, Node.js)  
- 🌱 Currently improving **backend + system design basics**  
- 🎯 Targeting **internships & entry-level roles**  
- 📍 India  

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,nodejs,express,mongodb,git,github,tailwind" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=debasis-panda1&show_icons=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=debasis-panda1&theme=tokyonight" />
</p>

---

## 📈 Most Used Languages

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=debasis-panda1&layout=compact&theme=tokyonight" />
</p>

---

## 🧠 Sample Logic (JWT-style Middleware)

```js
export const protect = (req, res, next) => {
  const token = req.headers.authorization?.split(" ")[1];
  if (!token) {
    return res.status(401).json({ message: "Unauthorized" });
  }
  next();
};
