# Mondrian-style composition
## Objective
Recreate a composition inspired by the style of ***[Piet Mondrian](https://es.wikipedia.org/wiki/Piet_Mondrian)***, using HTML + CSS3, applying techniques such as:

- position (relative / absolute)
- flexbox
- size control (width, height)
- thick borders (border)
- block layout / distribution`

It must look like this:

<img width="569" height="663" alt="Screenshot 2026-04-10 120337" src="https://github.com/user-attachments/assets/f5b8d692-7ee1-4ecc-a592-dfa299fe31df" />


## Statement
You must build a web page that represents a geometric composition with colored blocks, following these rules:

### General structure
Create a main container .canvas:
- Fixed size (e.g., 500px × 500px)
- White background
- Thick black border (simulating the painting’s lines)
-  Block distribution

You must divide the container into several 

rectangular sections:

🔴 Upper left area
One large red rectangle
Occupies approximately 60% of the width and 60% of the height

🟡 Upper right area
One yellow rectangle
Occupies the upper right section

⚪ Middle right columns
Two vertical white rectangles
Separated by a thick black line

⚫ Lower left area
One large black block

⚪ Lower center area
Two small horizontal white blocks

🔵 Lower right area
One blue rectangle



## Important rules
All divisions must have:

- border: 8px solid black; (to simulate the black lines)

- You are not allowed to use images → only HTML + CSS

- You must use at least one of these techniques:

 -- position: absolute

 -- flexbox


## Technical requirements
HTML
One main container
divs for each color block
CSS

You must use:

- position
- z-index (if necessary)
- box-sizing: border-box
- Colors:
```
red → #E63946
yellow → #F1C40F
blue → #1D4ED8
black → #000
white → #F8F9FA
```

How it look:


<img width="584" height="602" alt="Screenshot 2026-04-10 115621" src="https://github.com/user-attachments/assets/7fe26fe9-9c9a-4148-9ab9-eaf9d4cce96c" />




Added hover also, then user puts cursor on each boxes, cursor turns pointer and box turns 1.2 bigger and has 8px border:


<img width="556" height="578" alt="Screenshot 2026-04-10 115654" src="https://github.com/user-attachments/assets/0406b623-786d-41c9-a7cb-b60975af74e0" />
<img width="569" height="589" alt="Screenshot 2026-04-10 115709" src="https://github.com/user-attachments/assets/89b66d5c-cc6f-4aa9-9ffb-a06e488aad71" />

