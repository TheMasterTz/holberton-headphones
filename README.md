# 0x09. Implement a design from scratch
## Details
      By Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School          Weight: 3                Ongoing project - started Apr 28, 2022 , must end by May 3, 2022           - you're done with 0% of tasks.      Manual QA review must be done          (request it when you are done with the project)      ## Concepts
For this project, students are expected to look at this concept:
* [Implement a design](https://intranet.hbtn.io/concepts/220) 

In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously. 
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.
Here the final result:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220501T202336Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3082eaf191da00b333bc5fe2b2993d9133b5eb0ad877f99d322f0d9168fff4bf) 

This webpage has been designed by Nicolas Philippot, UI/UX designer.You can find final screens  [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip) 

### Requirements
* you are not allowed to import external CSS framework (like Bootstrap)
* you are not to use Javascript
## Tasks
### 0. Read and be familiar with Figma
          mandatory         Progress vs Score  Task Body Create an account in  [Figma](https://intranet.hbtn.io/rltoken/eumOUW-eMS4X9ZDZg9KPLg) 
  and open this  [project](https://intranet.hbtn.io/rltoken/2ED3P1a2wnbQqRLi8aXJKw) 
  and “Duplicate to your Drafts” to have access to all design details.
If you can’t access to it, please find here the  [Figma file](https://intranet.hbtn.io/rltoken/NxsDNicWs5KSlsR94kt52A) 

 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220501T202336Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=08a3d3632e6f14e76b1a05516b6a8e94e8178c7bd08de63762103190d67393db) 

Important notes with Figma:
* if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/wltHny-KZP3B8JFRvpmVjA) 
 and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/Qb96K4nTPQJO1paP_OBELw) 

* some values are in float - feel free to round them
For this task, please write an amazing   ` README.md ` 
Interactions note:
* the web page must switch to the mobile version when the screen width is 480px or less
* links hover/active:  ` #FF6565 ` 
* button hover/active:  ` opacity: 0.9 ` 
* max width of the content: 1000px centered in the page
 Task URLs  Github information Repo:
* GitHub repository:  ` holberton-headphones ` 
* File:  ` README.md ` 
 Self-paced manual review  Panel footer - Controls 
### 1. Header
          mandatory         Progress vs Score  Task Body Building a web page the right way, is not easy - expect if you put in place strong foundations:
* reset CSS styling
* use variables
* simple/“as generic as you can” CSS selectors
* avoid using super specific CSS selectors as much as possible
* simple HTML structure -  ` div `  containers are your friend!
Last advice: Personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.
Now, your turn!
For this first task:  create the header/hero piece
Here an archive of all assets needed:  [images_0x09.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220501T202336Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=3c4b97763e6f45bddb58456c1ca3965e786609ebc04f2d1774f55016112a5c75) 

Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/4a93441c93989ad7ea72.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220501T202336Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=27fd4b0ca71de0be8069caa7b918e617f4dce9073e66033d70fabb4d8f9f8ae3) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/75a582f98640445a2dbf.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220501T202336Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d4dc6214411c309252b7ea0fbdd9957711887655531bd6d46b9e24e64c79f624) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holberton-headphones ` 
* File:  ` 0-index.html, 0-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 2. "What we do..." section
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
For this second task:  create the “What we do…” section
In this section, you will need custom font icons. Here the archive of it:  [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220501T202336Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=7d53d4d1d21b8b4e21cfb94d16817917598810375433ed60def3b01ed8f061b7) 
  Inside you will find demo page of how to use it.
Important:  try to build as generic as you can… you will probably need some components in next section.
 Task URLs  Github information Repo:
* GitHub repository:  ` holberton-headphones ` 
* File:  ` 1-index.html, 1-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 3. "Our results" section
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
For this third task:  create the “Our results” section
Now you can reuse components form the previous task!
 Task URLs  Github information Repo:
* GitHub repository:  ` holberton-headphones ` 
* File:  ` 2-index.html, 2-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 4. Contact us
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
A good landing page has always a contact form.
You are free to add any animations and/or constraints on fields.
 Task URLs  Github information Repo:
* GitHub repository:  ` holberton-headphones ` 
* File:  ` 3-index.html, 3-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 5. Footer
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
Last piece of the page… the Footer!
When you are done, here the result:
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220501T202336Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7ecf9966eb0e052170ec169ad5098486bfa3e427cd242900ab1b44f5cf60a968) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/83d6311e87d4775ca4b3.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220501T202336Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e7731195f9d39bbcf721bb5e96b3fbe12c9772f3115297d5befcb03c6c32e5ae) 

And you are done! 
Good job!
 Task URLs  Github information Repo:
* GitHub repository:  ` holberton-headphones ` 
* File:  ` 4-index.html, 4-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
[Done with the mandatory tasks? Unlock 3 advanced tasks now!](https://intranet.hbtn.io/projects/622/unlock_optionals) 

Ready for a  manual review