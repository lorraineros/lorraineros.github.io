---
layout: default
title: form
---


<div class="register">
<fieldset>
<h1>Who are you?</h1>
<form>
    First name:<br>
    <input type="text" name="firstname" required>
    <br>
    Last name:<br>
    <input type="text" name="lastname" required><br>
    E-mail:<br>
    <input type="text" name="mail" required><br>
    Phone number:<br>
    <input type="tel" name="phone number" title="Vinsamlegast skráið aðeins tölustafi" required><br>
    <br>
    Gender:<br>
    <input type="radio" name="gender" value="male" checked> Male<br>
    <input type="radio" name="gender" value="female"> Female<br>
    <input type="radio" name="gender" value="other"> Other<br>
    <br>
    When is your birthday?<br>
    <input type="date" data-date="" data-date-format="DD MMMM YYYY" required><br>
    <br>
    Subject: <br>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea><br>
    <br>
    <input type="submit" value="Submit">
  </form>
