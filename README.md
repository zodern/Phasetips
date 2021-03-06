# PhaseTips
A tooltips UI component for Phaser.io Javascript library

<h3>Initialize the tooltip anywhere in your game</h3>
```
var myTooltip = new Phasetips(gameInstance, options);
```
pass necesery options like: context (the object that launches the tooltip)

```
new Phasetips(gameInstance, {
    targetObject: myObj,
    context: "Hello tooltip",
    strokeColor: 0xff0000
  });
```

<hr>

<img src="http://i221.photobucket.com/albums/dd22/djmid71/phasetips_zpsjtzerwxx.gif"/>

<strong>View example: <a href="http://www.netgfx.com/trunk/games/tools/phasetips">Complete example</a></strong>

  <hr>

<strong>Game Instance</strong>
The game instance that we want the tooltips to appear to, such as "game"

<strong>General Options:</strong>

<ul>
	<li><strong>context:</strong> The information inside the tooltip, can be String, Number, Sprite, Phaser.Text, Phaser.BitmapText, Phaser.Group, Phaser.Image</li>
	<li><strong>width:</strong> The width of the tooltip (default: auto)</li>
  <li><strong>height:</strong> The height of the tooltip (default: auto)</li>
  <li><strong>x</strong> The x position of the tooltip (default: auto based on position)</li>
	<li><strong>y</strong> The y position of the tooltip (default: auto based on position)</li>
	<li><strong>targetObject</strong> The actual object in which the tooltip will appear on hover (default: Game)</li>
	<li><strong>animation: </strong> The animation effect (default: fade, options:fade, grow, none)</li>
  <li><strong>animationSpeedShow: </strong> The duration of the animation effect showing the tooltip (default: 300)</li>
  <li><strong>animationSpeedHide: </strong> The duration of the animation effect hiding the tooltip (default: 200)</li>
  <li><strong>animationDelay: </strong> The animation delay before showing the tooltip (default: 0)</li>
	<li><strong>padding: </strong> The padding that the context keeps from the tooltip bounds (default: 20)</li>
    <li><strong>positionOffset: </strong> The position offset that the tooltip keeps from the targetObject (default: 20)</li>
    <li><strong>strokeColor: </strong> The color of tooltip stroke (default: 0xffffff)</li>
    <li><strong>strokeWeight: </strong> The line weight of the tooltip stroke (default: 2)</li>
    <li><strong>customBackground: </strong> If the tooltip will use a custom background (default: false)</li>
    <li><strong>position: </strong> The position of the tooltip based on the targetObject (default: top, options: top, bottom, left, right)</li>
    <li><strong>enableCursor: </strong> Enables the hand-cursor over the target object when hovered (default: false)</li>
    <li><strong>textStyle: </strong> Declares styles for the simple text element (default: {
            fontSize: 12,
            fill: "#ffffff",
            stroke: "#1e1e1e",
            strokeThickness: 1,
            wordWrap: true,
            wordWrapWidth: 200
        }</li>
    <li><strong>onHoverCallback: </strong> Calls a function when hover occurs (default: fn)</li>
    <li><strong>onOutCallback: </strong> Calls a function when hover ends (default: fn)</li>

</ul>

<strong>API Functions</strong>

<ul>
    <li><strong>printOptions: </strong> Prints the options specified in the constructor on the console</li>
    <li><strong>updatePosition: </strong> Change the x, y of the tooltip</li>
    <li><strong>destroy: </strong> Destroys the tooltip and all its children</li>
    <li><strong>hideTooltip: </strong> Hide the tooltip</li>
    <li><strong>showTooltip: </strong> Show the tooltip</li>
</ul>

<i>
</i>

<hr>

<strong>Buy me a coffee or tea!</strong> <br>
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=JCFPKZJ7Y23JJ&lc=GR&item_name=NetGfx%2ecom&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted"><img src="https://www.paypalobjects.com/webstatic/en_US/btn/btn_donate_92x26.png"/></a>


<hr>

>The TODO list is diminising!

>Please let me know if you come across some bug or have something to contribute





