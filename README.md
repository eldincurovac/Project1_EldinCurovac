
<html lang="en">
  <head>
    <!--
        Name : Eldin Curovac
        Course : Web Application Development
        Assignment : LAB1 
        Due Date: 10/10/2021
        Purpose : To use all the tags we learned in first class and make our first HTML CV Resume. 
    -->
    <meta charset="UTF-8" />
    <!-- This part of the code is for initializing the title of our first website which is going to be shown
    in the browser's tab
-->
    <title> CV - Eldin Curovac </title>
  </head>

  <body>
     <!-- The first and the main header of the website would be shown above 
        the photo of the person -->
      <figure>
    <h1><ins>Biography</ins></h1>
    <img src="cvpic.jpg" alt="My CV photo" style="width:200px;height:200px;">
</figure>
<!-- 
    Since we want to make introudction to the CV and say few words about ourselves,
    we are going to put it in <blockquote> and make it pop out of other text in the website. 
    I tried to use as much as possible tags to practice and did not really write the most important informations
    about myself here. 
-->
    <blockquote>
      <p>
        Hello! My name is <strong>Eldin Curovac</strong> and I am a student of
        the <em>3<sup>rd</sup> year of <abr title = "Software Engineering">SE</abr>, <abr title= "Faculty of Engineering
          and Natural Sciences">FENS</abr> at <abr title= "International University of Sarajevo" > IUS </abr></em>. My tution fee per year was <s>6000€</s>, but with 60% of the scholarship I pay <ins>2400€</ins>. 
      </p>
    </blockquote>

    <!-- 
        I added the first title of the CV which I named "PROFILE" and put here all of the information
        that I think are important for somebody who is trying to get to know me from the CV and hears my
        name for the first time. As well as the little icon connected to the meaning of the title.
    -->
    <br/>
    <hr>
    <h2><strong>PROFILE</strong> <img src="profile.png" alt="Profile Icon" style="width:30px;height:30px;"> </h2>
    <hr>
    <blockquote>
      <p>
        Throughout the CV you can find out that I am very
        <strong>sociable, communicative, open and a person willing to work both alone
          and with a group of people,</strong>
        in a team. My two biggest interests are <strong>programming</strong> and
        <strong>social interaction</strong>
        with people. I find that there are many jobs that just connect these two
        interests of mine. I find that I have an advantage because I speak and
        write English fluently, but I also understand Turkish. In addition, my
        mother tongue is Bosnian, and therefore I speak and write Serbian,
        Croatian and Montenegrin fluently.
      </p>
    </blockquote>
  <br/>
     <!-- 
      All the titles in the CV are divided from other text by the <hr> tag since we are not using the
      CSS for this project and we are trying to make it as nice as possible with only using HTML. All 
      other things remained the same as in the previous title. 
  -->
  <hr>
  <h2><em>EDUCATION</em> <img src="education.png" alt="Education Icon" style="width:30px;height:30px;"> </h2>
  <hr>
    <!--
          This is the first time in this project I am using the list. In this case I am using an ordered
          list since I am listing the schools I attended and talking about my knowledge which is from the time I 
          went to primary school until the present. 
      -->
  <blockquote>
    <ol>
      <li>
        <h3>HIGHER EDUCATION</h3> 
        <p><em>2019 – present</em></p> 
        <p><strong>International University of Sarajevo,
            Faculty of Engineering and Natural sciences, Department of Engineering,
            Software engineering Program</strong>
            <br>
            <p>I am currently a second year student of
                Software Engineering at the Faculty of Engineering and Natural Sciences.
                In the first year, I passed courses related to programming in two
                programming languages (C ++ and Java). I have projects from both
                programming languages. In addition, I have completed a <em>Software
                    Construction course, but also Calculus 1 and Calculus 2, as well as
                    Turkish Language, Understanding Science and Technology , Academic
                    Writing and Reading, Programming Languages, Introduction to Probability
                    and Statistics, Project Management, Disscrete Mathematics , Software
                    Testing and Maintance , Computer Architecture , Database Managemet ,
                    Operations Research, Quality and Realibility Engineering, etc.</em> My
                studies are in English.</p> </p>
      </li>
      <br>
      <li>
        <h3>HIGH SCHOOL</h3> 
        <p><em>2015 - 2019 </em></p> 
        <p><strong>JU MSŠ "ENVER POZDEROVIĆ" - GORAŽDE </strong>
            <br>
            <p>During this period, I showed a strong desire for 
                information technology. In addition, I was <strong>president of the student 
                    council</strong> of my school. In addition, I actively worked on writing 
                    a school magazine, but also writing essays, and won first place at the federal 
                    level in one of the competitions.</p> </p>
      </li>
    </li>
    <br>
    <li>
      <h3>PRIMARY SCHOOL</h3> 
      <p><em>2006 - 2015 </em></p> 
      <p><strong>JU OŠ "HUSEIN EF. ĐOZO " - GORAŽDE </strong>
          <br>
          <p>During elementary school, I first showed a penchant for computer science where I was a
               member of the computer science section. In that section, I first encountered HTML coding.
                It was in elementary school that I participated for the first time in the <em>world competition 
                    <strong>"Hour of Code"</strong>.</em></p> </p>
    </li>
    </ol>
    <br/>
    </blockquote>
    <hr>
          <h2>WORKING EXPERIENCE <img src="work.png" alt="Work Icon" style="width:30px;height:30px;"> </h2> 
          <hr>
          <blockquote>
                <!-- 
                  For this part I am using unordered list just because some of activities were happening or are still 
                  happening in the same time, so we do not really have the right order to form this list. Also, I wanted to
                  have a part of code with unordered list to see how this type of lists are functionating.
              -->
          <ul>
            <li>
                <strong>Editor of the website of the non-governmental organization
                    <em>NETWORK OF STUDENT COUNCILS OF BOSNIA AND HERZEGOVINA</em></strong>
                    <p><em>dec 2019 - present</em></p>
               <p>In this position, I work on editing and updating the website of an organization from Bosnia and Herzegovina that deals with activities with high school students, but also projects that encourage problem solving through activities. Through page editing, I worked on sorting data and writing code related to the website, which gives me experience in HTML.</p> 
        </li>
        <li>
            
            <strong>PEER EDUCATOR
                NETWORK OF STUDENT COUNCILS OF BOSNIA AND HERZEGOVINA
                </strong>
                <p><em>sep 2019 - present</em></p>
           <p>I work with high school students from all over Bosnia and Herzegovina and transfer my knowledge in the field of PR, communication skills, project writing, etc.</p> 
    </li>
