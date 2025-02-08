**Mobile Development** 
	- the process of creating software for mobile devices
	- includes writing code to create the software and designing
	- biggest difference between software development is the ability to use native features on mobile devices

##### Types of Mobile App Frameworks
- **Native Apps**
	- designed for specific operating systems. Makes use of device features such as RAM, camera, etc
	- *Performance*: High (optimized for platform)
- **Progressive Web Apps (PWAs)**
	- brings the power of the web to mobile, providing an app-like experience without requiring installation. developed with web technology (HTML...)
	- *Performance*: Moderate
- **Hybrid Apps**
	- combination of both types, offers cross-compatibility
	- *Performance*: Lower than native
	
##### Developing mobile apps
**For IOS**
- *Objective C* - first language supported by Apple
- *Swift* - introduced in 2014 as a language specification

**For Android**
- *Java* - default language to write Android apps since the platform was introduced in 2008
- *Kotlin* - released in 2017, is interoperable with Java code, all Java libraries can be called from Kotlin. Tidier form of Java
	
**Mobile App Architecture**
- is the blueprint of building your app
1. *Presentation Layer* 
	- front end/the visible part of the app
	- main purpose is to take data and display it
2. *Business Layer* 
	- contains the application's core logic/how it should behave
	- often takes user input or raw data from the data layer, processes it, then sends it to the presentation layer
	- is the most complex part
3. *Data Layer* 
	- intermediary between other app layers and external resources
	- main purpose is gathering raw data from various sources (databases or API)and sending it to upper layers

**Factors to Consider**
- *Device Type* - determines the hardware capabilities and screen sizes
- *Development framework* - vital for efficient application development and maintenance
- *Bandwidth* - impacts how app communicates with servers and fetches data
- *Network fluctuations* - mobile networks are prone to varying signal strength and stability fluctuations, which can affect app performance 
- *User interface* - plays a crucial role in shaping overall user experience
- *Navigation Method* - defines how users navigate your app and access its features and content
- *Real-time updates vs. push notifications* - deciding between the two depends on the nature of your app and the importance of timely information delivery