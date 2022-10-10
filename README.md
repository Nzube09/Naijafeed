<!DOCTYPE html>

<html>

<head>

   <title></title>

   <style>

      @import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300..700&display=swap");

*,

*::before,

*::after {

  box-sizing: border-box;

  padding: 0;

  margin: 0;

}

body {

  font-family: "Quicksand", cursive;

  display: inline-grid;

  place-items: center;

  height: 100vh;

  background: #7f7fd5;

  background: linear-gradient(to right, #91eae4, #86a8e7, #7f7fd5);

}

.container {

  display: flex;

  flex-wrap: wrap;

  justify-content: center;

  max-width: 1200px;

  margin-block: 2rem;

  gap: 2rem;

}

img {

  max-width: 10%;

  display: block;

  object-fit: cover;

}

.card {

  display: grid;

  flex-direction: column;

  width: clamp(20rem, calc(20rem + 2vw), 22rem);

  overflow: hidden;

  box-shadow: 0 .1rem 1rem rgba(0, 0, 0, 0.1);

  border-radius: 1em;

  background: #ECE9E6;

background: linear-gradient(to right, #FFFFFF, #ECE9E6);

}

.card__body {

  padding: 1rem;

  display: flex;

  flex-direction: column;

  gap: .5rem;

   background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);

    background-size: 400% 400%;

    animation: gradient 10s ease infinite;

}

@keyframes gradient {

    0% {

        background-position: 0% 50%;

    }

    50% {

        background-position: 100% 50%;

    }

    100% {

        background-position: 0% 50%;

    }

}

.tag {

  align-self: flex-start;

  padding: .25em .75em;

  border-radius: 1em;

  font-size: .75rem;

}

.tag + .tag {

  margin-left: .5em;

}

.tag-blue {

  background: #56CCF2;

background: linear-gradient(to bottom, #2F80ED, #56CCF2);

  color: #fafafa;

}

.tag-brown {

  background: #D1913C;

background: linear-gradient(to bottom, #FFD194, #D1913C);

  color: #fafafa;

}

.tag-red {

  background: #cb2d3e;

background: linear-gradient(to bottom, #ef473a, #cb2d3e);

  color: #fafafa;

}

.card__body h4 {

  font-size: 1.5rem;

  text-transform: capitalize;

}

.card__footer {

  display: flex;

  padding: 1rem;

  margin-top: auto;

    background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);

    background-size: 400% 400%;

    animation: gradient 10s ease infinite;

}

@keyframes gradient {

    0% {

        background-position: 0% 50%;

    }

    50% {

        background-position: 100% 50%;

    }

    100% {

        background-position: 0% 50%;

    }

}

.user {

  display: flex;

  gap: .5rem;

}

.user__image {

  border-radius: 50%;

}

.user__info > small {

  color: #666;

}

   </style>

</head>

<body background="yellow">

<h1 align="center">Russia Vs Ukraine</h1>

    

   <div class="container">

   <br>

   <br><br>

   

   

   <div class="card">

         <div class="card__header">

            <iframe width="350" height="240" class="card__image" src="https://www.youtube.com/embed/tfAwRP93wI0"></iframe> 

         </div>

         <div class="card__body">

            <span class="tag tag-blue">Sad News</span>

            <h4>Sad News For Indian</h4>

            <p>An Indian student was killed after being hit by shelling in Kharkiv, a city in eastern Ukraine, the government said Tuesday. The victim is from Karnataka, and was a fourth year medicine student of Kharkiv National Medical University.</p>

         </div>

         <div class="card__footer">

            <div class="user">

               <img src="https://blob.sololearn.com/avatars/fa70d18e-9827-4728-87e4-5b757c95e4a1.jpg" alt="user__image" class="user__image">

               <div class="user__info">

                  <h5>Vaibhav Singh</h5>

                     <small>2h ago</small>

               </div>

            </div>

         </div>

      </div>

   

   

   

   

   

   

   

      <div class="card">

         <div class="card__header">

            <iframe width="350" height="240" class="card__image" src="https://www.youtube.com/embed/CEZyzD-8UR0"></iframe> 

         </div>

         <div class="card__body">

            <span class="tag tag-blue">Ukraine News</span>

            <h4>Ukraine Latest news</h4>

            <p>Russian Presidend Putin has oreder his Nuclear Department Forces to be on alert.</p>

         </div>

         <div class="card__footer">

            <div class="user">

               <img src="https://blob.sololearn.com/avatars/fa70d18e-9827-4728-87e4-5b757c95e4a1.jpg" alt="user__image" class="user__image">

               <div class="user__info">

                  <h5>Vaibhav Singh</h5>

                     <small>2h ago</small>

               </div>

            </div>

         </div>

      </div>

      <div class="card">

         <div class="card__header">

            <iframe width="350" height="240" class="card__image" src="https://www.youtube.com/embed/71lyeWd5JVw"></iframe> 

         </div>

         <div class="card__body">

            <span class="tag tag-blue">Ukraine News</span>

            <h4>Ukraine Latest news</h4>

            <p>Russian Presidend Putin has oreder his Nuclear Department Forces to be on alert.</p>

         </div>

         <div class="card__footer">

            <div class="user">

               <img src="https://blob.sololearn.com/avatars/fa70d18e-9827-4728-87e4-5b757c95e4a1.jpg" alt="user__image" class="user__image">

               <div class="user__info">

                  <h5>Vaibhav Singh</h5>

                     <small>2h ago</small>

               </div>

            </div>

         </div>

      </div>

      <div class="card">

         <div class="card__header">

            <iframe width="350" height="240" class="card__image" src="https://www.youtube.com/embed/KfG1byiMQHw"></iframe> 

         </div>

         <div class="card__body">

            <span class="tag tag-blue">Ukraine News</span>

            <h4>The Battle For Kyiv</h4>

            <p>The day that many feared would never come has arrived far sooner than anyone expected.After a night of intense shelling on the Ukrainian capital, Russian operatives are now in Kyiv.</p>

         </div>

         <div class="card__footer">

            <div class="user">

               <img src="https://blob.sololearn.com/avatars/fa70d18e-9827-4728-87e4-5b757c95e4a1.jpg" alt="user__image" class="user__image">

               <div class="user__info">

                  <h5>Vaibhav Singh</h5>

                     <small>2h ago</small>

               </div>

            </div>

         </div>

      </div>

      <div class="card">

         <div class="card__header">

            <iframe width="350" height="240" class="card__image" src="https://www.youtube.com/embed/HIPNVm6lNfM"></iframe> 

         </div>

         <div class="card__body">

            <span class="tag tag-blue">Ukraine Live</span>

            <h4>Ukraine Live</h4>

            <p>Live Earth Cam View for Ukraine.

            It is Available On Youtube.</p>

         </div>

         <div class="card__footer">

            <div class="user">

               <img src="https://blob.sololearn.com/avatars/fa70d18e-9827-4728-87e4-5b757c95e4a1.jpg" alt="user__image" class="user__image">

               <div class="user__info">

                  <h5>Vaibhav Singh</h5>

                     <small>2h ago</small>

               </div>

            </div>

         </div>

      </div>

      <div class="card">

         <div class="card__header">

            <iframe width="350" height="240" class="card__image" src="https://www.youtube.com/embed/VaA5LDP7kgk"></iframe> 

         </div>

         <div class="card__body">

            <span class="tag tag-blue">Ukraine People</span>

            <h4>Ukraine Citizen</h4>

            <p>Former Miss Ukraine <b>Anastasia Lenna</b> has Joined The Military To Fight Against Russia. Other Ukraine Also Joined The Army Who Is Above 18 Years And Below 65 Years Old.</p>

         </div>

         <div class="card__footer">

            <div class="user">

               <img src="https://blob.sololearn.com/avatars/fa70d18e-9827-4728-87e4-5b757c95e4a1.jpg" alt="user__image" class="user__image">

               <div class="user__info">

                  <h5>Vaibhav Singh</h5>

                     <small>2h ago</small>

               </div>

            </div>

         </div>

      </div>

      <div class="card">

         <div class="card__header">

            <iframe width="350" height="240" class="card__image" src="https://www.youtube.com/embed/4vSCRfs5ZTs"></iframe> 

         </div>

         <div class="card__body">

            <span class="tag tag-blue">Ukraine News</span>

            <h4>Ukraine News</h4>

            <p>The World's largest aircraft, the Ukrainian An-225 Mriya has been destroyed.</p>

         </div>

         <div class="card__footer">

            <div class="user">

               <img src="https://blob.sololearn.com/avatars/fa70d18e-9827-4728-87e4-5b757c95e4a1.jpg" alt="user__image" class="user__image">

               <div class="user__info">

                  <h5>Vaibhav Singh</h5>

                     <small>2h ago</small>

               </div>

            </div>

         </div>

      </div>

      <div class="card">

         <div class="card__header">

            <iframe width="350" height="240" class="card__image" src="https://www.youtube.com/embed/1CsypolHYhM"></iframe> 

         </div>

         <div class="card__body">

            <span class="tag tag-blue">Indian Student</span>

            <h4>Good News For Indian Student</h4>

            <p>Poland Is Allow Indian Students To Enter Poland Without Any Visa. So Far, A Total 469 Indian nationals Have Been Evacuated For War-Hit Ukraine.</p>

         </div>

         <div class="card__footer">

            <div class="user">

               <img src="https://blob.sololearn.com/avatars/fa70d18e-9827-4728-87e4-5b757c95e4a1.jpg" alt="user__image" class="user__image">

               <div class="user__info">

                  <h5>Vaibhav Singh</h5>

                     <small>2h ago</small>

               </div>

            </div>

         </div>

      </div>

   </div>

</body>

</html>
