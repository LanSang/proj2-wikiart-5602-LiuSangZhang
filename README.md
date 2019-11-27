<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WikiArt Analysis</title>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
    <link href="style.css" type="text/css" rel="stylesheet">
  </head>
  <body>
<!--     <header class ="container">
      <div class ="row">
        <h1 class = "col-sm-6">WikiArt Analysis</h1>
          <nav class = "col-sm-6 text-right">
            <a href = "experience.html">Styles</a>
            <a href = "education.html">Design</a>
            <a href = "about.html">About Us</a>
          </nav>
      </div>

      <section class = "jumbotron" style="height: 800px;">
        <div class ="container">
          <div class= "row">
            <h2>Emotion in Art</h2>
          </div>
        </div>
       </section>
    </header> -->
<!--     <section class = "jumbotron" style="height: 800px;">
        <div class ="container">
          <div class= "row">
            <h2>Emotion in Art</h2>
          </div>
        </div>
    </section> -->


    <header id="header" class="header" style="height: 700px;">
      <div class ="row">
        <div class = "col-sm-1"></div>
        <h1 class = "col-sm-5" style="font-size:24px;" >WikiArt Analysis</h1>
        <nav class = "col-sm-6 text-right">
          <a href = "#category">Styles</a>
          <a href = "design.html">Design</a>
          <a href = "about.html">About Us</a>
        </nav>
      </div>



        <div class="header-content">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <div class="text-container">
                            <h1>Emotion in Art </h1>
                            <p class="p-heading p-large">asdfghjklasdfghjklasdfghjklasdfghjklasdfghjklasdfghjklasdfghjklasdfghjklsdfghjklsdfghjklasdfghjklasdfghjklasdfghjkasdfghjkasdfghjkl</p>
                        </div>
                    </div> 
                </div> 
            </div>
        </div> 
    </header> 

