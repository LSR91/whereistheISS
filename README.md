# whereistheISS
This app shows where the ISS is at this moment. Its coordinates are updated every 10 seconds and it is possible to see it on a map.

This APP is made using React and Redux.

You can change the time interval and get updated coordinates faster o slower:

src/containers/App.js>setInterval(()=>{this.props.onGetPosition();},10000);
