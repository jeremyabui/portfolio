# portfolio
Portfolio website
Technologies used:
HTML, CSS, JS, Bootstrap

Your process/approach.
My approach for this portfolio was to create a simple and clean one page portfolio. I started by making the sidebar and the landing section. From there, I made each individual section for the my experience, projects, skills, and contact. I incorportated some bootstrap to make the project screenshots a carousel. Once the layout was done, I focused on the styling to make the page a little nicer while still keeping a simple design. 

Unsolved problems.
Waiting for headshot photo. 

Your biggest wins and challenges.
I was happy with the style of my portfolio since I feel like CSS in one of the areas I have a lot to improve on. 

Screenshots of the snippets of code you used to solve particularly interesting problems (think code highlights)
Carousel code: 
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
        <div class="carousel-item active">
            <a href="https://pages.git.generalassemb.ly/jbui/blackjack-project-zero/">
                <img class="d-block w-100" src="project_screenshots/Blackjack.png" alt="Blackjack">
            </a>
        </div>
        <div class="carousel-item">
            <a href="https://illegalmemeexchange.herokuapp.com/">
                <img class="d-block w-100" src="project_screenshots/Illegal_meme_exchange.png" alt="Illegal Meme Exchange">
            </a>
        </div>
        <div class="carousel-item">
            <a href="https://wayfarer-damnbros.herokuapp.com/">
                <img class="d-block w-100" src="project_screenshots/Wayfarer.png" alt="Wayfarer">
            </a>
        </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
