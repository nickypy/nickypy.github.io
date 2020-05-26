<template>
  <div>
    <nuxt />
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

body {
  background-color: #282a36;
  color: #d1d6db;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button {
  display: inline-block;
  border-radius: 32px;
  border: 1px solid #887eab;
  color: #887eab;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
  margin-top: 15px;
  margin-right: 15px;
}

@media only screen and (max-width: 768px) {
  .button {
    display: block;
    width: 50%;
    margin-left: auto;
    margin-right: auto;
  }
}

.button:hover {
  color: #d1d6db;
  background-color: #887eab;
}
</style>
