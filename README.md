# Monosodium

### TODO

* Figure out how to send messages - through the app? or another service? or feeder (and rename this to service?)
* Use MQTT for queueing?

---

## Structure

### App ([`monosodium-app`](https://github.com/featherbear/monosodium-app/))

The web frontend and server

### Service ([`monosodium-service`](https://github.com/featherbear/monosodium-service/))

Backend service to interact with Messenger (send and receive)

### Commons ([`monosodium-commons`](https://github.com/featherbear/monosodium-commons/))

Common code shared between repositories

---

# Architecture

* monosodium-app
* monosodium-service
* MongoDB - storing of messages

---

# License

MIT License

Copyright 2019 - 2021 Andrew Wong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.