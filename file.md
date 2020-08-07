    1. What is Semantic HTML? 
      - Meaningful HTML markup tags
      
    2. What is HTML used for? 
      - Display data in a graphical form 
      
    3. What is an attribute and where do we put it? 
      - Modifiers of an HTML element type
      - They go inside the opening front tag
      
    4. What is the h1 tag used for? How many times should I use it on a page?
      - The largest/most important header
      - Once per page 
      
    5. Name two tags that have required attributes
      - img 
      - a (anchor)
    
    6. What do we put in the head of our HTML document? 
      - Meta data 
      - Importing fonts 
    
    7. What is an id? 
      - A selector that can only be used once 
      - Used with # 
    
    8. What elements can I add an id to? 
      - Any element 
    
    9. How many times can I use the same id on a page? 
      - Once 
    
    10. What is a class? 
      - A selector that can be used on multiple elements
    
    11. What elements can I add a class to? 
      - Any element
    
    12. How many times can I use the same class on a page? 
      - As many times as you want
    
    13. How do I get my link to open in a new tab?
      - <a href="#" target="blank"></a>
    
    14. What is the alt attribute in the image tag used for? 
      - Describing the image 
    
    15. How do I reference an id?
        - # 
    
    16. What is the difference between a section and a div?
      - Section is semantic HTML which separates sections of the page 
      - Div is presentational HTML which can be used for layout and design
    
    17. What is CSS used for? 
      - Designing HTML webpage 
    
    18. How to we select an element? Example - every h2 on the page
      - Calling that element's tag followed by brackets 
      - h2 {}
    
    19. What is the difference between a class and an id? - Give me an example of when I might use each one
      - A class can be used multiple times while an id can only be used once 
      - Use an id for the title of the page 
      - Use class for all images on the page 
    
    20. How do we select classes in CSS?
      - A dot before the class name
      - .className{}
    
    21. How do we select a p element with a single class of “human”?
      - .human{}
    
    22. What is a parent child selector? When would this be useful? 
      - Selects all elements that are a child of the specified elemnt
      - It would be useful when you want to style a element inside another element
    
    23. How do you select all links within a div with the class of sidebar?
      - .sidebar a {}
    
    24. What is a pseudo selector?
      - Elements that are in a specific state 
      - ex. first-child, hover, last-child etc. 
    
    25. What do we use the change the spacing between lines?
        - line-height 
    
    26. What do we use to change the spacing between letters?
        - letter-spacing 
        
    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?
        - text-transform: uppercase;
        - text-transform: lowercase;
        - text-transform: capitalize;
    
    28. How do I add a 1px border around my div that is dotted and black?
        - div { border: 1px dotted black; }
    
    29. How do I select everything on the page? 
       - * 
       - Universal selector
    
    30. How do I write a comment in CSS?
      - /**/
    
    31. How do I find out what file I am in, when I am using the command line? 
      - pwd
    
    32. Using the command line - how do I see a list of files/folders in my current folder?
      - ls 
    
    33. How do I remove a file via the command line? Why do I have to be careful with this? 
      - rm fileName.txt
      - There is no safe guards when removing from the command line. Once it's deleted it's gone forever. 
    
    34. Why should I use version control? 
      - So you don't have to have multiple copies of the project as you develop it 
      - Can be used as a backup if needed
    
    35. How often should I commit to github?
      - Every time you complete a feature 
    
    36. What is the command we would use to push our repo up to github? 
      - git push -u origin master 
    
    37. Walk me through Lambda's git flow. 
      - Fork the repo to my github
      - Add the TL as a collaborator to the repo
      - Git clone the repo onto my computer 
      - cd into repo folder
      - Checkout a new branch named 'firstName-lastName'
      - Push up changes periodically with comments on each commit
      - Once I'm done with the project, create a new pull request and add my TL as a reviewer
    
