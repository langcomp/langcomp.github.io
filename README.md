# langcomp.github.io
language and computation lab website


### How to Add a Lab Member
1. Put a picture of yourself in 'assets/img'
2. Put your CV in 'assets/pdfs' 
3. Locate the file within _data/people for your level of education/role in the lab
4. Add an array entry filled with the following information
~~~~
- name: 
  position:
  picture: ''          #include the file name of your image in assets/img 
  background: >
    # A description of where you're coming from, your education, etc
  projects:  >
    #Name or description of current project (a sentence or 2)
  cv: ""               #string of file name in assets/pdfs
  link:               #string
  contact:
    email: 
~~~~

### How to Add a Paper
1. Put pdf of paper in '/assets/papers/'
2. In _data/papers.yaml, add array entry with following information
~~~~
- year: 2015
  title: What is the letter g?
  authors: Jane Dee, John Doe
  publication: ArviX
  description: Lorem Ipsum ...
  pdf: ''   #file name of paper within assets/papers
~~~~

### How to Add a Project
1. Put a markdown/html file into '/projectpages/'
2. Put an image that encapsulates your project into '/assets/img/'
    - this image will grab the middle "square" of the image, so you're better off including a square image to start with
3. In _data/projects.yaml, add an array entry with the following information
~~~~
- name: # Name of Project
  picture: # name of image file you put in '/assets/img/'
  researchers: # you can add as many people as you'd like to this field
    - name: Fake Person
      email: dummy@gmail.com
  description: >
    #long-ish description of your project (maybe a paragraph)
  project_link: #name of the markdown/html file you put in '/projectpages/'
  git_link: #full link to the repo associated with this project