<!--     <div id="counter">
        <div class="cell">
            <div class="counter-value number-count" data-count="231">1</div>
            <div class="counter-info">Happy<br>Users</div>
        </div>
        <div class="cell">
            <div class="counter-value number-count" data-count="121">1</div>
            <div class="counter-info">Issues<br>Solved</div>
        </div>
        <div class="cell">
            <div class="counter-value number-count" data-count="159">1</div>
            <div class="counter-info">Good<br>Reviews</div>
        </div>
    </div> -->

     <section id = "style-category" class = "container">
          <p>WikiArt Emotions Dataset has annotastion for around 4000 pieces of arts created between 1415 and 2012 from FOUR western styles: <span style="color:#aa7942;">Renaissance Art</span>, <span style="color:#778899;">Post Renaissance Art</span>, <span style="color:#ba55d3;">Modern Art</span>, and <span style="color:#ff0000;">Contemporary Art</span>. The four styles of arts consist of TWENTY-TWO categories: <span style="color:#aa7942;">Early Renaissance, High Renaissance, Northern Renaissance</span>, <span style="color:#778899;">Baroque, Neoclassicism, Realism, Rococo, Romanticism</span>, <span style="color:#ba55d3;">Abstract Art, Abstract Expressionism, Art Informel, Color Field Painting, Cubism, Expressionism, Impressionism, Lyrical Abstraction, Magic Realism, Neo-Expressionism, Pop Art, Post-Impressionism, Surrealism</span>, and <span style="color:#ff0000;">Minimalism</span>. The style and category of art that is popular has been changing over the years.</p>
          <video width="1150" height="600" controls style="clear:both;display:block;margin:auto; max-width: 100%; height: auto !important;">
            <source src="images/category_overTime.mov" type="video/mp4">
            <source src="movie.ogg" type="video/ogg">
            Your browser doesn't support HTML5 video。
          </video>
    </section>

     <section id = "category-count" class = "container">
      <div class = "row">
        <div class = "col-sm-5 explain">
          <div class ="font-weight-bold">
            <h3>Styles & Categories</h3>
            <p>Each art style has different numbers of categories, and the number of annotated arts is generally the same for each category. As a result, we see the most annotated art pieces for <span style="color:#ba55d3;">Modern Art</span>, which has the largest number of categories, followed by <span style="color:#778899;">Post Renaissance Art</span>, <span style="color:#aa7942;">Renaissance Art</span>, and lastly <span style="color:#ff0000;">Contemporary Art</span>.</p>
          </div>
        </div>
        <div class = "col-sm-7">
          <img class ="portrait" src = "images/style_category_count@2x.png">
        </div>
    </section>

    <section id ="category-rate" class = "container">
      <div class = "row">
        <div class = "col-sm-6">
          <img class ="portrait" src = "images/style_category_meanRate@2x.png" style="max-width: 90%;max-height: 90%; width: auto; height: auto;">
        </div>
        <div class = "col-sm-6 explain">
          <div class ="font-weight-bold">
          <h3>Like Rating for categories</h3>
          <p > People today tend to like arts of <span style="color:#aa7942;">Renaissance</span> and <span style="color:#778899;">Post Renaissance Arts</span>, but their attitudes towards <span style="color:#ba55d3;">Modern Arts</span> vary a lot by the specific category. <span style="color:#ff0000;">Contemporary Art</span> is not really favored by contemporary people. </p>
        </div>
        </div>
    </section>

     <section id = "emotion" class = "container">
          <h2>Is there any pattern in the emotions art pieces of different styles and categories evoke?</h2>
          <p> Art evokes emotions in observers. One piece of art can arouse multiple types of emotions, and different art can arouse different emotions. Is there any pattern in the emotions art pieces of different styles and categories evoke?</p>
          <video width="1150" height="600" controls style="clear:both;display:block;margin:auto;max-width: 100%; height: auto !important;">
            <source src="images/EmotionVote_byStyleCategory.mov" type="video/mp4">
            <source src="movie.ogg" type="video/ogg">
            Your browser doesn't support HTML5 video。
          </video>
      </section>

     <section id = "emotion-count" class = "container">
      <div class = "row">
        <div class = "col-sm-7">
          <img class ="portrait" src = "images/emotion_type_count@2x.png">
        </div>
        <div class = "col-sm-5 explain">
          <div class ="font-weight-bold">
            <h3>Emotions & Types</h3>
            <p>WikiArt Emotions Dataset has annotations of TWENTY emotions: <span style="color:#53da18;">Gratitude, Happiness, Humility, Love, Optimism, Trust</span>, <span style="color:#ff9900;">Anger, Arrogance, Disgust, Fear, Pessimism, Regret, Sadness, Shame</span>, <span style="color:#0b5394;">Agreeableness, Anticipation, Disagreeableness, Shyness, Surprise</span>, and <span style="color:#0b5394;">Neutral</span> from THREE types: <span style="color:#53da18;">Positive</span>, <span style="color:#ff9900;">Negative</span>, and <span style="color:#0b5394;">Other or Mixed</span>. Most art pieces evoke Positive emotions, less art pieces evoke Negative emotions, and Other or Mixed emotions are least evoked.</p>
          </div>
        </div>
    </section>

    <section id ="emotion-rate" class = "container">
      <div class = "row">
        <div class = "col-sm-6 explain">
          <div class ="font-weight-bold">
            <h3>Emotion Rating</h3>
            <p> Considering all Styles and Categories, <span style="color:#53da18;">Happiness, Trust, Humility</span> and <span style="color:#53da18;">Optimism</span> are the most common <span style="color:#53da18;">Positive</span> emotions people feel about arts. <span style="color:#ff9900;">Fear</span> and <span style="color:#ff9900;">Sadness</span> are the most commonly evoked <span style="color:#ff9900;">Negative</span> emotions. <span style="color:#0b5394;">Surprise</span> and <span style="color:#0b5394;">Anticipation</span> are the most commonly aroused <span style="color:#0b5394;">Other or Mixed emotions</span>. </p>
          </div>
        </div>
        <div class = "col-sm-6">
          <img class ="portrait" src = "images/emotion_type_meanScore@2x.png" style="max-width: 90%;max-height: 90%; width: auto; height: auto;">
        </div>
    </section>


    <section id = "corralation" class = "container">
      <div class = "row">
        <div class = "col-sm-7">
          <img class ="portrait" src = "images/emotionByType.png">
        </div>
        <div class = "col-sm-5 explain">
          <h3>Like and Emotion</h3>
          <p class = "font-weight-bold"> Is there any relationship between the degree people like an art Style and the type and degree of Emotions that art Style evokes? Very likely! <span style="color:#aa7942;">Renaissance</span> and <span style="color:#778899;">Post Renaissance Arts</span> are the two art Styles people like most. They both evoke the strongest <span style="color:#53da18;">Positive</span> emotions and weakest <span style="color:#0b5394;">Other or Mixed</span> emotions. The <span style="color:#ff9900;">Negative</span> emotions they evoke are also relatively strong compared to the emotions evoked by <span style="color:#ba55d3;">Modern</span> and <span style="color:#ff0000;">Contemporary Arts</span>. <span style="color:#ff0000;">Contemporary</span> Art is the art Style people dislike. The emotions it arouses tend to be of a lower degree. The strongest emotion type it evokes is <span style="color:#0b5394;">Other or Mixed</span> and the weakest emotion type it evokes is <span style="color:#53da18;">Positive</span> and <span style="color:#ff9900;">Negative</span>, a pattern opposite to <span style="color:#aa7942;">Renaissance</span> and <span style="color:#778899;">Post Renaissance Arts</span>. People tend to like <span style="color:#ba55d3;">Modern Art</span>, though to a much lower degree than <span style="color:#aa7942;">Renaissance</span> and <span style="color:#778899;">Post Renaissance Arts</span>. <span style="color:#ba55d3;">Modern Art</span> evokes less strong emotions on average, though it still evokes stronger <span style="color:#53da18;">Positive</span> emotions than <span style="color:#0b5394;">Other or Mixed</span> and <span style="color:#ff9900;">Negative</span>.</p>
        </div>
    </section>



    <section id="category">
      <div class="container">
        <div class = "row">
         <div class="imgcard col-sm-3" onclick="{location.href='detail.html'}">
            <img src="images/r.png" style="width:100%">
             <div class="container">
                 <p>Renaissance Art</p>
             </div>
         </div>

         <div class="imgcard col-sm-3" onclick="{location.href='detail-pr.html'}">
            <img src="images/pr.png" style="width:100%"/>
             <div class="container">
                 <p>Post Renaissance Art</p>
             </div>
         </div>

        <div class="imgcard col-sm-3" onclick="{location.href='detail-m.html'}">
            <img src="images/m.png" style="width:100%">
             <div class="container">
                 <p>Modern Art</p>
             </div>
        </div>

        <div class="imgcard col-sm-3" onclick="{location.href='detail-c.html'}">
          <img src="images/c.png" style="width:100%"/>
           <div class="container">
               <p>Contemporary Art</p>
           </div>
       </div>

       </div>
    </div>
  </section>


  <div id="gotop">
    <div class="arrow"></div>
    <div class="stick"></div>
  </div>




    <footer class = "container" >
        <div class = "row" >
          <p>&copy; 2019 INFO 5602 Group 5</p>
        </div>
    </footer>




    <script src="http://cdn.staticfile.org/jquery/1.11.1-rc2/jquery.min.js"></script>
    <script>
      $(function(){

          $(window).scroll(function(){  

              var scrollt = document.documentElement.scrollTop + document.body.scrollTop; 

              if( scrollt >800 ){  

                  $("#gotop").fadeIn(400); 

              }else{

                  $("#gotop").stop().fadeOut(400); 

              }

          });

          $("#gotop").click(function(){ 

              $("html,body").animate({scrollTop:"0px"},200);

          }); 

      });
    </script>
  </body>
</html>