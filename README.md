qgis-wps-client
===============

OGC-WebProcessingService (WPS) provide a powerful tool for process integration in service-oriented architectures (SOA).
The QGIS Web Processing Client plugin gives you the opportunity to connect QGIS with WPS servers to execute processes.
You can install the plugin directly with the QGIS plugin installer in your system or download it here.

The Kappasys-WPS Services are based on PyWPS. For testing purposes there are available three different processes.
The data upload is limited to 3Mb per session.

http://www.kappasys.ch/pywps/pywps.cgi

    Returner testing process that takes the selected vector data and sends it back to the client.
    Vector overlay process: This process uses two input layers in a GRASS vector overlay process.
    You can calculate the difference, intersection, and the union of the layers.
    Vector Buffer Process: This process calculates a buffer around the input vector objects.
    The process is based on the Python OGR library

Kappasys offers to integrate your processes into this infrastructure. In this way it is possible for any client to use your specific process. The only requirement for the use of the processes, is that the client can communicate via HTTP.

Of course, the processes can be secured with authorization and authentication mechanisms. We can advise you.

 
