# VehicleInsuranceQuotes

This application was developed as part of the [Connex Telecommunica.ons Angular / Java Project](TakeHome_Assignment_FullStack.pdf) challenge.

It is a Spring Boot Reactive Webflux application that also serves static resources.
The deployment target is the traditional approach, such as [Heroku](https://www.heroku.com/).

The application leverages the [MongoDB Atlas](https://www.mongodb.com/atlas/database?tck=docs_server) cloud NoSQL database for data storage.

The computation of a premium involves a set of configurations initialized by Spring Boot in a NavigableMap.
This design allows us to modify rules without redeploying the application, thanks to the integration with a config server.


# License

## MIT License

Copyright (c) 2020 Christian Kevin TRAORÉ

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.