---
layout: default
title: Portfolio
---

# Non-Maker Projects

I'm curious about nearly everything. I love drawing, writing poetry, thinking about philosophy (mostly political, mind, and ethics currently), complexity theory (*currently on a binger unifying assembly theory with the emergence of cognition*), furniture design, creative graphic design, wood working, and so many others, I can't list them and I'm not going to bore you to death clicking through endless projects.

While these interests aren't directly tied to my core focus on robotics, they certainly inspire and shape it ([e.g. Freudian repression used in continual learning](https://portfolio.colebjohnson.com/research#real-time-balancing-of-stability-and-plasticity-in-continual-learning-applied-to-adaptive-speed-estimation-controllers-for-lower-limb-prostheses)). Someday, I hope robotics might return the favor and offer us new insights into philosophy and other fields as well.

---

<div class="portfolio-grid">
  <!-- Project 0 -->
  <div class="portfolio-card" onclick="toggleModal('modal0')">
    <h2>Artwork</h2>
    <p>Sketching &middot; Ink &middot; Painting</p>
  </div>
  
  <!-- Project 1 -->
  <div class="portfolio-card" onclick="toggleModal('modal1')">
    <h2>Tomorrow's Utopia Book</h2>
    <p>Political Philosophy &middot; Ethics</p>
  </div>

  <!-- Project 2 -->
  <div class="portfolio-card" onclick="toggleModal('modal2')">
    <h2>On The Emergence of Cognition From Complexity</h2>
    <p>Assembly & Complexity Theory</p>
  </div>

  <!-- Project 3 -->
  <div class="portfolio-card" onclick="toggleModal('modal2.5')">
    <h2>Woodworking & Rocket Engine</h2>
    <p>Chess Board &middot; SLA Printing &middot; Mallet</p>
  </div>

  <!-- Project 4 -->
  <div class="portfolio-card" onclick="toggleModal('modal3.5')">
    <h2>Nature's Gifts & The Phaethon</h2>
    <p>Theory of the Mind &middot; Epistemology &middot; Ethics</p>
  </div>

  <!-- Project 4 -->
  <div class="portfolio-card" onclick="toggleModal('modal4')">
    <h2>Graphic & Furniture Design</h2>
    <p>Blender &middot; Woodworking &middot; Rendering</p>
  </div>

