# tribute-page
i have created it during the internship in Oasis Infobyte
<!DOCTYPE html>
<!--this is level 2.2  where i have to create a page
which contains the three sections 1. video 2. image and a quates 3. footer section-->
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Multi-Section Webpage</title>
<style>
  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
  }
  .section {
    padding: 100px 0;
    text-align: center;
    color: #fff;
  }
  
  video {
    width: 100%;
    height: auto;
  }
  img {
    max-width: 100%;
    height: auto;
    padding-left: 130px;
  }
  .container {
    max-width: 1200px;
    margin: 0 auto;
  }
</style>
</head>
<body>
  <section id="section1" class="section">
    <div class="container">
      <video controls>
        <source src="https://v4.cdnpk.net/videvo_files/video/free/video0485/large_watermarked/_import_61c06141bc69e1.93529050_FPpreview.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </section>
  <style>
    #section1 {
      background-color: rgb(58, 45, 45);
    }
  </style>

  <section id="section2" class="section">
    <div class="container">
      <p>My vision for AI includes social companionship. He believes AI assistants could become tools to enhance social connections and improve communication. He pointed out many people could use more friends and better ways to express themselves.</p>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcREGmw3iT_nRV9Ehhku9Y3FvM7PA4cvuc8odA&usqp=CAU" alt="Image">
    </div>
  </section>
  <style>
    #section2 {
      background-color: rgba(0, 0, 0, 0.9);
      display:flex;
    }
  </style>

  <section id="section3" class="section">
    <div class="container">
      <h1> Biography</h1>
      <p>Steven Paul "Steve"< Jobs was an American information technology entrepreneur and inventor. He was the cofounder, chairperson, and CEO of Apple lnc, CEO and largest share holder of Pixar Animation Studios,and Founder,Chairman, and CEO of NeXT lnc. Jobs is widly recognised as the poineer of the microcomputer revolution of the 1970's along with Apple co-founder Steve Wozniak. "Creative  eatrepreneur whose pasion for perfection and ferocious drive revolutionized six industries: personal computers, animated movies, music, phones, tablet computing, and digital publishing. </p>

      <p>Made with Apple by <a href="####"> Arvind Kumar</a></p>
    </div>
  </section>
  <style>
    #section3 {
      background-color: rgba(1, 1, 0.4, 0.6);
      
    }
  </style>
</body>
</html>
