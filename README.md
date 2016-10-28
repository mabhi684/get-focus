# get-focus

--------------------------About index.html------------------------------------

xmlhttp.open("GET", url, true);

Setting it to true means you are making an asynchronous request. That means the code does not pause until the http request is complete. A synchronous call locks up the browser so nothing else runs. That can cause problems, so people prefer asynchronous.

if (this.readyState == 4 && this.status == 200)

The XHR object updates us on what it is doing. It gives us the updates with the onreadystatechange event. We register a function with it so we can keep track of its status. The onreadystatechange gets called 4 times. Each with a different state

0 = uninitialized
1 = loading
2 = loaded
3 = interactive
4 = complete

The data is available to us when the readystate is 4.

Now in the code
 this.status == 200, 
 it is checking for the complete state and it makes sure that the status is 200 [ok]




-------------------------------------END-------------------------------