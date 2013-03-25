A CHIRP Radio open web app

This is a static HTML5 app built for
[Firefox OS](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox_OS).

Developers
----------

You need a
[BootToGecko](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox_OS)
device. This will not work on the
[Firefox OS Simulator](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox_OS/Using_Firefox_OS_Simulator).

The app is static HTML5 but for local development you need to
run it from a server. You can do that with Node.JS.

Install the dependencies::

    npm install

Run the server::

    npm start

Open [http://0.0.0.0:3000/app.html](http://0.0.0.0:3000/app.html)
in a browser to make sure it's running.
Install the [manifest](http://0.0.0.0:3000/manifest.webapp) on a device.