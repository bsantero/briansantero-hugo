---
title: Contact
weight: 10
backText: "Brian's Blahg really is an epic poem broken up into short digestible chunks. Like Battlestar Galactica episodes."
backLink: "/blahg/"
forwardText: "Since you're here, you might as well check out his brand new, shiny, candle apple red Portfolio!"
forwardLink: "/project/"
---

<form class="contact" action="https://getsimpleform.com/messages?form_api_token=8fe3f0bce4d48b58cb7a19c033eefdfc" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='localhost:4000/index.html' />
  <!-- all your input fields here.... -->
  <table>
    <tr>
      <td class="form-label">
        <label for="name">Name</label>
      </td>
      <td class="form-field">
        <input type='text' name='Name' />
      </td>
    </tr>
    <tr>
      <td class="form-label">
        <label for="email">Email</label>
      </td>
      <td class="form-field">
        <input type='text' name='email' />
      </td>
    </tr>
    <tr>
      <td class="form-label">
        <label for="content">Message</label>
      </td>
      <td class="form-field">
        <textarea name="content" rows=3></textarea><br />
      </td>
    </tr>
    <tr class="submit">
      <td class="button-container">
        <input type='submit' value='Send it!' />
      </td>
    </tr>
</table>
</form>
