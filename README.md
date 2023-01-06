Challenges in this project and the ways to resolve them:

1. Use several background images and define their locations using background-position property:

   background-image: url(logo-light.svg), url(icon-facebook.svg), url(icon-instagram.svg), url(icon-twitter.svg);
                background-color: black;
                background-position: 32px 48px, 32px 268px, 72px 268px, 112px 268px;
                
2. Change the color only of a small part of a letter:

   .half-color {
                    background: linear-gradient(to right, white 70%, black 30%);
                    background-clip: text;
                    -webkit-background-clip: text;
                    -webkit-text-fill-color: transparent;
                }
                
3. Affect the same and another div located in descendant div simultaneously upon hovering:
    
    .ourlocButton:hover .ourloc {
                    background-color: #D5966C;
                }
    .ourlocButton:hover .rightarrow {
                    background-color: black;
                }
                
4. Change the color of whote svg images to black with:

                  filter: brightness(0.1);
