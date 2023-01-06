Challenges in this project and the ways to resolve them:

1. Used several background images and define their locations using background-position property:

   background-image: url(logo-light.svg), url(icon-facebook.svg), url(icon-instagram.svg), url(icon-twitter.svg);
                background-color: black;
                background-position: 32px 48px, 32px 268px, 72px 268px, 112px 268px;
                
2. Changed the color only of a small part of a letter:

   .half-color {
                    background: linear-gradient(to right, white 70%, black 30%);
                    background-clip: text;
                    -webkit-background-clip: text;
                    -webkit-text-fill-color: transparent;
                }
                
3. Affected the same and another div located in descendant div simultaneously upon hovering:
    
    .ourlocButton:hover .ourloc {
                    background-color: #D5966C;
                }
    .ourlocButton:hover .rightarrow {
                    background-color: black;
                }
                
4. Changed the color of the white svg logos to black with:

                  filter: brightness(0.1);
