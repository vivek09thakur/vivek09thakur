<div class="container">

    <div class="project-card">
        <h3>HIRO</h3>
        <p>Your personal healthcare companion</p>
        <a href="https://github.com/vivek09thakur/HIRO" target="_blank">View on Github</a>
    </div>

    <div class="project-card">
        <h3>PANDA</h3>
        <p>Paradigm based Artificial Neural Dailog Agent</p>
        <a href="https://github.com/vivek09thakur/PANDA" target="_blank">View on Github</a>
    </div>

    <div class="project-card">
        <h3>ELSA</h3>
        <p>Enhanced Language Sequence Agent</p>
        <a href="https://github.com/vivek09thakur/ELSA" target="_blank">View on Github</a>
    </div>

    <div class="project-card">
        <h3>LearnIT</h3>
        <p>An open source free of cost learning platform for all the computer science students pursuing their diplomas</p>
        <a href="https://learnit-io.vercel.app/" target="_blank">Visit Website</a>
    </div>

</div>

<style lang="css3">
    .container{
        width:70%;
        margin: 0 auto;
    }
    .project-card{
        font-family: 'Poppins', sans-serif;
        background: #2b3962;
        padding: .5rem 1rem 1rem 1rem;
        margin: 20px 0;
        border-radius: .5rem;
    }
    .project-card:hover{
        transform: scale(1.05);
        transition: all .5s ease-in-out;
        position: relative;
        z-index: 1;
        box-shadow: 0 0 20px rgba(0,0,0,.5);
    }
    .project-card h3{
        margin: 0 !important;
        font-weight: 300;
        letter-spacing: 1px;
    }
    .project-card p{
        margin: 0 !important;
        font-size: 85%;
        padding:.5rem 0 1rem 0;
        letter-spacing: 1px;
        opacity: .8;
    }
    .project-card a{
        text-decoration: none;
        font-family:'JetBrains Mono', monospace;
        color: #fff;
        background: #1e2a47;
        margin: auto .3rem;
        padding: .5rem 1rem;
        border-radius: .5rem;
    }

    @media only screen and (max-width: 600px) {
        .container{
            width:90%;
        }
    }

</style>