<li>
            
    <strong>Traineeship with Erasmus+ Program at Sivas Cumhuriyet Univerity, Turkey 
        </strong>
        <p><em>june 2021 - september 2021 </em></p>
   <p>I was chosen out of 50 and more application to be part of Erasmus+ Program as exchange student in Sivas, Turkey. During my mobility I was working for the host university on Data Mining and jobs connected to programming in Java and Python. </p> 
</li>

        </ul>
        </blockquote>
        <br>
        <hr>
        <h2>SKILLS <img src="skill.png" alt="Skills Icon" style="width:30px;height:30px;"></h2> 
        <hr>
         <!-- 
                  Here, I am again using the unordered lists since I am talking about my skills.
                  Also, this time I tried another type of <ul> tag, "circle" which makes list look
                  organized in a little bit nicer way.
              -->
        <blockquote>
              <h3>SOFT SKILLS</h3>
             
            <ul type="circle">
                <li>
                    Communication </li>
                    <li>Customer service</li>
                    <li>Problem-solving </li>
                        <li>Time management </li>
                            <li>Leadership</li>
                            </blockquote>
<blockquote>
                            <h3>HARD SKILLS</h3>
            <ul type="circle">
                <li>
                    Software (Communication tools, Social Media, Spreadsheet) </li>
                    <li>Word Processing and Desktop Publishing Tools</li>
                    <li>Tools, Computer Programming (C++, Java) </li>
                        <li>Presentation </li>
                            <li>Foreign languages (English, Turkish)</li>
                </ul>
  
                </blockquote>
  
            </ul>
        <br>
        <hr>
            <h2>CONTACT ME <img src="contact.png" alt="Contact Icon" style="width:30px;height:30px;"></h2> 
            <hr>
            <blockquote>

    <!-- 
        The main goal of this part of the code is to use <adress> tag as well as 
            connecting most of the tags we already learn with the goal to have the webpage
            with functionality and ability of reading data clearly from it. 
    -->
    <adress>
      
        <ul>
          
        <li><dl><dt><strong>private e-mail:</strong></dt><dd><a href="mailto:eldin.curovac@icloud.com">
        eldin.curovac@icloud.com</a></dd></li>
        <li><dt><strong>official e-mail:</strong></dt>
          
        <dd><a href="mailto:190302022@student.ius.edu.ba">
          
            e.curovac@student.ius.edu.ba</a></dd></li>
          
        <li><strong>adress:</strong> </li><dd>old adress: <del>Murisa Živojevića 7, Bosna i Hercegovina, Federacija Bosne i Hercegovine, 73000 Goražde</del></dd>
    <dd>new adress: <ins>Stupska bb, Bosna i Hercegovina, Federacija Bosne i Hercegovine, 71000 Sarajevo</ins></dd></li>
        <li><dl><dt><strong>phone number: </strong></dt><dd>
          
            <ins>+387 62 - 644 / 697</ins></dd></li>
          
    </dl>
</ul>

</adress>       
</blockquote>
    </body>
</html>

