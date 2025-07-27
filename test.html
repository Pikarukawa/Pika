<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Danganronpa Quizz</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      max-width: 700px;
      margin: auto;
      padding: 30px;
      background: #f8f9fc;
      color: #333;
    }

    h2 {
      text-align: center;
      color: #d63384;
    }

    .slider-block {
      margin-bottom: 25px;
    }

    .trait-labels {
      display: flex;
      justify-content: space-between;
      font-size: 0.9rem;
      margin-bottom: 6px;
    }

    input[type=range] {
      width: 100%;
      -webkit-appearance: none;
      height: 8px;
      border-radius: 5px;
      background: linear-gradient(to right, #ffc107, #0d6efd);
      outline: none;
    }

    #submitBtn {
      display: block;
      margin: 30px auto;
      padding: 12px 30px;
      font-size: 1rem;
      background-color: #0d6efd;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }

    #submitBtn:hover {
      background-color: #084298;
    }

    #result {
      margin-top: 40px;
      text-align: center;
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 12px rgba(0,0,0,0.1);
    }

    #result img {
      max-width: 100%;
      border-radius: 12px;
      margin-top: 15px;
    }

    #resultQuote {
      font-style: italic;
      margin-top: 15px;
    }

    #resultRanking {
      margin-top: 30px;
    }

    ol {
      padding-left: 20px;
    }

    li {
      margin-bottom: 6px;
    }
  </style>
