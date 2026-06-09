# Sustainability Cell - Hero Page Redesign

Seeing the original hero page of the website, I realized that it was already very well designed. It presented its design and color theme in a very good and minimalistic manner. Changing anything too much might have ruined its minimalistic design. Hence I added only some subtle changes with some interactive elements which will make it more engaging.

## Changes I did:
* Moved the navigation bar on the left, just next to the logo. On the original website it s aligned to the right side, which covers the globe and reduces its focus.
* Exchanged the color of Sustainibility Cell and IIT Bombay making the sus cell text green for better look. Also made the sus cell text slightly bigger. 
* Added rotating quote-like text/fun-facts just below the “empowering sustainable…” text and the learn more button. For this, moved the heading and text slightly above to make space in between.As of now its just some random texts changing every 12 seconds which can later be changed accordingly.
* Also added a faint glow to it for more quote-like feel.
* Enhanced the learn more button. This is where I added most changes. First changed the "Learn More" to "Explore our Work" for better feel. Hovering over the button, first makes it change its color to forest green and text turns black. It also trigger a glow on some elements on the page like the logo, Sustainability Cell text in heading and the globe on the right. Along with this, added animation of some tree vines growing on the leftmost and rightmost side of the page when hovered on the button, conveying a feeling of growth when the user is willing to learn more.
* Added subtle cloud like effect at the bottom of hero page, which open up when scrolled down. The clouds are made thin and subtle so that they don’t interfere with the focus of the main page. When you scroll down, they perform a curtain opening effect combined with fading effect, opening way to the content below.
* While the original page is very good in itself, I noticed when you click on any of the navigation button, it directly takes you to that section of the page. While this works, this feels rather bland and straightforward. So, I added the missing scroll effect. Initially I used CSS to add a smooth scroll effect but it did not pair well with the cloud effect mentioned above. Hence I changed that with a custom slow to fast scroll effect made using JavaScript.
* Did not change much in the globe, as it was already very good looking. But added a subtle glow when hovered on learn more button. Because the globe was part of background image, making changes to it was tough. So I made an invisible circle element and placed in on the globe by fine tuning to achieve this. Also now, clicking the globe takes you to greenscore calculator.

I have ultimately did only a few and subtle changes to the hero page, but its also because the great work by the previous convenors in designing it in such a good way. The changes I made preserve the look it was given while also enhancing it with interactive elements.

All the changes I did majorly used HTML and CSS with some JavaScript for certain tasks. While I can do HTML and CSS well, I currently lack enough knowledge on JavaScript, but will soon catch up with it under a project I have taken up in “Seasons of Code” event by WnCC.

## Structure of files:
* This question 1 folder consists of the `index.html` file as well as the `style.css` file.
* It also has image folder containing the logo used in the website.
* To view, save all these files in one folder, and then open the `index.html` file on any web browser and that should work.

## AI Use:
For this, I have used AI in doing certain things. Ideating and deciding all the changes was done solely by  myself . No AI  was used in making ideas for changes. Coding part Is where I used AI.
* While I could have coded all the html page myself, I handed that work to gemini because it is a mundane task and using AI to do it won’t change much, instead save lots of time which is important.
* Also, after it provided the base HTML structure, I made changes to it accordingly, assigning proper classes and ids to different elements.
* Then I again used AI for making a base CSS structure file on top of this HTML file, and then myself made changes to it accordingly. Majority of this was to save as much time as possible and invest more time in actual thinking process.
* One thing I heavily used AI for was to add Javascript to it, because I lack the ample knowledge for it as of now. But also due to other project I have to work on, and this, I am gaining knowledge of it.
