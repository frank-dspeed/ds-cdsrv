# ds-cdsrv
Highly Scaleable Content Delivery Server System from DIREKTSPEED

# TODO
Admin Panel with rule Sets

Define Rules by req.

req.rules:
if header
if body
if parms
if geolocal
if requests in x time
if costum_condition like clicked on elemente 

track clicks on elements in the returned html or app

req.middelware.memcached
returns a memcached result directly

req.middelware.couchbase
returns a couchbase result directly

req.middelware.loadbalancer
sends the request to a backend

req.backends
- LB, PHP-FPM, CGI, HTTP, TCP, UDP, IMAP, POP3, WS, HTTP2, SSL

req.middelware.splitter
send the request to diffrent servers for diffrent actions

req.middelware.return cdn
