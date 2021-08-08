<h1>Evolution of HTTP:</h1>
              > It is the underlying protocoal of the world wide web(WWW).<br>
              > developed by Tim Berners-Lee and his team between 1989-1991.<br>
              >initially it is called mesh the rename as WWW<br>
<h2>HTTP/0.9 – The one-line protocol:</h2>
              >The initial version of HTTP had no version number; it has been later called 0.9 to differentiate it from the later versions. <br<
              > HTTP/0.9 is extremely simple: requests consist of a single line and start with the only possible method GET followed by the path to the resource (not the URL as both the protocol, server, and port are unnecessary once connected to the server).<br>
              >Unlike subsequent evolutions, there were no HTTP headers, meaning that only HTML files could be transmitted, but no other type of documents.<br>
<h2>HTTP/1.0 – Building extensibility:</h2>
               >HTTP/0.9 was very limited and both browsers and servers quickly extended it to be more versatile.<br>
               >Versioning information is now sent within each request.<br>
               >A status code line is also sent at the beginning of the response, allowing the browser itself to understand the success or failure of the request and to adapt its behavior in consequence (like in updating or using its local cache in a specific way)<br>
               >The notion of HTTP headers has been introduced, both for the requests and the responses, allowing metadata to be transmitted and making the protocol extremely flexible and extensible.<br>
               >With the help of the new HTTP headers, the ability to transmit other documents than plain HTML files has been added.<br>
<h2>HTTP/1.1 – The standardized protocol:</h2>
               >In parallel to the somewhat chaotic use of the diverse implementations of HTTP/1.0, and since 1995, well before the publication of HTTP/1.0 document the next year, proper standardization was in progress. The first standardized version of HTTP, HTTP/1.1 was published in early 1997, only a few months after HTTP/1.0<br>
               >A connection can be reused, saving the time to reopen it numerous times to display the resources embedded into the single original document retrieved.<br>
               >Pipelining has been added, allowing to send a second request before the answer for the first one is fully transmitted, lowering the latency of the communication.<br>
               >Chunked responses are now also supported.<br>
               >Additional cache control mechanisms have been introduced.<br>
               >Content negotiation, including language, encoding, or type, has been introduced, and allows a client and a server to agree on the most adequate content to exchange.<br>
               >Thanks to the Host header, the ability to host different domains at the same IP address now allows server colocation.<br>
