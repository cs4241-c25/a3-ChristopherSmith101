## Mobile Legends Database App

your glitch (or alternative server) link e.g. https://a3-mlbb-database.glitch.me/

This application serves as a place for users to store heroes that they play in Mobile Legends. Some issues that
I ran into while developing this website was the user login feature of the app. I chose local storage as my
authentication strategy because it was easier to understand and implement compared to Local Strategy. I used
bootstrap in combination with my original grid styling for assignment A2. I did this because I was already
satisfied with my layout, but I did want my font and color styling to be made better, which bootstrap helped
with.

In order to test things, I have two users you can log in with. "fluffy" with password "1", and "togekip" with
password "2".

## Technical Achievements
- **Lighthouse (1 point)**: I got 100 for performance, accessibility, and best practices. I got 91 for SEO, and the ONLY
                            thing I didn't have was a robot.txt file. I do not think this is something that was wrong
                            on my end, since robot.txt is not something we talked about in class.
- **Implemented a "Delete All" feature (5 pts)**: I created another feature that accesses and deletes all heroes from
                                                  a logged-in user's database.
## Design/Evaluation Achievements
- **CRAP Principles** (10 points):
  Which element received the most emphasis (contrast) on each page?
    The elements that received the most contrast on each page were the form input areas. Since the background is
  a light blue color, the white background and gray text in the form is easy to read for the user. As for the
  headers, they are underlined and bolded to make it clearer.

  How did you use proximity to organize the visual information on your page?
    I used grid styling for my main.css style sheet, which makes it easy to place components at certain fraction
  points that I specify. Using this method, I placed headers on a row followed by a row containing forms. Each
  header that is associated with a form is in the same section of the grid, making it easy to understand. I used
  proximity with buttons and forms so that the submit button is close to the actual form input boxes. Any other
  buttons that are not associated with a form are named after what they do. For example, the "logout" button will
  log a user out of the website, redirecting to the login page, and the "Remove All" button will delete all the
  heroes in the user's database.

  What design elements (colors, fonts, layouts, etc.) did you use repeatedly throughout your site?
    The color scheme that I went for is a light blue background with black lettering and white text boxes and such.
  The font is Sans Serif. I always included a header above where the information is kept so as not to confuse
  users.

  How did you use alignment to organize information and/or increase contrast for particular elements.
    I used alignment to put information in the proper section. Headers belong with their prospective forms and
  the header "Results" should be directly above the table that is created with the hero data. Space was created
  between rows in order to create separation and therefore contrast between the header and information.
