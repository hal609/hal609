### Heya 👋

- 🌱 Working on my MSc. at MMU
- ✨ They/She
- 🔭 You can see some of my projects below
- ❤️ Feel free to reach out to me here or email hal@kolb.co.uk

<style>
/* Base styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  padding-top: var(--header-height-small);
  color: var(--primary-color);
  background-color: var(--secondary-color);
  line-height: 1.4;
  min-height: 100vh
}
/* Grid Formatting */
.grid {
  padding: 5%;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 3%;
}

@media screen and (max-width: 500px) {
  .grid {
    grid-template-columns: repeat(2, 1fr);
  }
}


.square {
  aspect-ratio: 1/ 1;
  border-radius: 5px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 10%;
  background-color: #1E1E1E;
  color: #fff;
  margin: 0;
  filter: saturate(1.1);
  filter: contrast(1.1);
}

.square:hover {
  aspect-ratio: 1/ 1;
  border-radius: 5px;
  display: flex;
  flex-direction: column;
  filter: saturate(0.2);
  filter: contrast(1.9);
  filter: brightness(1.1);
  align-items: flex-start;
  padding: 10%;
  background-color: #1E1E1E;
  color: #fff;
  margin: 0;
}

.square img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  object-position: center;
  padding: 0;
}

.square.fullImg {
  padding: 0;
  position: relative;
  width: auto;
}

.square.fullImg img {
  object-fit: cover;
  border-radius: 5px;
}

.top-row {
  display: flex;
  position: absolute;
  align-items: center;
  padding: 3px;
  width: 20%;
  height: auto;
  border-radius: 5px 0px 5px 0px;
  background-color: #000000aa;

}
</style>
<div class="grid">
    <a href="www.hkolb.co.uk/cube_guy.html">
      <div class="square fullImg">
        <img src="cube_guy.avif" />
        <div class="top-row">
          <img class="item1" src="Godot_icon.svg">
        </div>
      </div>
    </a>
    <a href="https://github.com/Hal609/Ray-Trace-Cpp">
      <div class="square fullImg">
        <img src="raytrace_icon3.avif" />
        <div class="top-row">
          <img class="item1" src="cpp_logo.svg">
        </div>
      </div>
    </a>
    <a href="www.hkolb.co.uk/llic.html">
      <div class="square fullImg">
        <img src="women_in_computing.avif" />
        <div class="top-row">
          <img class="item1" src="document.svg">
        </div>
      </div>
    </a>
    <a href="www.hkolb.co.uk/minesweeper.html">
      <div class="square fullImg">
        <img src="minesweeper_square_icon.avif" />
        <div class="top-row">
          <img class="item1" src="Godot_icon.svg">
        </div>
      </div>
    </a>
    <a href="www.hkolb.co.uk/song_creator.html">
      <div class="square fullImg">
        <img src="song_creator_icon_square.avif" />
        <div class="top-row">
          <img class="item1" src="python_two_tone.svg">
        </div>
      </div>
    </a>
    <a href="www.hkolb.co.uk/website.html">
      <div class="square fullImg">
        <img src="site_screenshot_6.avif" />
        <div class="top-row">
          <img class="item1" src="html-1.svg">
        </div>
      </div>
    </a>
    <a href="www.hkolb.co.uk/house_jobs.html">
      <div class="square fullImg">
        <img src="house_jobs_icon.avif" />
        <div class="top-row">
          <img class="item1" src="Google-flutter-logo.svg"">
      </div>
    </div>
    </a>  
    <a href="www.hkolb.co.uk/cloak.html">
          <div class="square fullImg">
            <img src="macIcon.png" />
            <div class="top-row">
              <img class="item1" src="Godot_icon.svg">
            </div>
          </div>
    </a>
  </div>