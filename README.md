# CadaVR
A virtual reality medical educational environment that leverages structural models of anatomy, natrual input, and mathematical models of physiology to help students learn.

### Live Demo
[![CadaVR Promotional Video](http://img.youtube.com/vi/eYyuEjhD-k8/0.jpg)](http://www.youtube.com/watch?v=eYyuEjhD-k8 "CadaVR")

## Server Setup
    1. Install nodejs - https://nodejs.org/en/download/
    2. Install meteor: https://www.meteor.com/install
    3. Deploy to local server:
        a. Go to the CadaVR git dir
        b. Go to the site dir: Run "cd site"
        c. Deploy to local server: Run "meteor"
    4. Deploy to meteor.com:
        a. Go to the CadaVR git dir
        b. Go to the site dir: Run "cd site"
        c. Deploy to meteor.com: Run "meteor deploy ryancadavr.meteor.com"
        a. Or replace the url with a custom url, e.g.: <yourname>cadavr.meteor.com
        
## Running the Leap Motion
To run the leap service so other machines can access the leap device, run the following command:

Windows:
LeapSvc --websockets_allow_remote=true --websockets_enabled=true --run

Mac & Linux:
leapd --websockets_allow_remote=true --websockets_enabled=true --run
