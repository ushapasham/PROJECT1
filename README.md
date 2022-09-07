# PROJECT1
<!DOCTYPE html>
<html lang='en'>
  <head>
    <meta charset="utf-8">
    <meta name="viewpoint" content="width=device-width">
    <title>Basic HTML</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <main>
      <nav class='navBar'>
        <h1>Usha Pasham Portfolio</h1>
          <div class= 'navigationMenu'>
            <a href='#aboutMe'>About Me</a>
            <a href='#Skills'>Skills</a>
            <a href='#projects'>Projects</a>
            <a href='#contactForm'>Let's Connect!</a>
          </div>
         </nav>
      <section class='heroSection'>
        <img clss='profileImage'
        src='https://cdn-icons-png.flaticon.com/512/194/194938.png'>
        <div class='herosectionDetails'>
        <h1>Usha Pasham</h1>
        <h3>Computer Science Engineering</h3>
        </div>
      </section>
      <section class='aboutMe' id='aboutMe'>
        <h1>What I Do...</h1>
        <p> <b>Hi I am Usha Pasham  b.tech 2nd year from KL University Hyderabad</b>. I created this website for my Profile.
       <i>  <b> WHAT IS HTML</b><i>
         <i> HTML (HyperText Markup Language) is the code that is used to structure a web page and its content.
           For example, content could be structured within a set of paragraphs, a list of bulleted points, or using images and data tables</i>
        </p>
      </section>
      <section class='skillsAndProjects'>
        <div class='skills' id=skills>
          <h1 class='cardHeading'>Skills</h1>
          <img src='/images/html.svg' title='HTML'>
          <img src='/images/java.svg' title='Java'>
          <img src='/images/python.svg' title='Python'>
          <img src='/images/c.svg' title='C'>
          
        </div>
        <div class='projects' id='projects'>
          <h1 class='cardHeading'>Projects</h1>
          <div class='projectContainer'>
            <img src='/images/c.svg'>
            <div class='projectDescription'>
              <h4>Project Name</h4>
              <p>Some details of the project.Some details of the project.Some details about the project.</p>
          </div>
        </div>
           
           <div class='projectContainer'>
            <img src='/images/c.svg'>
            <div class='projectDescription'>
              <h4>Project Name</h4>
              <p>Some details of the project.</p>
          </div>
        </div>
      </section>
      <section class='contactForm' id='contactForm'>
        <h1>Let's Connect!</h2>
        <div class='formGroup'>
          <label for='name'>Enter Full Name</label><br/>
          <input type='text' id='name' placeholder='Full Name'/>
        </div>
        <div class='formGroup'>
          <label for='email'>Email</label><br/>
          <input type='text' id='email' placeholder='Email' />
        </div>
        <div class='formGroup'>
          <label for='message'>Message</label><br/>
          <textarea placeholder="Send some message!" id="message" name="w3review"
            rows="4" cols="50"></textarea>
        </div>
        <button class='submitButton' onClick={submit()}>Connect</button>
      </section>
      
    </main>
