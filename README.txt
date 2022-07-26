

About

I started this project to learn web development. I have been following along with the tutorial by
Kevin Powell at https://www.youtube.com/watch?v=zPHMqqyD2kY&list=PL4-IK0AVhVjNDRHoXGort7sDWcna8cGPA&index=4

I have worked through the first three videos posted. All errors are my own. 

As this is my first project, I have also included my steps in setting up software to begin. 

Notes


1) Install VM using VirtualBox or VMware to Linux Ubuntu

2) install VScode editor & Chrome onto VM
- also add npm

3) install Node.js

Node is a runtime environment that allows execution of javascript code outside the 
browser, on a server/desktop

>sudo apt install curl
>curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
>sudo apt-get install -y nodejs

DAY 1

4) Follow along with Kevin Fowler Part 1

- install npm
>npm create vite@latest
name practice-powell-youtube
framework: vanilla
variant: vanilla

>cd practive-powell-youtube
>npm install
npm notice created a lockfile as package-lock.json. You should commit this file.
4 packages looking for funding, run 'npm fund' for details

>npm run dev
will output http://localhost:xxxx/
use Ctrl+select to open in a browser


5) Download relevant files from FrontEnd Mentor
https://www.frontendmentor.io/challenges/manage-landing-page-SLXqC6P5

- download starter files
- andy bell css reset file - paste into style.css
- add style guide colors/fonts to the style.css
- paste font google links into index.html 
- paste font google "css rules to specify family" in style.css
- set font variables

part 1 video pause 36:13min

DAY 2

- open VS code editor
- verify colors/accent colors added to style.css
- verify font and font sizes added
- review terms

Notes
Font size is converted to REM units in the style doc
16px font = 1rem
everything else is a proportion of 16
10px = .625rem
20px = 1.25rem

- Rem stands for "root em" meaning root element
- Each browser determines the px value of it's HTML elements
- Most browsers default to 16px equal to 1 rem
- EM units are different than REM units
- EM units are proportions of their own element, REM units are proportions
of the HTML element

Lists are created using objects "ul" and "ol"
UL means unordered lists (example, bullet points)
OL means ordered lists (sequential as in numbers or letters)
in a UL or OL object you define portions of the list, including:
 list-style-type (shape)
 list-style-image (bubble heads)
 list-style-position (outside/inside)
etc.


6) Continue rough out the Colors/Fonts/Containers as Utility Classes

-finished first video

7) Work on index.html

- comments in html use format: <!-- comment here -->

part2 video pause at 24min

Also: learned how to pull text from the jpg mockup by inserting
picture to Onenote and then r-click, copy text from image.

DAY 3

8) Work on index.html > finish w/ video 2 Kevin Powellt

finish index.html rough draft
review order of
main
head
body
header

pause @ start of 3rd video

DAY 4

3rd video

-general styling in style.css
- error with font family

-create Figma account
Kevin Powell uses Figma to pull container sizes, font sizes, etc. 

- to view in browser as mobile > Dev Tools is F12
- if in VM, go to Settings > more tools > dev tools
- at the top is a blue icon "device toggle"
- under "dimensions" select by device

- in style.css
add buttons
add padding
add to utility classes




