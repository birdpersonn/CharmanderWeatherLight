<div id="header" align="right">
  <img src="https://media.giphy.com/media/eKiI67RMFbnxa7WuKC/giphy.gif" width="155"/>
  <div id="badges" align="right">
    <a href = "https://www.instagram.com/birdpersonn/">
      <img src="https://img.shields.io/badge/LinkedIn-74a2ed?logo=linkedin&logoColor=white?style=plastic" alt="LinkedIn Badge"/>
    </a>
    <a href = "https://www.linkedin.com/in/chanel-carpenter-594a6b71/">
      <img src="https://img.shields.io/badge/Instagram-bc9eeb?logo=linkedin&logoColor=white?style=plastic" alt="LinkedIn Badge"/>
    </a>
  </div>
</div>

<h1>
  charmander weather light
  <img src="https://media.giphy.com/media/pbviPVVW08jD2/giphy.gif" width="120"/>
</h1>

## 🌙 project overview:
modify a charmander plushie to tell the temperature outside. the flame on his tail should light up on a color scale from yellow to red depending on the temperate outside. 

## 🌙 ingredients: 
- charmander plushie (bought a build-a-bear charmander off ebay)
- raspberry pi (using a pi zero w)
- candelabra/flame lightbulb (must be incandescent bulb, not led)
- power supply for pi (i used a $10 portable charger)
- zipper
- needle and thread
- scissors
- soldering iron
- gorilla glue (or similar strength)
- rgb led diode (diffused option looks better)
- various jumper wires

## 🌙 recipe: 

#### get the plushie ready
1. sew in zipper—this allows for easier access to get components in and out of the plushie
   * find best spot for zipper and make sure it is big enough for your larger components (pi and power supply) to fit through 
   * cut into plushie and pin zipper into place
   * use any tutorials necessary to sew zipper into place
   * test to make sure you can use the zipper without it coming undone and that the opening is big enough
2. replace flame with hollowed out lightbulb—be careful!
   * lightbulb cannot be led (not able to hollow out; i've tried 😤 ). also i've learned it's better to have a diffused or frosted light bulb. if you can't find one, you can spray the bulb with a frosted glass spray (i got one from JoAnne's)
   * hollow out the bulb so that it is empty and you are able to fit the rgb diode through the bottom. i don't really have any ways of doing this that i feel comfortable sharing or condoning. do so at your own risk and be careful, i've definitely broken a few bulbs before trying to do this.
   * cut off flame of plushie and use extra strength glue to attach bulb to end of tail

#### get the pi ready
1. set up your pi
   * there are many ways to get started, i chose to run headless on my macbook. if you have no idea what that means, don't worry, neither did i, just look up how to get a pi running and go through whichever method seems easiest. 
2. get your pi connected to wifi
   * some pi models do not come with a built-in wifi option, so you might need a dongle or attachment for this. 
   * my pi zero w was very easy to set up (following a tutorial of course) with nothing extra needed!
3. attach rgb light to pi
   * there are many <a href="https://cdn.sparkfun.com/assets/learn_tutorials/1/5/9/5/GPIO.png" target="_blank" rel="noopener noreferrer">diagrams</a> and tutorials online explaining how to properly attach diodes
   * use jumper wires to make sure the length from the pi to the light is long enough to be thred through the tail. test it out before attaching anything. 
   * i used blue putty to hold all the connections in place until the very end of the project!
