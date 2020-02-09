<template>
  <div>
    <h1 class="title">Bitter</h1>
    <h2 class="subtitle">Ebb</h2>
    <a href="https://www.youtube.com/channel/UCO1CMxB7ZFORHOmqLZxeShw?sub_confirmation=1">YouTube</a>
    <a href="https://twitter.com/BitterEbb">Twitter</a>
    <a href="https://www.twitch.tv/bittarlol">Twitch</a>
    <a href="https://www.reddit.com/user/BitterBrb">Reddit</a>
  </div>
</template>

<script>
export default {
  head() {
    return {
      script: [
        { src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }
      ]
    }
  }
}
</script>

<style>
body {
  background: url('~assets/B logo.PNG') repeat;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: -apple-system, BlinkMacSystemFont, 'Voice In My Head', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: bold;
  font-size: 5.9rem;
  color: #ccc;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-family: -apple-system, BlinkMacSystemFont, 'Voice In My Head', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  font-size: 3rem;
  color: #ccc;
  word-spacing: 5px;
  padding-bottom: 15px;
}
a {
  font-weight: bold;
  color: #ccc;
}
</style>