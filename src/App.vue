<script>
  export default {
    data() { return {
      headerIsOn: true
    }}, methods: {
      switchHeader() {
        console.log("switched Header!")
        this.headerIsOn = false;
      }
    }
  }
</script>

<template>
  <header v-show="headerIsOn" id="warning">CODINGNEWS.BENRAZ.DEV IS IN BETA<i class="x-button" @click="switchHeader()">X</i></header>
  <header>
    <div id="title">
      <h1>Microsoft Anounces 365 Copilot</h1>
      <h3>Ben Raz • 3/19/2023</h3>
    </div>
    <img src="https://play-lh.googleusercontent.com/94uR6O49JmqiMMMsrfoDlWvWkqLf6rfE25zOH2BWnuzozzlfY1qnKaNzuQbUcupcpX9L=w240-h480-rw" />
  </header>
  <article>
    <p>
      On March 6th 2023, Microsoft officially announced at their 365 AI event
      that Microsoft 365 (formerly Office 365), will be enhanced with a new AI
      assistant, dubbed 365 Copilot.
    </p>
    <p>
      This assistant will resemble a more intelligent form of clippy that helps
      automate meaningless tasks like creating meeting summaries and generating
      copy.
    </p>
    <p>
      It will also help you use Office better. According to Microsoft’s press
      release “Now, you can be more creative in Word, more analytical in Excel,
      more expressive in PowerPoint, more productive in Outlook, and more
      collaborative in Teams.” This system can also analyze meetings, summarize
      spreadsheets, and create marketing writeups.
    </p>
    <p>
      One of the big questions is whether this is bad news and how bad it is. I
      personally don’t foresee massive job loss, but many people who do
      repetitive office work will probably be replaced if they cant adapt.
    </p>

    <p>
      Another important fact is that Microsoft has so far been the first major
      company to implement these AI innovations. Microsoft, unlike companies
      like Google, can experiment more freely with AI because Office and Bing
      are not as popular as Workspace or Google Search. Google is not in such a
      position to experiment freely and has now had to play an embarrassing game
      of catch-up if it wants to remain relevant.
    </p>

    <p>
      An example of Google’s response to this has been seemingly rushed
      announcements of BARD and AI integrations in Google Workspace. While
      Google is definitely in a difficult spot right now, I don't think they
      will let this innovation make them obsolete. They will fiercely compete
      with Microsoft, and it’s about time for more innovation in the neglected
      areas of Search and collaboration software.
    </p>
  </article>
</template>
