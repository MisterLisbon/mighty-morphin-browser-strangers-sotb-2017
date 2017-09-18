# "Mighty Morphin' Browser Strangers"
### a.k.a. How Samsung Internet and Other Little-Known Browsers are Contributing to the Web

My slides for [State of the Browser](https://www.stateofthebrowser.com/) 2017. 

## To view the slides

(In progress!) They're at: https://poshaughnessy.github.io/mighty-morphin-browser-strangers-sotb-2017/

Use arrow keys or the arrow buttons to move left/right.


## To run locally

```
npm install
npm start
```


## To use the Bluetooth remote control

Load up the Remote page on a Web Bluetooth supporting browser, e.g. Chrome for Android, on the device you want to use 
as a presentation remote: http://localhost:9000/remote.html

Press Connect and (as long as you have the Node server running and Bluetooth enabled on both devices) you should see
a device option called 'Remote Receiver'. Select that, wait til it says Connected, then you can use the buttons to send 
commands!


## To deploy (for Peter's reference)

```
npm run deploy
```

## Additional credits

* Lightning background by [oompa123](https://commons.wikimedia.org/wiki/File:Pink_Lightning.jpg)
