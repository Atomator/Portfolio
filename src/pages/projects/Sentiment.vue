<template>
<!-- Basic app page to sit on the site for now -->
  <div id="app">
    <div class="container project-header">
      <div class="columns is-vcentered">
        <div class="column is-one-half">
          <div id="main" class="pull-right">
            <h1 class="project-title">Sentiment<strong class="has-text-primary">.</strong> </h1>
            <h2 class="subtitle has-text-weight-medium">
              Machine Learning. Meet Mental Health.
            </h2>
            <!-- <a class="button-primary" href="https://www.youtube.com/watch?v=MMX9esKbbkc&list=PLCseOl6jsv2oRbhZzk3ZvgrnswPK12wim&index=6">
              <a class="icon">
                <img src="../../assets/media icons/youtube.svg" class="logo">
              </a>
            </a> -->
            <a class="button-primary" href="https://connorsparks.medium.com/ui-ux-design-for-a-micro-journaling-application-b74c9d2c8d1b">
              <a class="icon">
                <img src="../../assets/media icons/medium.svg" class="logo">
              </a>
            </a>
            <a class="button-primary" href="https://github.com/sentimentapp/application">
              <a class="icon">
                <img src="../../assets/media icons/github.svg" class="logo">
              </a>
            </a>
          </div>  
        </div>
        <div class="column is-one-half has-text-centered">
          <img class="is-vertical-center" src="../../assets/images/sentiment-cover.png" width="60%">
        </div>
      </div>
    </div>
    <div class="container">
      <div class="tile-centered-primary">
        <p class="title-light" style="margin-bottom: 5px;">Skills</p>
        <p class="has-text-white-ter" style="margin-bottom: 30px;">VueJS, HTML, CSS, CapacitorJS, Tensorflow/Keras</p>
        <p class="title-light" style="margin-bottom: 5px;">Project Duration</p>
        <p class="has-text-white-ter">June 2020 - December 2020</p>
      </div>
    </div>
    <div class="container has-text-centered">
      <p class="section-title-primary">Why</p>
      <br>
      <p>Throughout High School, I've had my struggles with mental health. In my battles against the forces of anxiety and depression, I've tried various weapons, but one of these tools has always stuck with me: journaling. In my life, journaling has become a way to ground myself, because writing forces the dark and ephemeral thoughts in my mind to become concrete and definable issues that I can tackle. As such, when I was offered the oppertunity to intern with the Colorado School of Mine's Computing 4 Good (C4G) program, I was able to draw upon my own personal experience to propose that my team create Sentiment: a journaling app that uses machine learning to classify the emotions of entries to help the user track their mental state.</p>
    </div>
    <div class="container">
      <div class="tile-column-dark is-vcentered">
        <div class="column has-text-centered">
          <p class="section-title-light">The Team</p>
          <p class="has-text-light">During the C4G internship, I was paired with a group of four students and as such, it was important that we figured out our group dynamic from the get-go. As a team, we split into three micro-groups, each one responsible for a different aspect of the application: UI/UX, app development, and the machine learning model. Due to my previous design work, I became the head of the UI/UX section of the project. However, I also worked with the app development and machine learning teams to help complete the application. Along with our micro-teams, we agreed to meet three times a week to check in on our progress, using Trello as our task manager of choice.</p>
        </div>
        <div class="column">
          <img src="../../assets/images/sentiment-trello.png" alt="driveline-code">
        </div>
      </div>
   </div>
    <div class="container has-text-centered">
      <p class="section-title-primary">Creation</p>
      <p class="has-text-dark title-dark" style="margin-bottom: 25px;">Idea</p>
      <p style="margin-bottom: 100px;">The purpose of the application was to act as a demo for positional tracking on mobile, meaning the experience created couldn’t rely on controllers. Using Richie’s Plank Experience as a guide, the app would start by having user based in a virtual city. From there they would enter an elevator that would begin to move up a building and when it reached the top they would be presented with a plank they could walk. The game would end when they fell and hit the ground.</p>
      <p class="has-text-dark title-dark" style="margin-bottom: 25px;">Timeline</p>
      <div class="timeline is-centered">
        <header class="timeline-header">
          <span class="tag is-medium is-primary has-text-white-ter" style="font-size: 20px; font-weight: 900; border-radius: 10px; padding: 0px 30px 0px 30px;">Start</span>
        </header>
        <div class="timeline-item is-primary">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content has-text-left">
            <p class="heading">Research</p>
            <p>Inspired by the project by Github Repository by Andrew Nakas I choose to use Unity as my workspace of choice with his work as a guide.</p>
          </div>
        </div>
        <div class="timeline-item is-primary">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content">
            <p class="heading">Nature Assets</p>
            <p>I started by testing the tracking by creating a nature environment using free Unity Assets, but it failed to convey the feelings of immersion that I wanted.</p>
          </div>
        </div>
        <div class="timeline-item is-primary">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content has-text-left">
            <p class="heading">Blender</p>
            <p>Even though I had never used Blender before I quickly learned the basics and I was able to create buildings for the city in under four days, and the city itself in under seven.</p>
          </div>
        </div>
        <div class="timeline-item is-primary">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content">
            <p class="heading">Placement</p>
            <p>Unity’s ARFoundation tutorial helped me to figure out how I was going to “place” the virtual environment in order to make sure the users height was correct.</p>
          </div>
        </div>
        <div class="timeline-item is-primary">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content has-text-left">
            <p class="heading">Moving Up</p>
            <p>At this point I created the elevator itself, having it close its doors and begin moving up upon user entry.</p>
          </div>
        </div>
        <div class="timeline-item is-primary">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content">
            <p class="heading">Falling Down</p>
            <p>I then added in “gravity” to allow the user to fall when the exit the elevator and then fall off the plank.</p>
          </div>
        </div>
        <div class="timeline-item is-primary">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content has-text-left">
            <p class="heading">VR</p>
            <p>I then added in the VRKit (ARKit + GVR) SDK to allow for the user to trigger VR when inside the elevator.</p>
          </div>
        </div>
        <div class="timeline-item is-primary">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content">
            <p class="heading">UI</p>
            <p>Once the experience was completed I created a main menu system that the user was greeted with upon entering the app.</p>
          </div>
        </div>
        <div class="timeline-item is-primary">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content has-text-left">
            <p class="heading">App</p>
            <p>Creating an app icon, I proceeded to load the final version onto my phone and then share my creation with others.</p>
          </div>
        </div>
        <header class="timeline-header" style="margin-bottom: 100px;">
          <span class="tag is-medium is-primary has-text-white-ter" style="font-size: 20px; font-weight: 900; border-radius: 10px; padding: 0px 30px 0px 30px;">End</span>
        </header>
      </div>
      <a class="button is-primary is-large has-shadow" style="margin-right: 0px;" href="https://www.youtube.com/watch?v=EKLHCKwgs-4&list=PLCseOl6jsv2oRbhZzk3ZvgrnswPK12wim">
        <a class="icon">
          <img src="../../assets/media icons/youtube.svg" class="logo">
        </a>
        <p class="has-text-weight-bold" style="margin-left: 10px;">Watch the Process!</p>
      </a>
    </div>
    <div class="container has-text-centered">
      <p class="section-title-primary">Challenges</p>
      <br>
      <p>When creating this project I was challenged in a variety of ways. Primarily I had to learn Unity, Blender, and C#, which were all items I had not had prior exposure to. This meant that I spent the majority of my time learning the softwares rather than creating the product. Having a limited amount of time also made it difficult to complete the project, as it meant working long days on a limited schedule. However, this did help me to improve both my time and project management, so the challenge was worth it. Small issues also popped up, forcing me to spend days fixing issues and creating features that only should has taken hours. Yet, this showed me how to push through in a project and why perseverance is so important.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'sentiment'
}
</script>

<style scoped>
@import '../../assets/css/projects.css';

#welcomeMessage {
  font-weight: 900;
  font-size: 5.5em;

  /* Need a better way to manage the text spacing */
  margin-bottom: 50px;
}

.button {
  padding: 30px 35px 30px 35px;
  margin-right: 36px;
  margin-bottom: 35px;
  border-radius: 10px;
  box-shadow: 0 6px 6px rgba(10, 10, 10, 0.15);
}

.container {
  margin-bottom: 128px;
}

.is-centered {
  display: flex !important;
  margin-left: auto;
  margin-right: auto;
  /* width: 40%; */
}


p {
    font-size: 18px;
    line-height: 45px;
}

@media only screen and (min-width: 768px) {

  .pull-right {
    float: right;
  }

  .container {
    margin-bottom: 128px;
  }

  .work-header {
    padding-top: 50px;
    min-height: calc(100vh - 100px);
  }

}

@media only screen and (max-width: 768px) {
  #main {
    text-align: center;
  }
  
  .button {
    margin: 35px 18px 35px 18px;
  }

  .work-header {
    padding: 15px;
  }
}

</style>