
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Eeqan ❤️</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  min-height: 100vh;
  font-family: 'Trebuchet MS', sans-serif;
  background: linear-gradient(135deg, #ffb6d9, #ff758f, #ffc3a0);
  color: #a00048;
  text-align: center;
  overflow-x: hidden;
}

.heart {
  position: fixed;
  bottom: -40px;
  font-size: 25px;
  animation: floatUp linear infinite;
  pointer-events: none;
  z-index: 0;
}

@keyframes floatUp {
  to {
    transform: translateY(-115vh) rotate(360deg);
    opacity: 0;
  }
}

.container {
  position: relative;
  z-index: 1;
  width: 92%;
  max-width: 600px;
  margin: 35px auto;
  padding: 25px 18px;
  background: rgba(255,255,255,0.82);
  border: 3px solid white;
  border-radius: 28px;
  box-shadow: 0 10px 35px #d82b6b55;
}

h1 {
  font-size: clamp(27px, 7vw, 42px);
  font-weight: 900;
  line-height: 1.3;
  color: #e6005c;
  text-shadow: 2px 2px white;
}

.subtitle {
  font-size: 18px;
  color: #b00050;
}

.buttons {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 22px;
  margin: 35px 0;
  min-height: 65px;
}

button {
  border: none;
  border-radius: 50px;
  padding: 14px 30px;
  font-size: 20px;
  font-weight: bold;
  cursor: pointer;
  touch-action: manipulation;
  box-shadow: 0 5px 12px #0002;
}

#yes {
  color: white;
  background: #ff1675;
}

#yes:active {
  transform: scale(.94);
}

#no {
  color: #e6005c;
  background: #ffe0ed;
  transition: left .12s, top .12s;
  z-index: 10;
}

.letter {
  text-align: left;
  line-height: 1.85;
  font-size: 16px;
  color: #792044;
}

.hidden {
  display: none;
}

#celebration {
  padding: 15px 0;
}

#celebration h2 {
  font-size: 32px;
  font-weight: 900;
  color: #ff006e;
}

.dance {
  width: 180px;
  max-width: 70%;
  border-radius: 20px;
}

.graffiti {
  position: fixed;
  z-index: 5;
  pointer-events: none;
  font-size: 35px;
  animation: pop .8s ease-out forwards;
}

@keyframes pop {
  0% { transform: scale(0) rotate(-25deg); opacity: 0; }
  70% { transform: scale(1.4) rotate(15deg); opacity: 1; }
  100% { transform: scale(1) rotate(0); opacity: 1; }
}

.footer {
  font-size: 13px;
  color: #a00048;
}
</style>
</head>

<body>