</head>
<body>

  <h2>Quel personnage des RP Danganronpa es-tu?</h2>

  <!-- 14 traits avec labels bilatéraux -->
  <div id="sliders"></div>

  <button id="submitBtn">Je suis...</button>

  <div id="result">
    <h3 id="resultName"></h3>
    <img id="resultImage" src="" alt="Character Image" style="display: none;">
    <p id="resultQuote"></p>
  </div>

  <div id="resultRanking"></div>

  <script>
    const traits = [
      ["Indolent", "Entreprenant"],
      ["Violence", "Pacifisme"],
      ["Opportunisme", "Intégrité"],
      ["Intimidant", "Mignon"],
      ["Franc", "Diplomate"],
      ["Vilain Petit Canard", "Populaire"],
      ["Introverti", "Extraverti"],
      ["Suiveur", "Leader"],
      ["Instable", "Stable"],
      ["Émotionnel", "Rationnel"],
      ["Cynique", "Naïf"],
      ["Frigide", "Horny"],
      ["Égocentrique", "Altruiste"],
      ["Glace", "Feu"]
    ];

    const slidersContainer = document.getElementById("sliders");

    traits.forEach((pair, index) => {
      const block = document.createElement("div");
      block.className = "slider-block";

      block.innerHTML = `
        <div class="trait-labels">
          <span>${pair[0]}</span>
          <span>${pair[1]}</span>
        </div>
        <input type="range" min="0" max="100" value="50" id="trait${index + 1}">
      `;

      slidersContainer.appendChild(block);
    });

    const characters = [
      {
        name: "Agatha Proklinata",
        traits: [100, 31, 21, 17, 97, 41, 66, 93, 10, 21, 34, 10, 76, 97],
        image: "https://i.ibb.co/yFk9vnSS/agatha-proklinata-avatar.webp", // Replace with your own
        quote: "Premier personnage qui a canoniquement participé à un génocide."
      },
      {
        name: "Anémone Océane",
        traits: [90, 69, 66, 93, 90, 100, 45, 76, 31, 0, 90, 48, 97, 90],
        image: "https://i.ibb.co/WWBvyGSS/an-mone-oc-ane-avatar.png", // Replace with your own
        quote: "I can fix her, actually does."
      },
      {
        name: "Bao Choi",
        traits: [24, 97, 41, 59, 38, 62, 76, 59, 93, 76, 24, 66, 38, 72],
        image: "https://i.ibb.co/N2t4vcgd/bao-choi-avatar.png", // Replace with your own
        quote: "Eheh, j'ai causé la mort de tous mes potes."
      },
      {
        name: "Eris Mikoli",
        traits: [72, 48, 72, 100, 72, 76, 79, 79, 34, 41, 41, 41, 90, 100],
        image: "https://i.ibb.co/6JvStwPs/eris-mikoli-avatar.png", // Replace with your own
        quote: "Edgy past, Cutie girl."
      },
      {
        name: "Fiona Brennan",
        traits: [21, 45, 55, 48, 17, 45, 38, 62, 59, 48, 52, 59, 62, 62],
        image: "https://i.ibb.co/Y7whTkg8/fiona-brennan-avatar.png", // Replace with your own
        quote: "Grrrr Viola Grrrr."
      },
      {
        name: "Flynn DeLaCreme",
        traits: [66, 28, 7, 41, 7, 10, 69, 34, 0, 3, 38, 100, 52, 48],
        image: "https://i.ibb.co/tPcqcDp3/flynn-de-lacreme-avatar.png", // Replace with your own
        quote: "Sais-tu comment j'ai eu ces cicatrices ?"
      },
      {
        name: "Juan Luna",
        traits: [10, 41, 100, 7, 21, 34, 34, 72, 100, 45, 100, 17, 79, 76],
        image: "https://i.ibb.co/HLwVzkYt/juan-luna-avatar.png", // Replace with your own
        quote: "Hmm... Oui."
      },
      {
        name: "Lydia Findlay",
        traits: [55, 90, 45, 76, 83, 83, 100, 10, 48, 66, 86, 93, 59, 97],
        image: "https://i.ibb.co/mVXcVpNC/lydia-findlay-avatar.png", // Replace with your own
        quote: "Miam Miam, c'est bon les orteils."
      },
      {
        name: "Lyra May",
        traits: [93, 62, 31, 86, 24, 72, 17, 45, 17, 100, 17, 31, 24, 10],
        image: "https://i.ibb.co/FLCts5Nj/lyra-may-avatar.png", // Replace with your own
        quote: "J'ai une relation très saine avec Anémone, elle fait tout, et moi, je suis une reine."
      },
      {
        name: "Marco Lunargento",
        traits: [52, 66, 59, 28, 100, 59, 62, 83, 62, 52, 76, 52, 72, 69],
        image: "https://i.ibb.co/XkFxC1KC/marco-lunargento-avatar.png", // Replace with your own
        quote: "A essayé de draguer durant un jeu de la mort, a fini friendzoné avec un enfant à charge."
      },
      {
        name: "Orlando Sylla",
        traits: [59, 21, 79, 21, 59, 7, 3, 7, 28, 83, 48, 0, 45, 7],
        image: "https://i.ibb.co/4RdsBsSL/orlando-sylla-avatar.png", // Replace with your own
        quote: "Bad Ending: Vous êtes Orlando."
      },
      {
        name: "Sabrina Margaretha",
        traits: [28, 55, 14, 45, 34, 28, 72, 28, 79, 17, 14, 62, 28, 93],
        image: "https://i.ibb.co/q31nChN8/sabrina-margaretha-avatar.png", // Replace with your own
        quote: "A ne pas consommer en état d'ivresse."
      },
      {
        name: "Aislinn Fisceau",
        traits: [0, 72, 34, 66, 48, 66, 7, 31, 38, 72, 3, 76, 34, 17],
        image: "https://i.ibb.co/xStWWxLJ/Aislinn-Fisceau-Avatar.png", // Replace with your own
        quote: "Adore son frère, le laisse mourir. #Relatable."
      },
      {
        name: "Darren Mulligan",
        traits: [17, 10, 10, 52, 62, 14, 52, 3, 10, 10, 66, 72, 31, 45],
        image: "https://i.ibb.co/0RKStbWb/Darren-Mulligan-Avatar.png", // Replace with your own
        quote: "Allez ma jolie... Viens... Allez... Fais pas ta meuf... Eheheheheh..."
      },
      {
        name: "Jean-Philippe Provincial",
        traits: [14, 76, 17, 72, 10, 0, 41, 69, 76, 7, 93, 24, 0, 48],
        image: "https://i.ibb.co/v4RhqjvD/Jean-Phillipe-Provincial-Avatar.png", // Replace with your own
        quote: "Euh... Rip ?"
      },
      {
        name: "Nadir Khalid",
        traits: [97, 100, 86, 62, 55, 86, 90, 100, 55, 86, 69, 38, 93, 90],
        image: "https://i.ibb.co/S4zs0kTr/Nadir-Khalid-Avatar.png", // Replace with your own
        quote: "Premier homme populaire de l'histoire d'Internet, sans aucun doute le sang arabe."
      },
      {
        name: "Noel Stoga",
        traits: [79, 59, 52, 90, 86, 79, 93, 41, 41, 62, 34, 79, 90, 59],
        image: "https://i.ibb.co/cc12mbXH/Noel-Stoga-Avatar.png", // Replace with your own
        quote: "Hihihihihihihihihihihihi! Je suis suuuuuper heureuse d'être comme toi. Tu veux être ma doublure ?"
      },
      {
        name: "P.K",
        traits: [69, 24, 0, 24, 38, 17, 48, 38, 21, 69, 0, 97, 17, 52],
        image: "https://i.ibb.co/S74hLzkG/P-K-Avatar.png", // Replace with your own
        quote: "P.K. Même pas Phanishwar, P.K. Eh beh, je te félicite pas."
      },
      {
        name: "Seto Watson",
        traits: [48, 93, 90, 3, 93, 55, 28, 21, 83, 93, 45, 45, 55, 3],
        image: "https://i.ibb.co/wZQvBKbs/Seto-Watson-Avatar.png", // Replace with your own
        quote: "Ultime assassin devenu le boytoy de Valentine tel Kirboo l'est pour Toady. Étrangement, c'est une meilleure fin que 99% des autres personnages."
      },
      {
        name: "Soo-Yun Kim",
        traits: [86, 14, 3, 34, 45, 3, 10, 17, 3, 14, 48, 90, 3, 3],
        image: "https://i.ibb.co/nqNn02kV/Soo-Yun-Kim-Avatar-2.png", // Replace with your own
        quote: "<br><a href=\"https://www.internet-signalement.gouv.fr/PharosS1/\" target=\"_blank\">...</a>"
      },
      {
        name: "Summer Hiverno",
        traits: [3, 86, 83, 79, 52, 31, 31, 24, 48, 34, 79, 69, 83, 0],
        image: "https://i.ibb.co/9k8njjn1/Summer-Hiverno-Avatar-2.png", // Replace with your own
        quote: "Elle est timide, elle est gentille, elle s'est fait friendzone par Aislinn. Elle est vraiment incroyable Summer Hiverno."
      },
      {
        name: "Valentine Dauclerq",
        traits: [34, 100, 97, 38, 52, 97, 97, 90, 72, 31, 83, 55, 100, 55],
        image: "https://i.ibb.co/pv68CQwz/Valentine-Dauclerq-Avatar-2.png", // Replace with your own
        quote: "Le terme « waifu » vient du mot japonais « 妻 » qui signifie « épouse ». Il a été adopté par les fans d’anime et de manga pour désigner leurs personnages féminins préférés. C’est à l’origine une déformation de la prononciation japonaise du mot anglais « wife »."
      },
      {
        name: "Ezekiel",
        traits: [76, 0, 93, 0, 0, 24, 0, 55, 24, 59, 97, 7, 21, 28],
        image: "https://i.ibb.co/JFtGrsQC/Ezekiel-Avatar.png", // Replace with your own
        quote: "Nous avons demandé à ChatGPT de nous expliquer le personnage d'Ezekiel et notre serveur a explosé."
      },
      {
        name: "Luna Stillwell",
        traits: [7, 34, 48, 69, 45, 41, 14, 0, 14, 24, 7, 86, 48, 24],
        image: "https://i.ibb.co/Fbsskj07/Luna-Stillwell-Avatar.png", // Replace with your own
        quote: "Je suis pas venue ici pour souffrir, ok ?!"
      },
      {
        name: "Neil Pursley",
        traits: [83, 3, 7, 10, 69, 52, 55, 48, 38, 28, 10, 52, 41, 41],
        image: "https://i.ibb.co/RGXKGbqx/Neil-Pursley-Avatar.png", // Replace with your own
        quote: "Tu fais 50 blagues, mais personne ne t'appelle Neil le blagueur. Par contre tu tue quelqu'un et trahis ta meilleure amie UNE FOIS et là tout de suite-"
      },
      {
        name: "Orfilia Beowulf",
        traits: [100, 0, 69, 14, 3, 90, 24, 66, 7, 38, 21, 14, 55, 79],
        image: "https://i.ibb.co/tpg5Jbnf/Orfilia-Beowulf-Avatar.png", // Replace with your own
        quote: "Plus elle tue, plus elle est populaire, appellez la Jeffrey Dahmer 2."
      },
      {
        name: "Rowan Finnegan",
        traits: [62, 66, 45, 83, 79, 38, 83, 48, 90, 55, 93, 28, 69, 38],
        image: "https://i.ibb.co/7Nv19zdQ/Rowan-Finnegan-Avatar.png", // Replace with your own
        quote: "360° Noscoped, rip bozo."
      },
      {
        name: "Sibert Hauke",
        traits: [10, 38, 38, 55, 76, 21, 48, 0, 45, 28, 59, 34, 48, 28],
        image: "https://i.ibb.co/hxVgj4N8/Sibert-Hauke-Avatar-2.png", // Replace with your own
        quote: "-Sinon tu veux pas faire quelque chose de ta vie Sibert ??? -Non."
      },
      {
        name: "Vassily Selenius",
        traits: [41, 52, 62, 31, 31, 48, 28, 52, 97, 97, 14, 10, 14, 14],
        image: "https://i.ibb.co/TBCJBBvq/Vassily-Selenius-Avatar.png", // Replace with your own
        quote: "Seul raciste sympathique au monde."
      },
      {
        name: "Yolanda Freiheit",
        traits: [100, 7, 28, 97, 14, 93, 86, 97, 66, 90, 24, 21, 10, 34],
        image: "https://i.ibb.co/n8tmjYr1/Yolanda-Freiheit-Avatar.png", // Replace with your own
        quote: "Gatekeep, Gaslight, Girlboss."
      }
    ];

    function getUserVector() {
      return [
        parseInt(document.getElementById("trait1").value),
        parseInt(document.getElementById("trait2").value),
        parseInt(document.getElementById("trait3").value),
        parseInt(document.getElementById("trait4").value),
        parseInt(document.getElementById("trait5").value),
        parseInt(document.getElementById("trait6").value),
        parseInt(document.getElementById("trait7").value),
        parseInt(document.getElementById("trait8").value),
        parseInt(document.getElementById("trait9").value),
        parseInt(document.getElementById("trait10").value),
        parseInt(document.getElementById("trait11").value),
        parseInt(document.getElementById("trait12").value),
        parseInt(document.getElementById("trait13").value),
        parseInt(document.getElementById("trait14").value),
      ];
    }

    function cosineSimilarity(vecA, vecB) {
      let dot = 0, magA = 0, magB = 0;
      for (let i = 0; i < vecA.length; i++) {
        dot += vecA[i] * vecB[i];
        magA += vecA[i] ** 2;
        magB += vecB[i] ** 2;
      }
      return dot / (Math.sqrt(magA) * Math.sqrt(magB));
    }

    document.getElementById("submitBtn").addEventListener("click", function () {
      const userVector = getUserVector();

      const matches = characters.map(character => {
        return {
          ...character,
          score: cosineSimilarity(userVector, character.traits)
        };
      });

      // Sort from highest similarity to lowest
      matches.sort((a, b) => b.score - a.score);

      const topMatch = matches[0];

      // Show top match
      document.getElementById("resultName").innerText = `Tu ressemble le plus à: ${topMatch.name}`;
      document.getElementById("resultQuote").innerHTML = `"${topMatch.quote}"`;
      document.getElementById("resultImage").src = topMatch.image;
      document.getElementById("resultImage").style.display = 'block';

      // Show ranking list
      const rankingDiv = document.getElementById("resultRanking");
      rankingDiv.innerHTML = "<h4>Classement Complet:</h4><ol>" +
        matches.map(m => `<li>${m.name} (${(m.score * 100).toFixed(2)}%)</li>`).join("") +
        "</ol>";
    });
  </script>
</body>
</html>
