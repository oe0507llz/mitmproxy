# mitmproxy

Steps to make it working on local Mac:

* ```brew install mitmproxy```

* ```mitmproxy -p 9999``` <br>
In case that the port 9999 is not available, use a different one

* System Preferences -> Network -> Advanced -> Proxies -> Configure HTTP and HTTPS proxies to be localhost with port 9999

* Open a website and you will see the traffic through the mitmproxy

* What we see is essentially the same as Chrome DevTool
