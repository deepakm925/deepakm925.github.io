---
layout: home
header:
  title: DEEPAK MAHTANI
  text: >
    DEVELOPMENT |

    DATA ANALYSIS & SCIENCES    |
    
               MACHINE-LEARNING |

               POWER BI ANALYSIS
    
  action: # action button is optional
    label: GO TO SITE MENU OPTIONS
    url: '#about'


sections:
    
  - type: call-to-action.html
    section_id: about
    background_style: bg-dark
    title: MENU OPTIONS 
    text: ""
    actions:
      - title: ABOUT DEEPAK!
        url: '#members'
        class: btn-light
      - title: Software and Skills
        url: '#services'
        class: btn-light
      - title: Project Portfolio
        url: '#portfolio'
        class: btn-light
  
  - type: members.html
    section_id: members
    title: ABOUT DEEPAK
    background_style: bg-info text-white
    members:
      - title: Deepak MAHTANI 
        image: assets/img/my-images/deepak.jpg
        text: HI my name is Deepak I am a coder! 
        url: '#' 

  - type: members.html
    section_id: services
    title: SOFTWARE AND SKILLS
    background_style: bg-big-info text-black
    members:
      - title: PYTHON
        image: assets/img/my-images/python-logo.png
        url: '#'
      - title: SQL
        image: assets/img/my-images/sql-logo.png
        url: '#'
      - title: DAX
        image: assets/img/my-images/dax-logo.png
        url: '#'
      - title: ANACONDA-NAVIGATOR
        image: assets/img/my-images/anaconda-navigator-logo.webp
        url: '#'
      - title: SPYDER-IDE
        image: assets/img/my-images/spyder-logo.png
        url: '#'
      - title: JUPYTER NOTEBOOK
        image: assets/img/my-images/jupyter-logo.png
        url: '#'
      - title: MICROSOFT POWER-BI
        image: assets/img/my-images/powerbi-logo.png
        url: '#'
      - title: MICRSOFT VISUAL-STUDIO
        image: assets/img/my-images/visual-studio.png
        url: '#'

  - type: portfolio.html
    # this section has always ID 'portfolio'
    section_id: portfolio
    title: PORTFOLIO text-black
    background_style: bg-dark
    projects:
      - title: Project 1
        text: This is a very short project description.
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: 1.jpg
        url: '#'
      - title: Project 2
        text: This is a very short project description.
        icon: 2.jpg
        url: '#'
      - title: Project 3
        text: This is a very short project description.
        icon: 3.jpg
        url: '#'
      - title: Project 4
        text: This is a very short project description.
        icon: 4.jpg
        url: '#'
      - title: Project 5
        text: This is a very short project description.
        icon: 5.jpg
        url: '#'
      - title: Project 6
        text: This is a very short project description.
        icon: 6.jpg
        url: '#'


---