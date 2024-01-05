<script
  src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"
  integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL"
  crossorigin="anonymous"
></script>

<div class="card-container">
  <!-- Card1 -->
  <div class="card w-75 mb-3">
    <div class="card-body">
      <h5 class="card-title">HIRO</h5>
      <p class="card-text">Your Personal Healthcare Companion :D</p>
      <a
        href="https://github.com/vivek09thakur/HIRO"
        target="_blank"
        class="btn btn-primary">View On Github</a
      >
    </div>
  </div>

  <div class="card w-75 mb-3">
    <div class="card-body">
      <h5 class="card-title">PANDA</h5>
      <p class="card-text">Paradigm based Artificial Neural Dailog Agent</p>
      <a
        href="https://github.com/vivek09thakur/PANDA"
        target="_blank"
        class="btn btn-primary">View On Github</a
      >
    </div>
  </div>

  <div class="card w-75 mb-3">
    <div class="card-body">
      <h5 class="card-title">ELSA</h5>
      <p class="card-text">Enhanced Language Sequence Agent (ELSA)</p>
      <a
        href="https://github.com/vivek09thakur/ELSA"
        target="_blank"
        class="btn btn-primary">View On Github</a
      >
    </div>
  </div>

  <div class="card w-75 mb-3">
    <div class="card-body">
      <h5 class="card-title">LearnIT</h5>
      <p class="card-text">
        An open source free of cost learning platform for all the computer
        science students pursuing their diplomas.
      </p>
      <a
        href="https://learnit-io.vercel.app/"
        target="_blank"
        class="btn btn-primary">Visit Website</a
      >
    </div>
  </div>
</div>

<style lang="css3">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css");
  .card-container{
    margin: auto;
    width:70%;
    height: 70%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
    flex-wrap: wrap;
  }
  .card {
    font-family: "Poppins", sans-serif;
    border-radius: .2rem !important;
    width: 33% !important;
    min-height: 33% !important;
    margin: 2%;
  }
  .card:hover{
    transform: scale(1.03);
    transition: all 0.3s ease-in-out;
  }
  .card .card-title {
    font-size: 100% !important;
    color: #202123;
  }
  .card .card-text{
    font-size: 85% !important;
    opacity: .8;
  }
  .btn{
    border-radius: .2rem !important;
    
  }
  .btn-primary{
    font-size: 75% !important;
    opacity: .8;
    background: #810dfd !important;
    outline: #810dfd !important;
    border: #810dfd !important;
  }

  @media (max-width:750px){
    .card-container{
      width: 100%;
    }
    .card{
      width: 45% !important;
    }
  }
</style>
