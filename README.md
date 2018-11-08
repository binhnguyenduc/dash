# Dash

#### Dash is a Python framework for building analytical web applications. No JavaScript required.

Build on top of Plotly.js, React, and Flask, Dash ties modern UI elements like dropdowns, sliders, and graphs directly to your analytical python code.

[![CircleCI](https://circleci.com/gh/plotly/dash.svg?style=svg)](https://circleci.com/gh/plotly/dash)

See Original project [here](https://github.com/plotly/dash)

This Fork is to add JWT support for Dash:

- On client side, add an Authentication header with Bearer JWTToken with every POST and GET request to server
- On server side, add methods to allow user to request a JWTToken as well as authenticate the received JWTToken before sending data to client side.