<div class="container">
  <div style="font-size:42px">💗 🥹 💗</div>

  <h1>EEQAN,<br> WILL YOU BE<br> MY GIRLFRIEND? 💍❤️</h1>

  <p class="subtitle">
    Hey Eeqan! 🥹💖<br>
    Someone has a little question for you... 🙈
  </p>

  <div class="buttons" id="buttons">
    <button id="yes">YES 💗</button>
    <button id="no">NO 🙈</button>
  </div>

  <p style="font-weight:bold">
    Choose wisely, Eeqan! 🥺💕
  </p>

  <section id="celebration" class="hidden">
    <h2>YAYYYYY! SHE SAID YES! 🎉❤️</h2>

    <img class="dance"
      src="https://media.giphy.com/media/MDJ9IbxxvDUQM/giphy.gif"
      alt="Dancing celebration GIF">

    <h2>EEQAN ❤️ AFFAN</h2>
    <p style="font-size:21px;font-weight:900">
      YOU JUST MADE ME THE HAPPIEST PERSON EVER! 🥹💖
    </p>
    <p>Let our beautiful story begin... 🌹🦋</p>
    <button onclick="showLetter()">READ MY MESSAGE 💌</button>
  </section>

  <section id="message" class="hidden letter">
    <h2 style="text-align:center">Hey Eeqan ❤️🥹💗</h2>

    <p>
      I don’t really know how you’re going to react to this,
      but there’s something I’ve been wanting to tell you. 🫶🏻❤️
      We only met today, and honestly, I don’t know much about you
      yet, but I really enjoyed talking to you. There was something
      about our conversation that made me want to know you better,
      and I thought, why not just be honest about it? 🙈💕
      So here I am, trying to put my thoughts into words. 💌✨
    </p>

    <p>
      I’m not going to say that I know you completely or that I’ve
      fallen in love with you already, because I know that getting
      to know someone takes time. ❤️🌸 But I do know that I’d like
      to talk to you more, learn about your personality, know what
      makes you happy, listen to your stories, and discover all those
      little things that make you who you are. 🥹🦋💗
    </p>

    <p>
      Honestly, I don’t know what you think about me yet, and that’s
      completely okay. I don’t want you to feel pressured or think
      that you have to say yes just because I’m telling you all this.
      🫶🏻🤍 I just wanted to express myself instead of keeping these
      thoughts to myself. Sometimes, you meet someone and feel like
      you'd like to know them beyond just a simple hello, and that’s
      kind of how I feel right now. ❤️🙈
    </p>

    <p>
      I’m not here to make big promises or tell you things that sound
      perfect but might not mean much at this stage. I’d rather take
      things slowly, talk to you, understand you, and let everything
      happen naturally. 🌹💖 I believe that a good connection takes
      honesty, trust, respect, and effort from both sides. And if we
      ever build something special together, I’d want it to be real,
      something that makes both of us happy. 🥹❤️✨
    </p>

    <p>
      Maybe we’ll become good friends, maybe we’ll get closer with
      time, or maybe something beautiful will grow between us.
      💕🌷 I don’t know what the future holds, but I’d genuinely
      like to find out. After all, every beautiful story starts
      somewhere, and maybe ours can start with getting to know each
      other a little better. 🦋💌
    </p>

    <p><b>
      So, Eeqan, would you give me a chance to get to know you better
      and see where things go between us?
    </b> 🥹❤️🌹</p>

    <p>
      You don’t have to give me an answer right away, and there’s
      absolutely no pressure. 😊🤍 I just wanted you to know that
      I’d like to get to know you more and see if we can build
      something nice together. 🫶🏻💗
    </p>

    <p>
      Whatever your answer is, I’ll respect it. But I’d be really
      happy if you decided to give me that little chance. 🙈❤️✨
    </p>

    <p><b>
      Maybe this is just the beginning of a beautiful story…
      who knows?
    </b> 🥹💖🌹🦋</p>

    <h2 style="text-align:center">❤️ THE BEGINNING? ❤️</h2>
  </section>

  <p class="footer">Made with love, just for Eeqan 💌</p>
</div>

<script>
const no = document.getElementById("no");
const yes = document.getElementById("yes");
const buttons = document.getElementById("buttons");
const celebration = document.getElementById("celebration");
const message = document.getElementById("message");

function moveNo() {
  // Move the button to a random safe position on the screen.
  no.style.position = "fixed";

  const maxX = Math.max(5, window.innerWidth - no.offsetWidth - 10);
  const maxY = Math.max(5, window.innerHeight - no.offsetHeight - 10);

  no.style.left = Math.random() * maxX + "px";
  no.style.top = Math.random() * maxY + "px";
}

no.addEventListener("pointerenter", moveNo);
no.addEventListener("pointerdown", (event) => {
  event.preventDefault();
  moveNo();
});
no.addEventListener("click", (event) => {
  event.preventDefault();
  moveNo();
});
no.addEventListener("touchstart", (event) => {
  event.preventDefault();
  moveNo();
}, { passive: false });

yes.addEventListener("click", () => {
  buttons.classList.add("hidden");
  document.querySelector(".subtitle").classList.add("hidden");
  celebration.classList.remove("hidden");

  // Graffiti and emojis all over the screen!
  const stickers = [
    "❤️", "💖", "💕", "💗", "😍", "😘",
    "💋", "🌹", "🦋", "💍", "🎉", "🥹"
  ];

  for (let i = 0; i < 65; i++) {
    const sticker = document.createElement("div");
    sticker.className = "graffiti";
    sticker.textContent =
      stickers[Math.floor(Math.random() * stickers.length)];

    sticker.style.left = Math.random() * 95 + "vw";
    sticker.style.top = Math.random() * 95 + "vh";
    sticker.style.animationDelay = Math.random() * 1.5 + "s";

    document.body.appendChild(sticker);
  }

  window.scrollTo({ top: 0, behavior: "smooth" });
});

function showLetter() {
  message.classList.remove("hidden");
  message.scrollIntoView({ behavior: "smooth" });
}

// Floating heart background.
const hearts = ["❤️", "💗", "💖", "💕", "💘", "💝"];

function createHeart() {
  const heart = document.createElement("div");
  heart.className = "heart";
  heart.textContent = hearts[Math.floor(Math.random() * hearts.length)];
  heart.style.left = Math.random() * 100 + "vw";
  heart.style.animationDuration = (4 + Math.random() * 5) + "s";
  heart.style.fontSize = (16 + Math.random() * 22) + "px";

  document.body.appendChild(heart);

  setTimeout(() => heart.remove(), 9000);
}

setInterval(createHeart, 350);
</script>

</body>
</html>
