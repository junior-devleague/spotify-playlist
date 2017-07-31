#Welcome To Spotify!
You will be recreating your own Spotify playlist that includes all your favorite songs!

**Here's an example:**
<p align="center">
<img src="https://github.com/junior-devleague/spotify-playlist/blob/master/images/regular.png"></img>
</p>

##Before you begin
- Pick five or more songs to include in your playlist
- Find **online** album cover art for the songs you picked
- Please create a mockup of your playlist for an instructor to approve :)

##Set-up your files
Please create the following files:
- index.html
- styles.css
- README.md

Create a link tag for your CSS stylesheet in your HTML document.

##HTML
1. Create a header containing the name of your playlist using a **header** tag, adding an id attribute with the value of `playlist-name`.

2. Create a playlist container for all of your songs using a **div** tag while adding an id attribute with the value of `playlist-songs`.

3. Create at least 5 different songs using a **div** tag and for each song, create a class attribute with the value of `my-songs`.

4. For each song:
  - Create a header containing the song's name using a **header** tag smaller than **h1**.
  - Create an **image** tag and set the source attribute to the song's album cover picture, creating a class attribute with the value of `album-cover`.
  - Using a **paragraph** tag, create a short description for each song that includes the artist and album name.

*BONUS* Wouldn't it be cool if each song played the actual music? Add an audio tag to each playlist song.

##CSS
1. Set the background image of the body to the Spotify logo using the `element` selector.
  
  For the Spotify Logo:
  - Make sure the image **does not** repeat (hint: background-repeat)
  - Set the size of the image big enough so it fits the screen
  - Center the background image

2. Align the header (name of your playlist) to the center with `id` selector.

3. With the `id` selector, style the container div accordingly:
  - Set a **transparent** background color (hint: use the *rgba* property)
  - Set the width to 50% of the page
  - Align the container to the center of the page

4. Change the styles of the individual songs using the `class` selector.
  - Align all songs and their content to the center of their container element.
  - Set all album covers to the same size.

5. Modify your individual songs further with these style attributes:
  - `background-color`
  - `color`
  - `font-size`
  - `font-family`
  - `height`
  - `text-align`
  - `width`

*Stretch Goals:*
  - Add the green "SHUFFLE PLAY" button at the top
  - Add a cover picture for your playlist
  - Play music when clicking on that song
  - **Attempt to format your playlist like the picture below**
  
<p align="center">
<img src="https://github.com/junior-devleague/spotify-playlist/blob/master/images/stretch-goals.png"></img>
</p>
