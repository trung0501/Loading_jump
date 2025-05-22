🏷️ Program Name: Loading Screen Animation

🎯 Program Purpose: Create an animation effect for the text “Loading” on the loading screen to enhance the user experience while waiting for the content of the application or website to load. The program shows liveliness and sophistication during the waiting process without boring the user.

🧩 The main component of the program:

    . HTML: Create content structure with a <div> tag contains the word "Loading", divided into each child character.

    . CSS: Definition of style, layout, color and animations (@Keyframes) to create motion effects for elements.

    . Google Fonts: Use modern and easy-to-read fonts to display text clearly and aesthetically.
    
⚙️ Principle of operation:

    1. HTML divides the word "loading" into <span class = "letter"> to easily control each individual character effect.

    2. CSS creates animations using @keyframes like:

      . dotMove: Moves the small dot below the letter.
      
      . letterStretch: Stretches the letter "i" like it's jumping up and then shrinking.

      . lineStretch: Creates a vertical stretch effect for the letter "L".

     3. The effects work together to create a smooth, rhythmic feel when the word “Loading” appears.

     4. The effects are split by character position via nth-child(), giving each letter its own separate animation.

     5. The whole thing is centered on the screen, adapting well to screen sizes thanks to media queries.
