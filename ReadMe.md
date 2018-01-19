# MWE for ROS3D problem with importing through npm
This is a Minimal Working Example for [issue 197](https://github.com/RobotWebTools/ros3djs/issues/197).

There are two: a simple as possible NodeJS based one and a create-react-app based one.

## NodeJS based (node-mwe)
I simply did `npm init`, then `npm install --save ros3d`, then wrote index.js. Use `node index.js` to run the example. This is the most basic example of the problem that I can come up with.

## ReactJS based (react-mwe)
For this I used the [create-react-app](https://github.com/facebookincubator/create-react-app) application to set up a basic ReactJS project. First, I did `create-react-app react-mwe`, then `npm install --save ros3d` and then edited App.js so it prints the imported ROS3D object on render. Use `npm start` to see the problem in action.