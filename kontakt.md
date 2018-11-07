---
layout: default
title: Kontakt
---

<div id="contact">
  <h1 class="pageTitle">Kontakt</h1>
  <div class="contactContent">
    <p>
      <b>E-Mail:</b> gegen.islamismus[at]protonmail.com<br>
      <a href="{{ site.url }}/assets/publickey.gegen.islamismus@protonmail.com.asc">PGP Public Key</a>
      <br><br>
      <a href="https://www.facebook.com/Leipziger-Initiative-gegen-Islamismus-2191724911109853">Facebook</a>
    </p>

  </div>
  <form action="https://formspree.io/gegen.islamismus@protonmail.com" method="POST">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" class="full-width"><br>
    <label for="email">Email Addresse</label>
    <input type="email" id="email" name="_replyto" class="full-width"><br>
    <label for="message">Nachricht</label>
    <textarea name="message" id="message" cols="30" rows="10" class="full-width"></textarea><br>
    <input type="submit" value="Send" class="button">
  </form>
</div>
