# Captcha Validator

## Overview

The Captcha Validator is a JavaScript-based solution for implementing a simple CAPTCHA system on a web page. It uses HTML5 canvas to generate random CAPTCHA strings, validates user input, and provides feedback.

## Features

- Random generation of alphanumeric CAPTCHA strings.
- User input validation against the generated CAPTCHA.
- Refresh functionality for generating a new CAPTCHA.
- Support for both "Enter" key and "Submit" button validation.

## Setup

1. Include the JavaScript file in your HTML:

    ```html
    <script src="captcha-validator.js"></script>
    ```

2. Add a canvas element to your HTML with the id "captcha":

    ```html
    <canvas id="captcha"></canvas>
    ```

3. Include text input, submit button, and output elements in your HTML:

    ```html
    <input type="text" id="textBox" placeholder="Enter CAPTCHA">
    <button id="submitButton">Submit</button>
    <div id="output"></div>
    ```

## Usage

1. Initialize the Captcha Validator in your JavaScript:

    ```javascript
    let captchaValidator = new CaptchaValidator();
    ```

2. Use the `refreshCaptcha` method to generate a new CAPTCHA:

    ```javascript
    captchaValidator.refreshCaptcha();
    ```
