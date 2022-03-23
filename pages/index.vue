<template>
  <main class="container">
    <div class="left_side">
      <div class="text_bar">
        <span class="lateral_text">©Salomé Dain</span>
        <span class="lateral_text">Agence BOBARD</span>
        <span class="lateral_text">Cabaniste</span>
      </div>

      <img class="image" src="~/assets/photo_antoine.jpg" alt="" />
    </div>

    <div class="right-side">
      <p>
        On a planté
        <br />
        notre site,
        <br />
        On attend
        <br />
        qu'il pousse.
      </p>
      <div class="contact">
        <span class="second_text">Site en construction </span>
        <span class="third_text">Contactez-nous à: </span>
        <span class="fourth_text">lucie@agence-bobard.com</span>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
<style>
body {
  margin: 0;
  font-family: "Inter", sans-serif;
  background-color: #f4f4ed;
}
.lateral_text {
  font-weight: 600;
}
@media (min-width: 1800px) and (max-width: 2000px) {
  .container {
    display: flex;
    margin: 0;
  }
  .left_side {
    height: 100vh;
    display: flex;
    width: 60%;
  }
  .text_bar {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: flex-end;
    height: 100vh;
    width: 3rem;
    margin-right: 1rem;
  }
  .lateral_text {
    writing-mode: vertical-rl;
    text-orientation: sideways-left;
    transform: rotate(180deg);
    text-transform: uppercase;
    font-family: "Fredoka", sans-serif;
  }
  .image {
    width: 85%;
    object-fit: cover;
  }
  .right-side {
    display: flex;
    flex-direction: column;
    width: 45%;
    margin-top: 15%;
  }
  p {
    justify-self: center;
    font-size: 5.5rem;
    text-transform: uppercase;
    font-family: "Fredoka", sans-serif;
    color: rgb(250, 211, 137);
    text-transform: uppercase;
    line-height: 1.2;
    text-align: justifyLeft;
    text-shadow: 0px 3px 3.68px rgba(0, 0, 0, 0.08);
    margin: 3rem 0 0 0;
  }

  .contact {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: flex-end;
    padding: 7rem 5rem 0 0;
  }
  .second_text {
    font-size: 2rem;
    margin-bottom: 1.5rem;
    font-family: "Inter", sans-serif;
  }
  .third_text {
    font-size: 2rem;
    font-family: "Inter", sans-serif;
  }
  .fourth_text {
    font-size: 2rem;
    font-style: italic;
    font-weight: 600;
    font-family: "Inter", sans-serif;
  }
}
@media (min-width: 1224px) and (max-width: 1800px) {
  .container {
    display: flex;
    margin: 0;
  }
  .left_side {
    height: 100vh;
    display: flex;
    width: 60%;
  }
  .text_bar {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: flex-end;
    height: 100vh;
    width: 3rem;
    margin-right: 1rem;
  }
  .lateral_text {
    writing-mode: vertical-rl;
    text-orientation: sideways-left;
    transform: rotate(180deg);
    text-transform: uppercase;
    font-family: "Fredoka", sans-serif;
  }
  .image {
    width: 85%;
    object-fit: cover;
  }
  .right-side {
    display: flex;
    flex-direction: column;
    width: 45%;
    margin-top: 10%;
  }
  p {
    justify-self: center;
    font-size: 4rem;
    text-transform: uppercase;
    font-family: "Fredoka", sans-serif;
    color: rgb(250, 211, 137);
    line-height: 1.2;
    text-shadow: 0px 3px 3.68px rgba(0, 0, 0, 0.08);
    margin: 3rem 0 0 0;
  }

  .contact {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: flex-end;
    padding: 5rem 5rem 0 0;
  }
  .second_text {
    font-size: 1.6rem;
    margin-bottom: 1.5rem;
    font-family: "Inter", sans-serif;
  }
  .third_text {
    font-size: 1.6rem;
    font-family: "Inter", sans-serif;
  }
  .fourth_text {
    font-size: 1.6rem;
    font-style: italic;
    font-weight: 600;
    font-family: "Inter", sans-serif;
  }
}
@media (min-width: 600px) and (max-width: 1224px) {
  .container {
    display: flex;
    margin: 0;
  }
  .left_side {
    height: 100vh;
    display: flex;
    width: 60%;
  }
  .text_bar {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: flex-end;
    height: 100vh;
    width: 3rem;
    margin-right: 1rem;
  }
  .lateral_text {
    writing-mode: vertical-rl;
    text-orientation: sideways-left;
    transform: rotate(180deg);
    text-transform: uppercase;
    font-family: "Fredoka", sans-serif;
  }
  .image {
    width: 85%;
    object-fit: cover;
  }
  .right-side {
    display: flex;
    flex-direction: column;
    width: 45%;
    margin-top: 15%;
  }
  p {
    justify-self: center;
    font-size: 3rem;
    text-transform: uppercase;
    font-family: "Fredoka", sans-serif;
    color: rgb(250, 211, 137);
    line-height: 1.2;
    text-shadow: 0px 3px 3.68px rgba(0, 0, 0, 0.08);
    margin: 3rem 0 0 0;
  }

  .contact {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: flex-end;
    padding: 5rem 1rem 0 0;
  }
  .second_text {
    font-size: 1.3rem;
    margin-bottom: 1.5rem;
    font-family: "Inter", sans-serif;
  }
  .third_text {
    font-size: 1.3rem;
    font-family: "Inter", sans-serif;
  }
  .fourth_text {
    font-size: 1.3rem;
    font-style: italic;
    font-weight: 600;
    font-family: "Inter", sans-serif;
  }
}
@media (max-width: 600px) {
  .container {
    display: flex;
    flex-direction: column;
    margin: 0;
  }
  .left_side {
    display: flex;
    flex-direction: column;
  }
  .text_bar {
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin: 1rem 0;
  }
  .lateral_text {
    text-transform: uppercase;
    font-family: "Fredoka", sans-serif;
    font-size: 0.8rem;
  }
  .image {
    width: 100%;
    object-fit: cover;
  }
  .right-side {
    display: flex;
    flex-direction: column;
    margin: 2rem 1rem 1rem 1rem;
  }
  p {
    justify-self: center;
    font-size: 3rem;
    text-transform: uppercase;
    font-family: "Fredoka", sans-serif;
    color: rgb(250, 211, 137);
    line-height: 1.2;
    text-shadow: 0px 3px 3.68px rgba(0, 0, 0, 0.08);
    margin: 1rem;
  }

  .contact {
    display: flex;
    justify-content: center;
    flex-direction: column;
    padding: 5rem 1rem 0 0;
    align-items: flex-end;
  }
  .second_text {
    font-size: 1.3rem;
    margin-bottom: 1.5rem;
    font-family: "Inter", sans-serif;
  }
  .third_text {
    font-size: 1.3rem;
    font-family: "Inter", sans-serif;
  }
  .fourth_text {
    font-size: 1.1rem;
    font-style: italic;
    font-weight: 600;
    font-family: "Inter", sans-serif;
  }
}
</style>
