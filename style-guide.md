# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Soft orange: hsl(35, 77%, 62%)
- Soft red: hsl(5, 85%, 63%)

### Neutral

Off-white: hsl(36, 100%, 99%)
Grayish blue: hsl(233, 8%, 79%)
Dark grayish blue: hsl(236, 13%, 42%)
Very dark blue: hsl(240, 100%, 5%)

## Typography

### Body Copy

- Font size (paragraph): 15px

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700, 800


.main_container{
    display: grid; 
    grid-template-columns: 1fr 1.3fr 0.7fr; 
    gap: 15px 15px; 
    grid-template-areas: 
        "img img aside"
        ". . ."
        ". . ."; 
    padding: 10px;
    
    .coverImg{
        display: grid; 
        grid-template-columns: 1fr 1fr ; 
        gap: 0px 0px; 
        grid-template-areas: 
          ". . ."
          ". . ."
          ". . ."; 
        grid-area: img; 
      img{
            
           aspect-ratio: 2/1;
  object-fit: cover;
  height: 100%;
  max-width: 100%;
        }  
        
    }