# https-ashleyfelton.github.io-index.html
Different landing pages that contains different styles and components 
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Work It</title>
    <style>
      body {
        background: radial-gradient(
          circle at 10% 20%,
          rgb(242, 235, 243) 0%,
          rgb(234, 241, 249) 90.1%
        );
      }
      h1 {
        text-align: center;
        color: rgb(86, 188, 226);
      }
      h2 {
        text-align: center;
        color: rgb(135, 238, 154);
      }
      img {
        display: block;
        margin: 0 auto;
        border-radius: 10px;
      }
      p {
        text-align: center;
      }
      .title {
        font-weight: 700;
        font-size: large;
        color: rgb(86, 188, 226);
      }
      a {
        text-decoration: none;
        cursor: pointer;
        color: rgb(86, 1, 86);
      }
      div {
        padding-top: 25px;
        padding-bottom: 25px;
      }
      button {
        display: block;
        margin: 0 auto;
        border: 0;
        border-radius: 20px;
        background-color: rgb(86, 1, 86);
        color: rgb(242, 235, 243);
        padding: 10px;
        line-height: 20px;
        box-shadow: rgba(40, 1, 40, 0.9) 4px 4px 15px 0;
        transition: all 200ms ease-in-out;
      }
      button:hover {
        color: rgb(86, 1, 86);
        background-color: rgb(242, 235, 243);
        cursor: pointer;
      }
      .overall {
        max-width: 600px;
        margin: 0 auto;
      }
    </style>
  </head>
  <body>
    <div class="overall">
      <h1>Move Your Body</h1>
      <h2>You only get one!</h2>
      <hr />
      <br />
      <img
        src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/056/438/original/workout_collage.jpg?1670203037"
        alt="collage of people working out"
        width="500px"
      />
      <br />
      <p>
        Want the cheat code to feeling better, looking better, and being
        healthy? All you have to do is move your body. Exercsing is the most
        fundamental activity in keeping your heart, brain, and body healthy.
        Doctors recommend at least 150 minutes of aerobic exercise a week. There
        are so many ways to reach this goal. You can go to the gym and weight
        lift or do cardio. You can do yoga...Its harder than you think. Hiking
        is also a great way while exploring the outdoors. Playing sports with
        friends. Biking around the city while running errands. It can even be as
        fun as dancing or roller skating with friends. There is no one path to a
        healthier you, there are many. All you have to do is...<span
          class="title"
          >move your body</span
        >
        .
      </p>
      <div style="text-align: center">
        <a
          href="https://www.nytimes.com/guides/smarterliving/how-to-start-exercising"
          target="_blank"
          ><strong><em>Click here to start getting healthy</em></strong></a
        >
      </div>
      <button>Talk with a trainer today!</button>
      <script>
        function talkWithTrainer() {
          let name = prompt("Hello, what is your name?");
          let training = prompt(
            "Would you be interested in talking with a trainer?"
          );

          if (
            training === "yes" ||
            training === "Yes" ||
            training === "Yeah" ||
            training === "yeah"
          ) {
            alert(
              "Congratulations " +
                name +
                "! You are one step closer to a healthier you."
            );
          } else {
            alert(
              "Get your body moving anyway you can. I beleive in you " +
                name +
                "!"
            );
          }
        }

        let trainerButton = document.querySelector("button");
        trainerButton.addEventListener("click", talkWithTrainer);
      </script>
    </div>
  </body>
</html>
