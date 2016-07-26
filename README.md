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
  links:               #list of strings
  contact:
    phone: 
    email: 
~~~~

### How to Add a Paper
1. Put pdf of paper in 'assets/papers'
2. In _data/papers.yaml, add array entry with following information
~~~~
- year: 2015
  title: What is the letter g?
  authors: Jane Dee, John Doe
  publication: ArviX
  description: Lorem Ipsum ...
  pdf: ''   #file name of paper w/in assets/papers
~~~~