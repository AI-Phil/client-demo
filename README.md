# Client Demo

This is an example of some basic client access to Astra Data API.

## License

Copyright (c) 2024 DataStax, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

**THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Setup

1. Create a copy of `.env.example` into a file named `.env` and edit values appropriately.
2. Create a Python virtual environment and install `requirements.txt` into it; this was built with Python 3.11.8.

## Python `astrapy` SDK

Look at `astrapy.ipynb` for an example of using Python to load and read collections using Vectorize.

## Data API (REST)

Using the [Thunder Client Extension](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client):

1. Create an environment using the `.env` file
2. Import the `thunder-collection_client-demo.json` collection

And then run the examples.