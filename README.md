

# Planning the application 

  1. Answer Questions
    - What am I building?
    -Who am I building this for?(my target audience)
    -What features do we need to have?

  2. User Stories
  3. Model my Data
  4. Think through the pages we need in our app.

  ### Answer to the questions above
  1. What am I building? I am building a personal site to attract potential employers, a place where I can blog and show examples of my work, and have people contact me.

  2. Who am I building this for (my target audience)? I am building it for myself, but also the community. Learning by blogging is an awesome way to document my journey and show/share with others my process. Also a great way to show employers what I am doing.

  3. What features do I need to have? 
      - Posts 
          - Create / Edit / Destroy
          - Markdown
          - Syntax highlighting
          - Comments (Disqus)

      - Projects
        - Create / Edit / Destroy

      - Contact
          - Contact form
          - Sengrid

      - User (Devise)


## User Stories
  # As a I want tp be able to blank, so that blank
    - As a user, I want to be able to create posts so that I can share what i am learnig and building on my portfolio.
    - As a user, I want to be able to edit and destroy my post so that I can manage my portfolio.
    - As a user, I want to be able to I want to be able to make post in markdown format so that its easy for me to write post
    - As a user, I want to be able to highlight that various Syntax of code blocks that I share on my site.
    - As a user, I want to be able to show my potential employers examples of my work, or the things I built.
    - As a user, I want to be able to have vistors and potential employers be able to contact me through a form on my site. 
    - As a user, I want visitors to be able to leave comments on my post.

    ## Modeling my Data

      ##Post##
        title:string
        content:string

      ##Project##
        title:string
        description:text
        link:string

      ##User##


## Think through the pages we need in our app.

  - Home page
  - Posts#index
  - Posts#show
  - Projects#index
  - Projects#show
  - contact

## Wireframe

 ![](%20![](/Users/erictso/Desktop/myPortfolio/tsoisthewaytogo/Screen%20Shot%202019-02-09%20at%2010.58.40%20AM.png).png)