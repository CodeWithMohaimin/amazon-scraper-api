# Amazon Scraper API

This is an API project for scraping data from Amazon.com. The API provides the following functionalities:

- Get Product Details using product ID.
- Get Product Reviews Details using product ID.
- Get Product Offers from Amazon.
- Get Search result and show related products.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To run the API, you will need the following:

- Node js install
- A web Browser

## API Endpoints

### If you wanted to Get the Product Details use this parameter.

- product_id: The unique identifier of the product.

```bash
GET /product/<product_id>


```

### If you wanted to Get the Product Reviews use this parameter.

- product_id: The unique identifier of the product.

```bash
GET /reviews/<product_id>


```

### If you wanted to Get the Product Offers form Amazon.com use this parameter.

- product_id: The unique identifier of the product.

```bash
GET /offers/<product_id>


```

### If you wanted to Get Product search and related products use this parameter.

- There is no unique identifier of the product.

```bash
GET /search/<search_term>


```

---

#<p align="center">Author</p> <p align="center">[Mohaimin Islam]('https://www.youtube.com/ProgrammerMohaimn')</p>
