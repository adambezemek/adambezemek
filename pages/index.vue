<template>
  <section class="container mx-auto text-center">
    <h1 class="lowercase">I Strive to Make the Web Better.</h1>
    <Profile />
    <div class="flex">
      <div class="w-full flex flex-col justify-center">
        <div id="main">
          <h2 class="lowercase">I am Adam Bezemek.</h2>
          <p class="text-justify max-w-md mx-auto mb-32">
            Adam Bezemek is an accomplished Director of Technology that
            specializes in empowering his teams to create better quality, easily
            maintained, and scalable user interface applications. He has a
            passion for working with a plethora of new technologies and
            advocating the importance of Design Systems. For over ten years he
            has been crafting creative solutions to unique business problems
            across the entire technology stack and leading teams into more
            sustainable futures.
          </p>
        </div>
        <div id="life">
          <h2 class="lowercase">I Love my Life.</h2>
          <p class="text-justify max-w-md mx-auto mb-32">
            Adam is a loving father, supportive life partner, traveler,
            risk-taker, sports enthusiast and coffee addict. He is currently
            operating life somewhere near the sweet spot between order and
            chaos, while taking breaks to explore the beautiful bluffs of La
            Crosse, WI. He sometimes takes trips with friends and enjoys a good
            discussion about entrepreneurship.
          </p>
        </div>
        <div id="career">
          <h2 class="lowercase">I Enjoy my Career.</h2>
          <p class="text-justify max-w-md mx-auto mb-32">
            From Harley's (motorcycles) to Healthcare, Adam has experience
            across a vast spectrum of verticals, working with technology. He
            uses that experience to empathize with users and gain perspective
            for every new digital solution. He is skilled in user experience
            research, user interface design, and modern front end
            development.<br /><br />
            That said, when people ask him what he does, he usually says:<br />
            <em>“I make the web look pretty.”</em>
          </p>
        </div>
        <div id="speaker">
          <h2 class="lowercase">I Like Talking.</h2>
          <p class="text-justify max-w-md mx-auto mb-5">
            Sometimes you can find Adam speaking at events about the importance
            of Design Systems.
          </p>
          <h3 class="text-left font-sans max-w-md mx-auto pl-2 mb-2">
            Past Events:
          </h3>
          <ul class="text-left font-sans max-w-md mx-auto leading-normal">
            <li>Chippewa Valley Developers Group</li>
            <li>Open Source North</li>
            <li>JavaScript MN Meetup</li>
            <li>Minnebar Minneapolis</li>
            <li>AngularMN Meetup</li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Profile from '~/components/Profile.vue'

export default {
  head: function() {
    return {
      title: 'adam bezemek'
    }
  },
  components: {
    Profile
  }
}
</script>

<style lang="scss"></style>
