# CSS3 Transitions, Animations, and Advanced JavaScript Functions

## Objectives

Create smooth CSS transitions and animations.
<style>
.button {
  background-color: #4CAF50;
  color: white;
  padding: 16px 32px;
  font-size: 16px;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.3s ease;
}

.button:hover {
  background-color: #45a049;
  transform: scale(1.1);
}
</style>

<button class="button">Hover Me</button>

Use JavaScript functions for dynamic behavior.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dynamic Button Example</title>
  <style>
  

Implement local storage for data persistence.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Local Storage Demo</title>
  <style>
    body {
      font-family: sans-serif;
      text-align: center;
      margin-top: 50px;
    }
    input, button {
      padding: 10px;
      font-size: 16px;
      margin: 10px;
    }
  </style>
</head>
<body>

  <h1>Welcome <span id="usernameDisplay">Guest</span>!</h1>
  <input type="text" id="nameInput" placeholder="Enter your name" />
  <button onclick="saveName()">Save Name</button>
  <button onclick="clearName()">Clear Name</button>

  <script>
    // Function to save name to local storage
    function saveName() {
      const name = document.getElementById("nameInput").value;
      if (name) {
        localStorage.setItem("username", name);
        updateGreeting();

## Instructions
Add CSS animations to elements like buttons or images.

>[!NOTE]
> - Write a JavaScript function that:
> - Stores and retrieves user preferences using localStorage.
> - Implements an animation triggered by user actions.

## Tasks

Create a CSS animation.
Store data in localStorage.
Apply JavaScript to trigger animations.

Happy Coding! 💻✨
