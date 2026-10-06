# Clickcheck

A tiny reaction-time test web app built for the Shrink YSWS.

## how to use it

Click **Start**, wait for the red circle to turn green, then click **Click Me!** as quickly as possible. Your reaction time is shown in milliseconds.

## how it works

The app waits for a random amount of time after you press Start. When the circle turns green, `performance.now()` records the start time. Your reaction time is calculated when you click the button.

The entire app is contained in a single HTML file with one `<style>` tag and one `<script>` tag.

## building

```bash
npm install
node build.mjs
