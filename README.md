# Restock Shopping Cart

The app uses multile React components and hooks to construct a shopping cart with inventory kept in a strapi database for persistence.

## Installation

1. Simply clone the repository
2. Install strapi (`https://docs.strapi.io/dev-docs/quick-start`) and generate a database called `products` with the attributes and types of:

    { 
      name: string,
      country: string,
      cost: number,
      instock: number
    }

3. With npm installed and the http-server package added, run "http-server -c-1"
4. Open your web browser to `http://localhost:8080/`

## Usage

Once the webapge is loaded you should see the list of products. Click on the submit button to add items to your cart. You can also click the restock button to retrieve more inventory from the database.

## Support

Use this program at your own risk. If it does not behave correctly, challenge yourself to find the issues and share your fixes with the rest of the community!

## Roadmap of Future Improvements

In the future I would like to refactor the code a bit.

## License

MIT License

Copyright (c) [2024] [Chris Edwards]

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
