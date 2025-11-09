/* 💫 Yankee's Dark Neon + Gold Glow Theme */
:root {
  --neon-purple: #9D4EDD;
  --neon-gold: #FFD700;
  --bg-dark: #0D0D1A;
  --text-light: #EAEAEA;
}

body {
  background: var(--bg-dark);
  color: var(--text-light);
  font-family: 'Orbitron', sans-serif;
  margin: 0;
  padding: 0;
  text-align: center;
  overflow-x: hidden;
}

/* 🔮 Neon animated border glow */
h1, h2, h3 {
  color: var(--neon-gold);
  text-shadow: 0 0 10px var(--neon-gold), 0 0 20px var(--neon-purple);
  animation: glowPulse 2s ease-in-out infinite alternate;
}

/* ✨ Link styling */
a {
  color: var(--neon-purple);
  text-decoration: none;
  text-shadow: 0 0 5px var(--neon-purple), 0 0 15px var(--neon-gold);
  transition: all 0.3s ease;
}

a:hover {
  color: var(--neon-gold);
  text-shadow: 0 0 15px var(--neon-gold), 0 0 30px var(--neon-purple);
}

/* 🖼️ Image neon effect */
img {
  border-radius: 10px;
  box-shadow: 0 0 25px var(--neon-purple), 0 0 45px var(--neon-gold);
  transition: all 0.4s ease;
}

img:hover {
  transform: scale(1.05);
  box-shadow: 0 0 35px var(--neon-gold), 0 0 60px var(--neon-purple);
}

/* ⚡ Soft glow animation */
@keyframes glowPulse {
  from {
    text-shadow: 0 0 8px var(--neon-gold), 0 0 16px var(--neon-purple);
  }
  to {
    text-shadow: 0 0 20px var(--neon-purple), 0 0 35px var(--neon-gold);
  }
}
