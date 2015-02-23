# hawtio-plugin-hystrix
Hawt.io Plugin for Hystrix Dashboard

This is a standalone Hystrix Hawt.io plugin that allows embedding hystrix dashboard into the Hawt.io console.

Plugin intended to be deployed in OSGi container, such as Karaf. 

The plugin is self-containing - Hystrix dashboard is included in the final plugin war.

The plugin works in combination with https://github.com/vgoldin/camel-hystrix-bridge that exposes the Hystrix stream on http://localhost:8181/camel/hystrix/hystrix.stream in Karaf OSGi enviroment
