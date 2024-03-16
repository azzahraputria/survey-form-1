<!DOCTYPE html>
<html lang="en"></html>
<link rel="stylesheet" href="styles.css">
<h1 id="title">Your Lovely Diary</h1>
<p id="description">Let's write down your best moment today!</p>

<form id="survey-form">
  <div class="input-element">
  <label id="name-label">Name
    <input placeholder="Name" id="name" type="text" required>
  </div>
  </label>
  <div class="input-element">
  <label id="email-label">Email
    <input placeholder="Email" id="email" type="email" required>
  </div>
  </label>
  <div class="input-element">
  <label id="number-label">Year
  <input placeholder="Year" id="number" type="number" min="1965" max="2070" required>
  </div>
  </label>
  </div>

  <div class="input-element">
  <label id="select-label">How do you feel today?
  <select id="dropdown">
    <option>Happy!</option>
    <option>Bored</option>
    <option>Super tired</option>
  </select>
  </div>
  </label>
  </div>

  <div class="input-element">
    <label>Have you ever written here before?</label>
    <div class="input-element">
    <label><input type="radio" name="game" value="agree">Yes</input></label>
    </div>
    <div class="input-element">
    <label><input type="radio" name="game" value="disagree">No</input></label>
    </div>
  </div>

  <div class="input-element">
    <label>What can be learned today?</label>
    <div class="input-element">
    <label><input type="checkbox" name="feelings" value="temporary">All things are temporary, so I don't need to overthink it.</input></label>
    </div>
    <div class="input-element">
    <label><input type="checkbox" name="feelings" value="better">There are much better things to do than just keep it in the corner of your mind.</input></label>
    </div>
     <div class="input-element">
    <label><input type="checkbox" name="feelings" value="break">It's okay to take a break every now and then.</input></label>
    </div>
  </div>
  <label>Let's describe your day!</label>
  <textarea type="text"/></textarea>
  <button id="submit">
    Submit
  </button>
</form>
