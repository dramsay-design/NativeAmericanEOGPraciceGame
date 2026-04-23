<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>LOCK IN – Native Folklore Reading Game</title>
<style>
  :root{
    --bg1:#220735;
    --bg2:#4b146d;
    --bg3:#7c2d12;
    --purple:#b56cff;
    --orange:#ff9b3d;
    --coral:#ff7f8f;
    --pink:#ff9fc6;
    --light:#fff8f2;
    --card:rgba(31, 8, 52, 0.92);
    --line:rgba(255,255,255,.12);
    --gold:#ffd76b;
    --green:#87f3a0;
    --shadow:0 20px 45px rgba(0,0,0,.35);
  }

  *{box-sizing:border-box}
  html,body{margin:0;padding:0;scroll-behavior:smooth}
  body{
    min-height:100vh;
    font-family:"Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    color:var(--light);
    background:
      radial-gradient(circle at 12% 18%, rgba(255,127,143,.20), transparent 18%),
      radial-gradient(circle at 80% 12%, rgba(181,108,255,.22), transparent 22%),
      radial-gradient(circle at 75% 78%, rgba(255,155,61,.18), transparent 18%),
      linear-gradient(135deg, var(--bg1), var(--bg2) 48%, var(--bg3));
    overflow-x:hidden;
  }

  .glow-layer{
    position:fixed;
    inset:0;
    pointer-events:none;
    z-index:0;
    overflow:hidden;
  }
  .spark{
    position:absolute;
    border-radius:50%;
    width:5px;height:5px;
    background:white;
    box-shadow:0 0 10px white, 0 0 18px rgba(255,255,255,.65);
    animation: twinkle 4s infinite ease-in-out;
    opacity:.8;
  }
  .spark.big{
    width:8px;height:8px;
    background:linear-gradient(45deg, var(--orange), var(--coral));
    box-shadow:0 0 14px var(--orange), 0 0 24px var(--coral);
  }
  @keyframes twinkle{
    0%,100%{transform:scale(.6);opacity:.25}
    50%{transform:scale(1.55);opacity:1}
  }

  .wrap{
    position:relative;
    z-index:1;
    max-width:1220px;
    margin:0 auto;
    padding:24px;
  }

  .card{
    background:var(--card);
    border:1px solid var(--line);
    border-radius:28px;
    box-shadow:var(--shadow);
    padding:26px;
    margin-top:18px;
    backdrop-filter:blur(10px);
  }

  .hidden{display:none !important}
  .center{text-align:center}

  h1{
    margin:0 0 6px;
    font-size:3.2rem;
    letter-spacing:1px;
    line-height:1;
    background:linear-gradient(90deg, var(--orange), var(--coral), var(--purple));
    -webkit-background-clip:text;
    background-clip:text;
    color:transparent;
  }
  .subtitle{
    color:#ffeede;
    font-size:1.05rem;
    margin-bottom:16px;
  }
  .hero-text{
    max-width:760px;
    margin:20px auto 10px;
    font-size:1.2rem;
    line-height:1.65;
    font-weight:700;
  }
  .hero-note{
    color:var(--pink);
    margin-bottom:16px;
  }

  .input-row{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:12px;
    margin-top:18px;
  }
  input[type="text"]{
    width:min(520px, 92%);
    border-radius:16px;
    border:1px solid rgba(255,255,255,.18);
    background:rgba(255,255,255,.08);
    color:white;
    padding:14px 16px;
    font-size:1rem;
    outline:none;
  }
  input[type="text"]::placeholder{color:#f8deeb}

  button{
    border:none;
    border-radius:16px;
    padding:14px 22px;
    font-weight:800;
    font-size:1rem;
    cursor:pointer;
    transition:.2s ease;
  }
  button:hover{transform:translateY(-1px) scale(1.02)}
  .btn-main{
    background:linear-gradient(90deg, var(--orange), var(--coral), var(--purple));
    color:#2d083f;
  }
  .btn-alt{
    background:rgba(255,255,255,.08);
    color:white;
    border:1px solid rgba(255,255,255,.12);
  }

  .topbar{
    display:flex;
    justify-content:space-between;
    gap:12px;
    align-items:center;
    flex-wrap:wrap;
    margin-bottom:12px;
  }
  .stage-title{font-size:1.55rem;font-weight:800}
  .meta{color:#ffe8dd;font-size:.96rem}

  .progress{
    width:100%;
    height:16px;
    border-radius:999px;
    overflow:hidden;
    background:rgba(255,255,255,.08);
    border:1px solid rgba(255,255,255,.08);
    margin:8px 0 18px;
  }
  .bar{
    height:100%;
    width:0%;
    background:linear-gradient(90deg, var(--purple), var(--coral), var(--orange));
    transition:width .35s ease;
  }

  .text-panel{
    background:rgba(255,255,255,.05);
    border:1px solid rgba(255,255,255,.10);
    border-radius:22px;
    padding:22px;
    white-space:pre-wrap;
    line-height:1.82;
    color:#fffaf6;
    max-height:480px;
    overflow:auto;
    user-select:text;
  }

  .question{
    margin-top:18px;
    background:rgba(255,255,255,.045);
    border:1px solid rgba(255,255,255,.10);
    border-radius:20px;
    padding:18px;
  }
  .q-head{
    display:flex;
    justify-content:space-between;
    gap:10px;
    flex-wrap:wrap;
    margin-bottom:10px;
  }
  .q-num{color:var(--coral);font-weight:800}
  .q-std{color:var(--orange);font-weight:700;font-size:.95rem}
  .q-text{line-height:1.7;margin-bottom:10px}

  .option{
    display:block;
    margin:10px 0;
    padding:12px 14px;
    border-radius:14px;
    background:rgba(255,255,255,.05);
    border:1px solid rgba(255,255,255,.06);
    cursor:pointer;
  }
  .option:hover{background:rgba(255,255,255,.085)}
  .option input{margin-right:8px;transform:translateY(1px)}
  .choose-note{
    color:#ffe4ec;
    font-size:.92rem;
    margin:6px 0 10px;
    font-style:italic;
  }

  .drag-bank,.drop-wrap{display:flex;flex-wrap:wrap;gap:12px;margin-top:12px}
  .drag-item{
    padding:10px 14px;
    border-radius:14px;
    background:linear-gradient(90deg, var(--orange), var(--pink));
    color:#330b36;
    font-weight:800;
    cursor:grab;
    user-select:none;
  }
  .drop-zone{
    flex:1 1 240px;
    min-height:120px;
    border:2px dashed rgba(255,255,255,.24);
    border-radius:18px;
    padding:14px;
    background:rgba(255,255,255,.04);
  }
  .drop-zone h4{margin:0 0 10px;color:var(--gold)}

  .nav{
    display:flex;
    justify-content:space-between;
    gap:10px;
    flex-wrap:wrap;
    margin-top:20px;
  }

  .results h2{margin-top:0;font-size:2.25rem;color:var(--orange)}
  .score{font-size:1.25rem;margin:8px 0 16px}
  .summary-box{
    background:rgba(255,255,255,.05);
    border:1px solid rgba(255,255,255,.08);
    border-radius:18px;
    padding:16px;
    margin-top:14px;
    text-align:left;
  }
  .summary-box h3{margin:0 0 10px;color:var(--coral)}

  .certificate{
    margin-top:22px;
    position:relative;
    overflow:hidden;
    background:
      radial-gradient(circle at top left, rgba(255,127,143,.26), transparent 24%),
      radial-gradient(circle at bottom right, rgba(181,108,255,.22), transparent 24%),
      linear-gradient(135deg, #fff8f5, #fff1fb, #fff5e8);
    color:#4f184a;
    border:10px double #d97eff;
    border-radius:28px;
    padding:34px;
    text-align:center;
    box-shadow:0 0 0 5px rgba(255,215,107,.35) inset, 0 0 24px rgba(255,255,255,.42) inset;
  }
  .certificate:before,.certificate:after{
    content:"✦";
    position:absolute;
    font-size:3rem;
    color:#ff8c72;
    opacity:.35;
  }
  .certificate:before{top:16px;left:22px}
  .certificate:after{bottom:16px;right:22px}
  .certificate h2{margin:0;color:#7f2ab8}
  .big-name{font-size:2rem;color:#ce496b;font-weight:900;margin:12px 0}
  .mastery{
    display:inline-block;
    margin-top:14px;
    padding:10px 18px;
    border-radius:999px;
    background:linear-gradient(90deg, var(--gold), #fff0b0);
    color:#7a4b00;
    font-weight:900;
    letter-spacing:.5px;
  }
  .credit{margin-top:14px;text-align:center;color:#ffe5dd;font-size:.88rem}

  @media print{
    body{background:white}
    .glow-layer,.nav,#startScreen,.progress,.credit,.result-actions{display:none !important}
    .card{box-shadow:none;border:1px solid #ddd;background:white;color:#111}
    .certificate{display:block !important}
  }
</style>
</head>
<body>
<div class="glow-layer" id="glowLayer"></div>

<div class="wrap">
  <div id="startScreen" class="card center">
    <h1>LOCK IN</h1>
    <div class="subtitle">24 Questions • 3 Texts • Reading Analysis Challenge</div>
    <div class="hero-text">Read closely, think deeply, and prove what you know. This game will challenge you to analyze a poem, a legend, and an informational text using evidence, theme, structure, and author’s purpose.</div>
    <div class="hero-note">Enter your name and get ready to lock in.</div>
    <div class="input-row">
      <input id="studentName" type="text" placeholder="Enter your full name" autocomplete="off" />
      <button class="btn-main" onclick="startGame()">Start Game</button>
    </div>
  </div>

  <div id="gameScreen" class="card hidden">
    <div class="topbar">
      <div>
        <div class="stage-title" id="sectionTitle">Section</div>
        <div class="meta" id="sectionMeta">Text 1 of 3</div>
      </div>
      <div class="meta" id="questionCount">8 Questions</div>
    </div>

    <div class="progress"><div class="bar" id="bar"></div></div>

    <div class="text-panel" id="textPanel"></div>
    <div id="questionsPanel"></div>

    <div class="nav">
      <button class="btn-alt" onclick="prevSection()">Back</button>
      <button class="btn-main" onclick="nextSection()">Continue</button>
    </div>

    <div class="credit">Custom game built for classroom reading practice.</div>
  </div>

  <div id="resultScreen" class="card results hidden">
    <h2>Game Complete</h2>
    <div class="score" id="scoreText"></div>

    <div class="summary-box">
      <h3>Standards to Review</h3>
      <ul id="reteachList"></ul>
    </div>

    <div class="certificate hidden" id="certificate">
      <h2>Certificate of Mastery</h2>
      <p>This certifies that</p>
      <div class="big-name" id="certName"></div>
      <p>successfully completed</p>
      <h2>LOCK IN</h2>
      <p>and demonstrated strong reading analysis across poetry, folklore, and informational text.</p>
      <div class="mastery" id="masteryBadge">MASTERED • 75%+</div>
    </div>

    <div class="result-actions" style="margin-top:16px;">
      <button class="btn-main hidden" id="printBtn" onclick="window.print()">Print Certificate</button>
      <button class="btn-alt" onclick="location.reload()">Restart</button>
    </div>
  </div>
</div>

<script>
const glowLayer = document.getElementById("glowLayer");
for(let i=0;i<95;i++){
  const s=document.createElement("div");
  s.className="spark"+(Math.random()>.78?" big":"");
  s.style.left=Math.random()*100+"%";
  s.style.top=Math.random()*100+"%";
  s.style.animationDelay=(Math.random()*4)+"s";
  s.style.animationDuration=(3+Math.random()*4)+"s";
  glowLayer.appendChild(s);
}

document.addEventListener("copy", e => e.preventDefault());
document.addEventListener("cut", e => e.preventDefault());
document.addEventListener("paste", e => e.preventDefault());
document.addEventListener("contextmenu", e => e.preventDefault());
document.addEventListener("keydown", function(e){
  const k = e.key.toLowerCase();
  if((e.ctrlKey || e.metaKey) && ["c","x","v","u","s","a","p"].includes(k)) e.preventDefault();
});

const poemText = `In Mystic
by Joy Harjo

My path is a cross of burning trees,
Lit by crows carrying fire in their beaks.
I ask the guardians of these lands for permission to enter.
I am a visitor to this history.
No one remembers to ask anymore, they answer.
What do I expect in this New England seaport town,
near the birthplace of democracy,
Where I am a ghost?
Even a casino can’t make an Indian real.
Or should I say “native,” or “savage,” or “demon”?
And with what trade language?
I am trading a backwards look for jeopardy.
I agree with the ancient European maps.
There are monsters beyond imagination that troll the waters.
The Puritan’s determined ships did fall off the edge of the world . . .
I am happy to smell the sea,
Walk the narrow winding streets of shops and restaurants,
and delight in the company of friends, trees, and small winds.
I would rather not speak with history but history came to me.
It was dark before daybreak when the fire sparked.
The men left on a hunt from the Pequot village here where I stand.
The women and children left behind were set afire.
I do not want to know this, but my gut knows the language of bloodshed.
Over six hundred were killed, to establish a home for God’s people,
crowed the Puritan leaders in their Sunday sermons.
And then history was gone in a betrayal of smoke.
There is still burning though we live in a democracy erected over the burial ground.
This was given to me to speak.
Every poem is an effort at ceremony.
I asked for a way in.`;

const wampusText = `The Wampus Cat

Long ago, deep in the shadowy mountains that stretch through what we now call Arkansas and Missouri, people spoke in hushed voices of a creature known as the Wampus Cat—sometimes called the Gallywampus. Her story was not just one of fear, but of curiosity, disobedience, and transformation.

They say the Wampus Cat was not always a creature of the night. She was once a beautiful woman of the Cherokee people. Her hair was long and dark as river water at dusk, and her eyes were sharp with curiosity. While the men of her tribe would leave for days at a time to hunt in the mountains, the women were expected to remain behind, tending to the children, the fires, and the homes.

But this woman’s spirit was restless. She wondered what secrets the men shared—what stories they told, what magic they practiced beneath the stars. The more she thought about it, the more her curiosity grew until it could not be contained.

One night, as her husband left with the hunters, she followed him. Silently, carefully, she crept through the forest, her footsteps soft against the earth. To hide herself, she wrapped her body in the hide of a great mountain cat. The fur blended with the shadows, and she moved like a whisper between the trees.

After a long journey, she reached the hunters’ camp. The men sat in a circle around a glowing fire, their voices low and serious. Sparks rose into the night sky like tiny spirits. The woman crouched behind a jagged rock, clutching the cat hide tightly around her. From there, she watched and listened.

The stories they told were not meant for her ears. They spoke of sacred things—ancient spirits, powerful magic, and secrets passed down through generations. The flames flickered as if alive, and the air itself seemed to hum with unseen power. The woman leaned closer, her heart pounding. She was afraid… but she could not turn away.

Suddenly, the wind shifted. One of the elders stopped speaking. His eyes narrowed as he scanned the darkness. He had felt it—the presence of someone who did not belong. Slowly, he rose and walked toward the edge of the firelight, toward the very rock where the woman hid.

Before she could flee, she was discovered. The men pulled her from her hiding place, the mountain cat hide still wrapped around her trembling body. The firelight revealed her face, filled with fear and regret.

The elders were furious. She had broken a sacred law. The knowledge she had stolen was not meant for her, and her deception could not go unpunished. With heavy hearts, they decided her fate.

The eldest among them began to chant. The air grew thick. The fire roared higher, casting wild shadows across the trees. As the chant deepened, the mountain cat hide seemed to come alive. It tightened around her, fusing with her skin. The woman cried out—but her voice changed. It twisted into a low, terrifying growl. Her body shifted, bones stretching, muscles tightening. Her hands curled into claws. Her eyes burned with an eerie glow that pierced the darkness.

The transformation was complete. She was no longer human. She had become the Wampus Cat.

Banished from her tribe, she fled into the wilderness, her new form moving swiftly through the mountains and forests. Some say she walked on two legs like a human, while others claim she ran on four like a great cat. All agree on one thing—her eyes shone with an unnatural light, and her cry could freeze a person where they stood.

From that day on, strange stories spread across the land. Hunters spoke of being watched from the trees. Travelers told of glowing eyes following them through the night. And sometimes, in the quietest hours, people claimed they could hear her—half woman, half beast—calling out from deep within the forest.

In Arkansas and Missouri, they began calling her the Gallywampus, a name spoken with both fear and fascination. Even now, some say she still roams the mountains. Watching. Waiting. A reminder of what can happen when curiosity crosses the line into forbidden things—and when secrets are taken instead of earned.`;

const articleText = `Native American cultures are among the oldest continuous cultures in the world, and their traditions are deeply rooted in storytelling, spirituality, and a strong connection to nature. Across tribes such as the Cherokee Nation, Navajo Nation, and Lakota Tribe, folklore has played a critical role in shaping beliefs, behaviors, and daily life. These stories, passed down through oral tradition, were not simply forms of entertainment; they served as educational tools, moral guides, and spiritual frameworks. Native American folklore has had a lasting impact on cultural identity, influencing both traditional ways of life and practices that continue in modern times.

Folklore served as the foundation of knowledge in many Native American communities. Before written language became common, stories were used to explain natural events, teach survival skills, and guide behavior. Many tribes shared stories about creation, the origins of animals, and the roles humans play in the world. For example, trickster figures such as the coyote appear in multiple tribal traditions, often teaching lessons about consequences, responsibility, and human flaws. Anthropological research supports the claim that storytelling functioned as an early educational system, helping children learn expectations and values necessary for survival. These stories reinforced the importance of listening, respect, and community responsibility, shaping how individuals interacted with one another.

In addition to teaching social values, Native American folklore emphasized a deep spiritual connection to nature. Many tribes believed that all elements of the natural world—animals, plants, rivers, and even the wind—possessed a spirit. This belief, often described as animism, influenced how people treated the environment. For example, within the Navajo tradition, the concept of balance, known as hózhó, represents harmony between individuals and the natural world. Stories reinforced the idea that disrupting this balance could lead to negative consequences. As a result, Native American communities practiced sustainable living by hunting only what was necessary and using every part of the animal. This demonstrates that folklore was not abstract; it directly influenced environmental practices and promoted respect for the earth.

Folklore also played a significant role in shaping social structure and moral expectations. Stories often highlighted virtues such as courage, honesty, generosity, and loyalty, while warning against greed, selfishness, and dishonesty. In Lakota traditions, for instance, stories of warriors and spiritual leaders emphasized bravery and the importance of protecting the community. These narratives served as models for behavior, encouraging individuals to prioritize the well-being of the group over personal gain. Evidence from historical accounts and oral histories shows that these values were consistently reinforced through storytelling, helping maintain social order and unity within tribes.

Spiritual practices and ceremonies were also deeply connected to folklore. Many rituals, including dances, healing ceremonies, and seasonal celebrations, originated from traditional stories about creation and the spiritual world.

For example, powwows are large cultural gatherings that include music, dance, and storytelling, reflecting long-standing traditions. Similarly, Navajo sand painting ceremonies are rooted in healing stories and are used to restore balance and health. These practices provide evidence that folklore extends beyond storytelling and is embedded in lived cultural experiences. Through ceremonies, individuals connect with their ancestors, maintain cultural continuity, and express their spiritual beliefs.

Despite the effects of colonization, forced relocation, and cultural suppression, Native American traditions have endured and continue to evolve. Today, many tribes actively work to preserve their cultural heritage through education, language revitalization programs, and public events. Organizations such as the Cherokee Nation support storytelling initiatives and cultural programs that ensure traditions are passed on to future generations. Modern powwows, cultural festivals, and community gatherings demonstrate how folklore remains relevant in contemporary society. These events not only celebrate identity but also educate others about Native American history and values.

In conclusion, Native American folklore has played a crucial role in shaping cultural beliefs, social structures, and environmental practices. Through oral storytelling, tribes passed down essential knowledge that guided behavior, strengthened communities, and promoted harmony with nature. Evidence from anthropological studies, oral traditions, and modern cultural practices supports the claim that folklore continues to influence Native American life today. Although these traditions have adapted over time, their core values—respect, balance, and community—remain central. Understanding Native American folklore provides valuable insight into a worldview that emphasizes interconnectedness and sustainability, offering lessons that are still relevant in the modern world.`;

const sections = [
  {
    fullTitle:"Poem: In Mystic by Joy Harjo",
    text:poemText,
    questions:[
      {
        type:"single",
        standard:"RL.8.2",
        prompt:"Which statement best expresses the poem’s central idea?",
        options:[
          "The speaker visits Mystic only to enjoy the town’s shops, restaurants, and scenery.",
          "The poem shows that buried violence and erasure still shape the present, even in places celebrated for democracy.",
          "The poem argues that the past should remain forgotten so people can live peacefully.",
          "The speaker believes history is less powerful than personal memory."
        ],
        answer:1
      },
      {
        type:"single",
        standard:"RL.8.1",
        prompt:"Which line best supports the idea that the speaker feels invisible within the dominant version of American history?",
        options:[
          "‘I ask the guardians of these lands for permission to enter.’",
          "‘Where I am a ghost?’",
          "‘I am happy to smell the sea,’",
          "‘Every poem is an effort at ceremony.’"
        ],
        answer:1
      },
      {
        type:"single",
        standard:"RL.8.4",
        prompt:"What is the effect of the word ‘ghost’ as it is used in the poem?",
        options:[
          "It suggests the speaker is literally haunting the town.",
          "It emphasizes the speaker’s sense of being unseen, erased, or treated as unreal.",
          "It creates a cheerful and playful mood.",
          "It shows that the speaker has forgotten her own identity."
        ],
        answer:1
      },
      {
        type:"single",
        standard:"RL.8.3",
        prompt:"How does the poem’s shift from present-day observation to the Pequot massacre develop meaning?",
        options:[
          "It interrupts the poem with unrelated historical facts.",
          "It reveals that the place’s beauty exists alongside a violent history that still haunts the present.",
          "It proves the speaker prefers the past to the present.",
          "It changes the poem from serious to humorous."
        ],
        answer:1
      },
      {
        type:"multi",
        standard:"RL.8.1 / RL.8.6",
        prompt:"Which TWO details most clearly reveal the speaker’s critical view of how history has been remembered?",
        options:[
          "‘Even a casino can’t make an Indian real.’",
          "‘Walk the narrow winding streets of shops and restaurants,’",
          "‘Over six hundred were killed, to establish a home for God’s people,’",
          "‘and delight in the company of friends, trees, and small winds.’"
        ],
        answer:[0,2]
      },
      {
        type:"single",
        standard:"RL.8.5",
        prompt:"Why does the poet end with the lines ‘This was given to me to speak. / Every poem is an effort at ceremony. / I asked for a way in.’?",
        options:[
          "To show that the speaker now sees poetry as a duty to witness, honor, and recover silenced history.",
          "To explain that the speaker no longer cares about the events of the poem.",
          "To suggest the poem should only be read during special rituals.",
          "To show that the speaker wants to leave Mystic immediately."
        ],
        answer:0
      },
      {
        type:"drag",
        standard:"RL.8.4 / RL.8.5",
        prompt:"Drag each line into the effect it mainly creates in the poem.",
        items:[
          {text:"‘Lit by crows carrying fire in their beaks.’", target:"Ominous and unsettling imagery"},
          {text:"‘I am happy to smell the sea,’", target:"Moment of sensory calm"},
          {text:"‘The women and children left behind were set afire.’", target:"Historical violence"},
          {text:"‘Every poem is an effort at ceremony.’", target:"Purposeful reflection"}
        ],
        zones:["Ominous and unsettling imagery","Moment of sensory calm","Historical violence","Purposeful reflection"]
      },
      {
        type:"multi",
        standard:"RL.8.2 / RL.8.6",
        prompt:"Which TWO conclusions are best supported by the poem as a whole?",
        options:[
          "The poem suggests democracy can exist while still resting on injustice and erasure.",
          "The speaker sees history as completely separate from the present.",
          "The poem calls attention to the need to remember Native suffering honestly.",
          "The speaker believes language has no power to confront the past."
        ],
        answer:[0,2]
      }
    ]
  },
  {
    fullTitle:"Legend: The Wampus Cat",
    text:wampusText,
    questions:[
      {
        type:"single",
        standard:"RL.8.2",
        prompt:"Which theme is best developed in the legend?",
        options:[
          "Curiosity that ignores boundaries and sacred laws can lead to destructive consequences.",
          "Fear is always stronger than wisdom.",
          "Secrets should never be shared among any members of a community.",
          "Transformation always brings freedom and happiness."
        ],
        answer:0
      },
      {
        type:"single",
        standard:"RL.8.1",
        prompt:"Which detail best supports the inference that the woman’s downfall begins long before she is discovered?",
        options:[
          "Her hair was long and dark as river water at dusk.",
          "The more she thought about it, the more her curiosity grew until it could not be contained.",
          "Sparks rose into the night sky like tiny spirits.",
          "Travelers told of glowing eyes following them through the night."
        ],
        answer:1
      },
      {
        type:"single",
        standard:"RL.8.4",
        prompt:"What is the effect of the phrase ‘moved like a whisper between the trees’?",
        options:[
          "It creates comic imagery that makes the woman seem foolish.",
          "It emphasizes secrecy and stealth while building tension.",
          "It shows that the forest is friendly and welcoming.",
          "It suggests the woman has already become a spirit."
        ],
        answer:1
      },
      {
        type:"single",
        standard:"RL.8.3",
        prompt:"How does the discovery scene affect the development of the plot?",
        options:[
          "It resolves the conflict before the main action begins.",
          "It triggers the punishment and transformation that turn the woman into the Wampus Cat.",
          "It explains why the men leave to hunt.",
          "It proves the elders were mistaken about her actions."
        ],
        answer:1
      },
      {
        type:"multi",
        standard:"RL.8.1 / RL.8.3",
        prompt:"Which TWO details most clearly build suspense before the woman is discovered?",
        options:[
          "She wrapped herself in the hide of a great mountain cat.",
          "The elders were furious after she was caught.",
          "One elder stopped speaking and scanned the darkness.",
          "The story ends by warning that secrets should be earned."
        ],
        answer:[0,2]
      },
      {
        type:"single",
        standard:"RL.8.5",
        prompt:"Why does the author include a long transformation scene near the end of the legend?",
        options:[
          "To slow the pacing and make the punishment feel vivid, dramatic, and unforgettable.",
          "To suggest the woman deserves praise for her bravery.",
          "To show that the legend is mostly about the forest setting.",
          "To change the story into an informational article."
        ],
        answer:0
      },
      {
        type:"drag",
        standard:"RL.8.3 / RL.8.5",
        prompt:"Drag each event into the part of the plot where it belongs.",
        items:[
          {text:"The woman becomes consumed by curiosity about the men’s secrets.", target:"Rising action"},
          {text:"The elder senses a presence and discovers her hiding place.", target:"Climax"},
          {text:"The woman is transformed into the Wampus Cat.", target:"Falling action"},
          {text:"Stories spread that she still roams the mountains.", target:"Resolution"}
        ],
        zones:["Rising action","Climax","Falling action","Resolution"]
      },
      {
        type:"multi",
        standard:"RL.8.2 / RL.8.6",
        prompt:"Which TWO ideas does the ending emphasize?",
        options:[
          "The legend survives as both a warning and a mystery.",
          "The community eventually welcomes the Wampus Cat back home.",
          "Forbidden knowledge taken through deception can bring lasting consequences.",
          "The story proves that fear should control every decision."
        ],
        answer:[0,2]
      }
    ]
  },
  {
    fullTitle:"Informational Text: Native American Folklore and Culture",
    text:articleText,
    questions:[
      {
        type:"single",
        standard:"RI.8.2",
        prompt:"Which statement best captures the central idea of the article?",
        options:[
          "Native American folklore is mainly valuable because it entertains large audiences.",
          "Native American folklore has shaped values, beliefs, and practices in the past and continues to influence culture today.",
          "All Native American tribes share exactly the same stories and ceremonies.",
          "Modern festivals have replaced the traditional meaning of folklore."
        ],
        answer:1
      },
      {
        type:"single",
        standard:"RI.8.1",
        prompt:"Which detail best supports the claim that folklore functioned as an early educational system?",
        options:[
          "Powwows are large cultural gatherings that include music, dance, and storytelling.",
          "Stories were used to explain natural events, teach survival skills, and guide behavior.",
          "Many tribes believed rivers and wind possessed a spirit.",
          "Modern communities hold cultural festivals and public events."
        ],
        answer:1
      },
      {
        type:"single",
        standard:"RI.8.3",
        prompt:"How does the paragraph about hózhó contribute to the development of ideas in the article?",
        options:[
          "It provides a specific example of how folklore influenced environmental respect and balance.",
          "It proves that all tribes used the same word for harmony.",
          "It interrupts the article with an unrelated ceremonial detail.",
          "It argues that nature was feared more than respected."
        ],
        answer:0
      },
      {
        type:"single",
        standard:"RI.8.4",
        prompt:"What does the word ‘endured’ most nearly mean in the paragraph about colonization and cultural suppression?",
        options:[
          "were forgotten quickly",
          "survived through hardship",
          "were changed beyond recognition",
          "were copied from outside cultures"
        ],
        answer:1
      },
      {
        type:"multi",
        standard:"RI.8.1 / RI.8.8",
        prompt:"Which TWO details most directly support the claim that folklore is still relevant in modern Native American life?",
        options:[
          "Organizations such as the Cherokee Nation support storytelling initiatives and cultural programs.",
          "Many tribes shared stories about creation and the origins of animals.",
          "Modern powwows, festivals, and community gatherings continue to celebrate and teach cultural values.",
          "Stories once explained natural events before written language became common."
        ],
        answer:[0,2]
      },
      {
        type:"single",
        standard:"RI.8.6",
        prompt:"How does the author mainly present the topic throughout the article?",
        options:[
          "with a mocking tone that questions the value of folklore",
          "with a respectful, explanatory tone supported by examples and evidence",
          "with a biased tone that dismisses modern cultural practices",
          "with a mysterious tone that avoids clear claims"
        ],
        answer:1
      },
      {
        type:"drag",
        standard:"RI.8.3 / RI.8.8",
        prompt:"Drag each example into the idea it best supports.",
        items:[
          {text:"Stories taught children expectations and values necessary for survival.", target:"Folklore as education"},
          {text:"Hunting only what was necessary promoted respect for the earth.", target:"Folklore shaping environmental practice"},
          {text:"Stories highlighted virtues such as courage, honesty, and loyalty.", target:"Folklore shaping moral behavior"},
          {text:"Powwows and cultural programs help pass traditions to future generations.", target:"Folklore in modern life"}
        ],
        zones:["Folklore as education","Folklore shaping environmental practice","Folklore shaping moral behavior","Folklore in modern life"]
      },
      {
        type:"multi",
        standard:"RI.8.2 / RI.8.6",
        prompt:"Which TWO conclusions are best supported by the article’s conclusion?",
        options:[
          "Native American folklore offers lessons about interconnectedness and sustainability that still matter today.",
          "Folklore has become unimportant because communities now rely on written texts.",
          "Core values such as respect, balance, and community remain central even as traditions adapt over time.",
          "The article concludes that traditional practices should remain completely unchanged."
        ],
        answer:[0,2]
      }
    ]
  }
];

let currentSection = 0;
let playerName = "";
let answers = {};

function esc(str){
  return String(str).replace(/[&<>"']/g, m => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[m]));
}
function shuffle(arr){
  const copy=[...arr];
  for(let i=copy.length-1;i>0;i--){
    const j=Math.floor(Math.random()*(i+1));
    [copy[i],copy[j]]=[copy[j],copy[i]];
  }
  return copy;
}
function arraysEqual(a,b){
  if(!Array.isArray(a) || !Array.isArray(b) || a.length!==b.length) return false;
  const aa=[...a].sort((x,y)=>x-y);
  const bb=[...b].sort((x,y)=>x-y);
  return aa.every((v,i)=>v===bb[i]);
}
function gradeDrag(q, response){
  if(!response) return false;
  return q.items.every(item => {
    const placed = response[item.target] || [];
    return placed.includes(item.text);
  });
}
function scrollTopNow(){
  window.scrollTo({top:0, behavior:"smooth"});
}

function prepareQuestions(){
  sections.forEach(sec=>{
    sec.questions.forEach(q=>{
      if((q.type==="single" || q.type==="multi") && !q._prepared){
        const items=q.options.map((t,i)=>({t,i}));
        const s=shuffle(items);
        q.options=s.map(x=>x.t);
        if(q.type==="single"){
          q.answer=s.findIndex(x=>x.i===q.answer);
        }else{
          q.answer=s.map((x,newIndex)=>q.answer.includes(x.i) ? newIndex : null).filter(v=>v!==null);
        }
        q._prepared=true;
      }
      if(q.type==="drag" && !q._prepared){
        q.items=shuffle(q.items);
        q._prepared=true;
      }
    });
  });
}

function startGame(){
  const name = document.getElementById("studentName").value.trim();
  if(!name){
    alert("Please enter your name.");
    return;
  }
  playerName = name;
  prepareQuestions();
  document.getElementById("startScreen").classList.add("hidden");
  document.getElementById("gameScreen").classList.remove("hidden");
  renderSection();
  scrollTopNow();
}

function renderSection(){
  const sec = sections[currentSection];
  document.getElementById("sectionTitle").textContent = sec.fullTitle;
  document.getElementById("sectionMeta").textContent = `Text ${currentSection+1} of ${sections.length}`;
  document.getElementById("questionCount").textContent = `${sec.questions.length} Questions`;
  document.getElementById("bar").style.width = (((currentSection+1)/sections.length)*100) + "%";
  document.getElementById("textPanel").textContent = sec.text;
  renderQuestions(sec);
  scrollTopNow();
}

function renderQuestions(sec){
  const panel = document.getElementById("questionsPanel");
  panel.innerHTML = "";

  sec.questions.forEach((q, i)=>{
    const key = `${currentSection}_${i}`;
    const saved = answers[key];
    const div = document.createElement("div");
    div.className = "question";

    let html = `
      <div class="q-head">
        <div class="q-num">Question ${i+1}</div>
        <div class="q-std">${esc(q.standard)}</div>
      </div>
      <div class="q-text">${esc(q.prompt)}</div>
    `;

    if(q.type === "single"){
      q.options.forEach((opt, idx)=>{
        const checked = saved === idx ? "checked" : "";
        html += `
          <label class="option">
            <input type="radio" name="q_${currentSection}_${i}" value="${idx}" ${checked}>
            ${esc(opt)}
          </label>
        `;
      });
    }

    if(q.type === "multi"){
      html += `<div class="choose-note">Choose two answers.</div>`;
      q.options.forEach((opt, idx)=>{
        const checked = Array.isArray(saved) && saved.includes(idx) ? "checked" : "";
        html += `
          <label class="option">
            <input type="checkbox" name="q_${currentSection}_${i}" value="${idx}" ${checked}>
            ${esc(opt)}
          </label>
        `;
      });
    }

    if(q.type === "drag"){
      html += `<div class="drag-bank" id="bank_${currentSection}_${i}"></div>`;
      html += `<div class="drop-wrap">`;
      q.zones.forEach((z, zi)=>{
        html += `<div class="drop-zone" id="zone_${currentSection}_${i}_${zi}" data-zone="${esc(z)}"><h4>${esc(z)}</h4></div>`;
      });
      html += `</div>`;
    }

    div.innerHTML = html;
    panel.appendChild(div);

    if(q.type === "drag") setupDragQuestion(q, i, saved);
  });
}

function setupDragQuestion(q, questionIndex, saved){
  const bank = document.getElementById(`bank_${currentSection}_${questionIndex}`);
  const placements = saved || {};
  const placedTexts = new Set();

  q.zones.forEach(zone=>{
    if(placements[zone]) placements[zone].forEach(t=>placedTexts.add(t));
  });

  q.items.forEach((item, idx)=>{
    const el = document.createElement("div");
    el.className = "drag-item";
    el.textContent = item.text;
    el.draggable = true;
    el.id = `drag_${currentSection}_${questionIndex}_${idx}`;
    el.dataset.label = item.text;
    el.dataset.target = item.target;
    el.addEventListener("dragstart", e=>{ e.dataTransfer.setData("text/plain", el.id); });

    let placed = false;
    q.zones.forEach((zone, zi)=>{
      if(placements[zone] && placements[zone].includes(item.text)){
        document.getElementById(`zone_${currentSection}_${questionIndex}_${zi}`).appendChild(el);
        placed = true;
      }
    });

    if(!placed && !placedTexts.has(item.text)) bank.appendChild(el);
  });

  q.zones.forEach((zone, zi)=>{
    const z = document.getElementById(`zone_${currentSection}_${questionIndex}_${zi}`);
    z.addEventListener("dragover", e=>e.preventDefault());
    z.addEventListener("drop", e=>{
      e.preventDefault();
      const id = e.dataTransfer.getData("text/plain");
      const dragged = document.getElementById(id);
      if(dragged) z.appendChild(dragged);
    });
  });

  bank.addEventListener("dragover", e=>e.preventDefault());
  bank.addEventListener("drop", e=>{
    e.preventDefault();
    const id = e.dataTransfer.getData("text/plain");
    const dragged = document.getElementById(id);
    if(dragged) bank.appendChild(dragged);
  });
}

function saveCurrentSection(){
  const sec = sections[currentSection];
  sec.questions.forEach((q,i)=>{
    const key = `${currentSection}_${i}`;

    if(q.type==="single"){
      const checked = document.querySelector(`input[name="q_${currentSection}_${i}"]:checked`);
      answers[key] = checked ? Number(checked.value) : null;
    }

    if(q.type==="multi"){
      const checked = Array.from(document.querySelectorAll(`input[name="q_${currentSection}_${i}"]:checked`)).map(x=>Number(x.value));
      answers[key] = checked;
    }

    if(q.type==="drag"){
      const result = {};
      q.zones.forEach((zone, zi)=>{
        const zoneEl = document.getElementById(`zone_${currentSection}_${i}_${zi}`);
        result[zone] = Array.from(zoneEl.querySelectorAll(".drag-item")).map(x=>x.dataset.label);
      });
      answers[key] = result;
    }
  });
}

function prevSection(){
  saveCurrentSection();
  if(currentSection>0){
    currentSection--;
    renderSection();
  }
}

function nextSection(){
  saveCurrentSection();
  if(currentSection < sections.length-1){
    currentSection++;
    renderSection();
  } else {
    showResults();
  }
}

function showResults(){
  document.getElementById("gameScreen").classList.add("hidden");
  document.getElementById("resultScreen").classList.remove("hidden");

  let total = 0;
  let correct = 0;
  const misses = {};

  sections.forEach((sec, si)=>{
    sec.questions.forEach((q, qi)=>{
      total++;
      const key = `${si}_${qi}`;
      const resp = answers[key];
      let ok = false;

      if(q.type==="single") ok = Number(resp) === q.answer;
      else if(q.type==="multi") ok = arraysEqual(resp, q.answer);
      else if(q.type==="drag") ok = gradeDrag(q, resp);

      if(ok) correct++;
      else misses[q.standard] = (misses[q.standard] || 0) + 1;
    });
  });

  const percent = Math.round((correct / total) * 100);
  document.getElementById("scoreText").textContent = `${playerName} scored ${correct} out of ${total} — ${percent}%.`;

  const reteach = document.getElementById("reteachList");
  reteach.innerHTML = "";
  const missEntries = Object.entries(misses).sort((a,b)=>b[1]-a[1]);

  if(missEntries.length === 0){
    reteach.innerHTML = "<li>None — excellent work across all standards.</li>";
  } else {
    missEntries.forEach(([std,count])=>{
      const li = document.createElement("li");
      li.textContent = `${std} — ${count} question(s) missed`;
      reteach.appendChild(li);
    });
  }

  const cert = document.getElementById("certificate");
  const printBtn = document.getElementById("printBtn");
  if(percent >= 75){
    cert.classList.remove("hidden");
    printBtn.classList.remove("hidden");
    document.getElementById("certName").textContent = playerName;
    document.getElementById("masteryBadge").textContent = `MASTERED • ${percent}%`;
  } else {
    cert.classList.add("hidden");
    printBtn.classList.add("hidden");
  }

  scrollTopNow();
}
</script>
</body>
</html>
