# Multi-Browser Highlighting


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Version](https://img.shields.io/badge/Version-1.0-blue.svg)



A simple burp plugin that highlights the Proxy history to differentiate requests made by different browsers. The way this works is that each browser would be assigned one color and the highlights happen automatically. 

During pentesting, I often have two or more different browsers opened to test issues such as role matrix, as well as to show how requests in 1 client might affect another. It is however hard to visualize which requests were made by which browser within the proxy histroy. Hence this plug-in was created to help visualize how different requests interleave with one another.

++
- Added comparison of proxy listening interface to differentiate browsers.
- For use with same type of browser on different listening interfaces to test issues such as role matrix.
  - e.g. Firefox A on 127.0.0.1:8080 & Firefox B on 127.0.0.1:8081

It is designed to be **non-intrusive**, so highlighting is disabled by default. Turn it on in the Proxy context menu only when you need it.



## Screenshots

Requests from 3 different browsers show how their traffic interleave:

<img width="942" alt="screen shot 2017-07-13 at 1 59 28 pm" src="https://user-images.githubusercontent.com/11704508/28147891-8c9355a8-67d7-11e7-8fea-12505a71b404.png">


Toggle it on/off within context menu:

<img width="522" alt="screen shot 2017-07-13 at 3 03 19 pm" src="https://user-images.githubusercontent.com/11704508/28148687-7332c7ce-67dc-11e7-9c64-d949c259284b.png" width=25%>



## Author
Emmanuel Law