<!-- Modals -->
<div id="modal0" class="modal">
  <div class="modal-content">
    <button class="close-btn" onclick="toggleModal('modal0')">&times;</button>
    <h2>Artwork</h2>
    <p> In Process of Scanning All of Them (there're a lot). Page Coming Soon!</p>
  </div>
</div>

<div id="modal1" class="modal">
  <div class="modal-content">
    <button class="close-btn" onclick="toggleModal('modal1')">&times;</button>
    <h2>Tomorrow's Utopia: How Decentralization and Artificial Intelligence Can Bring an End to the Cycle of Ideological Tribalism</h2>
    <div class="two-column">
      <div class="text-column">
        <p>This is my high school attempt at postulating of a redesign of social structure. <a href="https://www.amazon.com/Tomorrows-Utopia-Decentralization-Intelligence-Ideological/dp/107461772X" target="_blank">See it here</a><br><br>
        <strong>Thesis</strong>: Of humans’ most influential evolutionary traits, we are hurt most by our need for other cultures and groups to be villainized in order to achieve coexistence. Our current conception of government as a centralized ruling body only enforces this as every government must appeal to its constituents in the short-term, thus exacerbating already present dispositions. However, along with the imminent development of human-level artificial intelligence, a different social structure emerges: a decentralized government. Increasing liberties, power of voice, accountability, efficiency, etc., of constituents and the state, the dissemination of the responsibilities of government has the potential to bring an end to the cycle of ideological tribalism in the future. Taking a philosophical, yet pragmatic approach, this book attempts to lay the foundations for how society must evolve in order to avoid the impending dystopia that humanity has created for itself and now faces.</p>
      </div>
      <div class="image-column">
        <img src="images/cover.png" alt="body Render" loading="lazy">
      </div>
    </div>
  </div>
</div>

<div id="modal2" class="modal">
  <div class="modal-content">
    <button class="close-btn" onclick="toggleModal('modal2')">&times;</button>
    <h2>On The Emergence of Cognition from Complexity</h2>
    <div>
      <h3>This project is ongoing, hoping to wrap up by December into a nice paper!</h3>
      <h3>Description</h3>
      <p>This paper explores how cognition emerges from the complexity inherent in biological and physical systems, examining theories that explain life’s resistance to entropy and its assembly through unique selection mechanisms. It builds on Schrödinger’s view of life as an entropy-fighting system and Assembly Theory’s focus on complexity arising from selection, asserting that real-world complexity results from the integration of both views.</p>
      <h3>Main Concepts</h3>
      <ul>
        <li><strong>Life and Entropy</strong>: Schrödinger’s theory posits that life defies entropy through energy consumption to maintain order, while Assembly Theory suggests life’s complexity arises via selection mechanisms that cannot occur randomly. By unifying these ideas, the paper explains how hierarchical selection processes contribute to dynamic complexity in biological systems.</li>
        <li><strong>Phase Transitions in Complexity</strong>: Complexity grows explosively during phase transitions, where systems discover new energy channels that support increasingly complex structures. These transitions, as theorized by Kauffman, allow systems to evolve from simpler states to intricate self-replicating structures, setting the stage for the emergence of cognition.</li>
        <li><strong>Cognition as a Phase Transition</strong>: Cognition is proposed as a unique phase transition that builds on prior evolutionary stages, such as stellar and biological evolution. This transition involves new 'units' of information processing—ideas—that operate under selection pressures, forming cognitive systems that optimize between stability and adaptability.</li>
      </ul>
      <h3>Theoretical Extension</h3>
      <p>The paper critiques Assembly Theory, arguing it lacks a mechanism for handling the unique cost and complexity of cognitive processes. It introduces an extension, "Extended Assembly Theory," to account for temporal costs, compression dynamics, and a contextual density threshold, enhancing the framework to better describe cognition and abstract thought.</p>
      <h3>Where This Research Leads</h3>
      <p>This framework’s implications are far-reaching, potentially explaining the emergence of consciousness, cultural evolution, and even digital information networks. The paper concludes by contextualizing cognition and complexity within a cosmological framework, suggesting that these processes mirror larger negentropic patterns in the universe.</p>
    </div>
  </div>
</div>

<div id="modal2.5" class="modal">
  <div class="modal-content">
    <button class="close-btn" onclick="toggleModal('modal2.5')">&times;</button>
    <h2>Rocket Engine</h2>
    <div class="three-image-row">
      <img src="images/motor3.png" alt="Image 1" loading="lazy">
      <img src="images/motor1.png" alt="Image 2" loading="lazy">
      <img src="images/motor2.png" alt="Image 3" loading="lazy">
    </div>
    <h2>Chess Board</h2>
    <div class="medium-image-row">
      <img src="images/chessrender1.png" alt="Image 1" loading="lazy">
      <img src="images/chessrender2.png" alt="Image 2" loading="lazy">
    </div>
    <div class="three-image-row">
      <img src="images/chesstiles1.png" alt="Image 1" loading="lazy">
      <img src="images/chesstiles2.png" alt="Image 2" loading="lazy">
      <img src="images/chessbase.png" alt="Image 3" loading="lazy">
    </div>
    <div class="medium-image-row">
      <img src="images/chesscorner.png" alt="Image 1" loading="lazy">
      <img src="images/chesswithdrawers.png" alt="Image 2" loading="lazy">
    </div>
    <div class="three-image-row">
      <img src="images/chessfinal1.png" alt="Image 1" loading="lazy">
      <img src="images/chessfinal2.png" alt="Image 2" loading="lazy">
      <img src="images/chessboard2.png" alt="Image 3" loading="lazy">
    </div>
    <h2>Boxes, Mallet, etc.</h2>
    <div class="medium-image-row">
      <img src="images/box2.png" alt="Image 1" loading="lazy">
      <img src="images/box1.png" alt="Image 2" loading="lazy">
    </div>
    <div class="three-image-row">
      <img src="images/mountains.png" alt="Image 1" loading="lazy">
      <img src="images/stand.png" alt="Image 2" loading="lazy">
      <img src="images/mallet.png" alt="Image 3" loading="lazy">
    </div>
  </div>
</div>

<div id="modal3.5" class="modal">
  <div class="modal-content">
    <button class="close-btn" onclick="toggleModal('modal3.5')">&times;</button>
    <h2>Nature's Gifts</h2>
    <div class="two-column">
      <div class="text-column">
        <p>I was curious about how nature itself grows epistemological constraints over our existence, so I wrote a poem about the most abstracted cases of these bonds. It's not an actual poem by structure, but that's the closest term I could call it. <a href="images/naturesgifts.pdf" target="_blank">Read it here</a>.</p>
        <h2>The Phaethon</h2>
        <p>This is a mythic journey through humanity’s evolution from primitive survival to complex societies marked by cycles of power and collapse. Initially, humanity emerges from its primitive state, empowered by divine gifts, but soon descends into internal conflict, enslaving and subjugating one another. This conflict gives rise to a hierarchical structure, eventually culminating in the birth of a republic based on freedom and self-rule. As society advances technologically, ideological divides deepen; some embrace artificial intelligence for governance and social equality, while others resist, leading to intense societal rifts. The resulting "moral war" forces both factions to confront the consequences of their dependence on AI and the ethical implications of altering human consciousness. In the end, disillusioned and weary, humanity returns to a simpler, almost primal existence, setting the stage for the cycle of societal rise and fall to begin anew.<br><br> It was one of my first writings and I'm quite fond of it, although it's very roughly written. <a href="images/phaethon.pdf" target="_blank">Read it here</a>.</p>
      </div>
      <div class="image-column">
        <img src="images/naturesgifts.png" alt="Leather Script" loading="lazy">
      </div>
    </div>
  </div>
</div>

<div id="modal4" class="modal">
  <div class="modal-content">
    <button class="close-btn" onclick="toggleModal('modal4')">&times;</button>
    <h2>Blender Projects</h2>
    <div class="three-image-row">
      <img src="images/Initial.png" alt="Image 1" loading="lazy">
      <img src="images/Half.png" alt="Image 2" loading="lazy">
      <img src="images/Final.png" alt="Image 3" loading="lazy">
    </div>
    <div class="centered-image">
      <img src="images/LivingRoom.png" alt="Image 2" loading="lazy">
    </div>
    <div class="medium-image-row">
      <img src="images/LampPost.png" alt="Image 1" loading="lazy">
      <img src="images/Portal.png" alt="Image 3" loading="lazy">
    </div>
    <h2>Furniture Designs</h2>
    <div class="three-image-row">
      <img src="images/table1.png" alt="Image 1" loading="lazy">
      <img src="images/table2.png" alt="Image 2" loading="lazy">
      <img src="images/table3.png" alt="Image 3" loading="lazy">
    </div>
    <div class="three-image-row">
      <img src="images/chair1.png" alt="Image 1" loading="lazy">
      <img src="images/chair3.png" alt="Image 2" loading="lazy">
      <img src="images/chair4.png" alt="Image 3" loading="lazy">
    </div>
    <div class="three-image-row">
      <img src="images/drawer7.png" alt="Image 1" loading="lazy">
      <img src="images/drawer9.png" alt="Image 2" loading="lazy">
      <img src="images/drawer10.png" alt="Image 3" loading="lazy">
    </div>
  </div>
</div>


<!-------------------------------------------- JS & Stylings -------------------------------------------->

<!-- JavaScript for Modal Toggle -->
<script>
  function toggleModal(modalId) {
    const modal = document.getElementById(modalId);
    if (modal) {
      const isVisible = modal.classList.contains("show-modal");
      modal.classList.toggle("show-modal", !isVisible);
      document.body.classList.toggle("modal-open", !isVisible);
    }
  }

  // Close modal when clicking outside of it
  window.addEventListener('click', function(event) {
    const modals = document.querySelectorAll('.modal');
    modals.forEach((modal) => {
      if (event.target === modal) {
        modal.classList.remove("show-modal");
        document.body.classList.remove("modal-open");
      }
    });
  });
</script>

<!-- CSS for the modal and portfolio grid -->
<!-- CSS for the modal and portfolio grid with fade-in/out effect and adjusted text sizes -->
<style>
/* Portfolio Grid */
.three-image-row {
    display: flex;
    justify-content: space-between;
    gap: 10px;
    margin-bottom: 20px;
}

.three-image-row img {
    width: 32%; /* Adjust each image to take up about a third of the container width */
    height: auto;
    max-width: 32%; /* Prevent the image from exceeding its container */
    border-radius: 4px;
    object-fit: contain;
    
}

  .centered-image {
    display: block;           /* Makes image act like a block-level element */
    margin: 0 auto;           /* Centers the image horizontally */
    width: 50%;               /* Sets image width to 50% of its container */
    max-width: 50%;          /* Ensures image does not exceed container width */
    height: auto;             /* Maintains the aspect ratio */
}

/* Modal Content Styling */
.modal-content {
    background-color: #fff;
    border-radius: 8px;
    padding: 20px;
    width: 80vw;
    height: auto;
    position: relative;
    text-align: left;
    overflow-y: auto;
    max-height: 80vh;
    box-sizing: border-box;
}

/* Two-Column Layout for First Section */
.two-column {
    display: grid;
    grid-template-columns: 1fr 1fr; /* Two equal-width columns */
    gap: 20px;
    margin-bottom: 20px;
}

.text-column {
    /* No additional alignment styling needed */
}

.image-column img {
    width: 100%; /* Make the image take up full width of the column */
    height: auto;
    border-radius: 4px;
}

/* Image Row Styling for other sections */
.image-row {
    display: flex;
    justify-content: space-between;
    gap: 10px;
    margin-bottom: 20px;
}

.image-row img {
    width: 48%;
    height: auto;
    border-radius: 4px;
}

.small-image-row {
    display: flex;
    justify-content: space-around;
    align-items: flex-start; /* Align images to the top of the row */
    gap: 10px;
    margin-bottom: 20px;
}

.small-image-row img {
    width: 48%; /* Scale these images to 48% of the container width */
    max-width: 20%; /* Prevent the image from exceeding its container */
    height: auto; /* Maintain aspect ratio */
    border-radius: 4px;
    object-fit: contain; /* Ensures aspect ratio is maintained without stretching */
}

.medium-image-row {
    display: flex;
    justify-content: center; /* Center the group horizontally */
    align-items: center; /* Center images of different heights vertically */
    gap: 10px;
    margin-bottom: 20px;
}

.medium-image-row img {
    width: 48%; /* Scale these images to 48% of the container width */
    max-width: 50%; /* Prevent the image from exceeding its container */
    height: auto; /* Maintain aspect ratio */
    border-radius: 4px;
    object-fit: contain; /* Ensures aspect ratio is maintained without stretching */
}


  /* Portfolio Grid */
  .portfolio-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    max-width: 100%;
    margin-top: 20px;
  }

  .portfolio-card {
    background-color: #ffffff;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 15px;
    text-align: center;
    transition: transform 0.2s;
    cursor: pointer;
    width: auto;
  }

  .portfolio-card:hover {
    transform: translateY(-5px);
  }

  .portfolio-card img {
    width: 100%;
    height: auto;
    border-radius: 4px;
    margin-bottom: 10px;
  }

  .portfolio-card h2 {
    font-size: 1.2em; /* Original font size for project titles */
    margin: 10px 0;
  }

  .portfolio-card p {
    font-size: 0.95em; /* Original font size for project descriptions */
    color: #555;
  }

  /* Modal Styles */
  .modal {
    display: flex;
    justify-content: center;
    align-items: center;
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background-color: rgba(0, 0, 0, 0.8);
    opacity: 0;
    visibility: hidden;
    transition: opacity 0.3s ease, visibility 0.3s ease;
    z-index: 1000;
  }

  .show-modal {
    opacity: 1;
    visibility: visible;
  }

  .show-modal .modal-content {
    transform: scale(1);
  }

  .modal-content img {
    width: 100%;
    height: auto;
    border-radius: 4px;
    margin-top: 10px;
  }

  .modal-content h2 {
    margin-top: 0;
  }

  .close-btn {
    position: absolute;
    top: 10px;
    right: 15px;
    font-size: 28px;
    color: #333;
    background: none;
    border: none;
    cursor: pointer;
    z-index: 10;
  }

  .modal-open {
    overflow: hidden;
  }
</style>
