[Costco Product Search Scraper](https://apify.com/easyapi/costco-product-search-scraper?fpr=data)

Powerful scraper for extracting product data from Costco.com search results. Get comprehensive product information for market research, price monitoring, and competitive analysis.

## Features ✨

- 🔍 Scrape products from any Costco.com search URL
- 📦 Extract detailed product information including:

- Product name and description
- Current price and unit price
- Product ratings and review count
- Availability status
- Product images
- Marketing features and statements
- Brand information
- Item specifications
- Category information
- ⚡ Fast and efficient pagination handling
- 🛡️ Built-in proxy support
- 🤖 Anti-blocking measures implemented
- 💾 Structured JSON output

## Usage 💡

Simply provide one or more Costco.com search URLs and set your desired maximum number of items to scrape. The actor will automatically handle pagination and extract all matching products.

## Input Parameters 📝

- `searchUrls`: Array of Costco.com search URLs to scrape
- `maxItems`: Maximum number of items to scrape (optional, default: unlimited)
- `proxyConfiguration`: Proxy settings (optional, recommended for production use)

## Output 📊

The actor outputs detailed product data in JSON format, including:

- Search URL reference
- Complete product details
- Timestamp of when the data was scraped

## Use Cases 🎯

- Price monitoring and tracking
- Competitive analysis
- Market research
- Product availability tracking
- Inventory monitoring
- E-commerce analytics

## Limitations ⚠️

- Respect Costco.com's terms of service and robots.txt
- Use appropriate delays between requests
- Configure proxy for production use

### Input Example

A full explanation of an input example in JSON.

```
{
    "searchUrls": [
        "https://www.costco.com/s?keyword=ball"
    ],
    "maxItems": 30
}
```

### Output sample

The results will be wrapped into a dataset which you can always find in the **Storage** tab. Here's an excerpt from the data you'd get if you apply the input parameters above:

And here is the same data but in JSON. You can choose in which format to download your data: JSON, JSONL, Excel spreadsheet, HTML table, CSV, or XML.

```
[
    {
        "searchUrl": "https://www.costco.com/s?keyword=ball",
        "product": {
            "item_product_marketing_statement": "",
            "item_variableweight": false,
            "item_product_name": "Kirkland Signature Golf Balls 2-dozen, White",
            "item_member_only": false,
            "item_fsa_eligible": false,
            "item_product_marketing_features": [
                "Limit 5 Per Membership;\n3-piece Urethane Cover Golf Ball;\n2-dozen, 24-count;\nConforms with USGA and R&A Rules"
            ],
            "item_buyable": true,
            "item_collateral_primaryimage": "https://bfasset.costco-static.com/U447IH35/as/5gfbrmhwmk3rjzncq7vvk6q6/1654518-847__1?auto=webp&format=jpg&width=350&height=350&fit=bounds&canvas=350,350",
            "item_chdi_eligible": false,
            "content_type": [
                "product"
            ],
            "Golf_Ball_Construction_attr": [
                "3 Piece"
            ],
            "item_short_description": "Kirkland Signature 3-Piece Golf Ball Performance Plus 2-dozen, White",
            "item_product_comparable": true,
            "group_id": "4000116565",
            "item_classification_itemclass": "Standard",
            "item_product_status_disponzeroinv": false,
            "Quantity_attr": [
                "24 Piece(s)"
            ],
            "item_ratings": 4.761300086975098,
            "item_product_image_swatchable": false,
            "item_link_fee_eligible": "false",
            "EDD_CHUBSmallPack_attr": [
                "0",
                "0"
            ],
            "item_status_published": true,
            "item_comparable": true,
            "item_name": "Kirkland Signature 3-Piece Golf Ball Performance Plus 2-dozen, White",
            "item_eligible_for_review": "true",
            "image": "https://bfasset.costco-static.com/U447IH35/as/5gfbrmhwmk3rjzncq7vvk6q6/1654518-847__1?auto=webp&format=jpg&width=350&height=350&fit=bounds&canvas=350,350",
            "item_product_buyable": true,
            "item_searchable": true,
            "item_disponzeroinv": false,
            "item_review_ratings": "4.761300086975098",
            "item_number": "1654518",
            "item_product_primary_image": "https://bfasset.costco-static.com/U447IH35/as/5gfbrmhwmk3rjzncq7vvk6q6/1654518-847__1?auto=webp&format=jpg&width=350&height=350&fit=bounds&canvas=350,350",
            "item_location_pricing_listPrice": 29.99,
            "item_manufacturing_skus": [
                "196633846136"
            ],
            "item_program_eligibility": [
                "Google",
                "3rdPartyDelivery",
                "GoogleGrocery",
                "SiteControlledInventory",
                "InWarehouse",
                "Standard",
                "WarehouseDelivery",
                "ShipIt"
            ],
            "item_as400_category": "IAB",
            "item_product_status_published": true,
            "Brand_attr": [
                "Kirkland Signature"
            ],
            "item_product_review_eligible": true,
            "categoryPath_ss": [
                "/sports-fitness.html",
                "/sports-fitness-golf.html",
                "/golf-balls.html"
            ],
            "item_location_pricing_pricePerUnit_price": 29.99,
            "item_as400_department": "26",
            "name": "Kirkland Signature Golf Balls 2-dozen, White",
            "description": "Kirkland Signature 3-Piece Golf Ball Performance Plus 2-dozen, White",
            "item_rating_value": [
                "1 & Up",
                "2 & Up",
                "3 & Up",
                "4 & Up"
            ],
            "item_product_price_in_cart_only": "0",
            "item_product_marketingcontent_keywords": [
                "GearUpForGolf",
                "memberfavorites"
            ],
            "item_image_swatchable": false,
            "item_product_short_description": "Kirkland Signature Golf Balls 2-dozen, White",
            "item_location_pricing_salePrice": 29.99,
            "id": "1654518!item.en-US",
            "item_backorderflag": 0,
            "item_product_status_backorderflag": 0,
            "item_startDate": "2023-04-26T00:00:00Z",
            "item_review_count": 0,
            "item_product_review_count": 1860,
            "item_product_status_backorderqty": 0,
            "item_rating_average_value": 0,
            "item_backorderqty": 0,
            "isFutureDate": false,
            "deliveryStatus": "in stock",
            "item_location_availability": "in stock",
            "item_location_stockStatus": "in stock",
            "item_location_itemNumber": "1654518",
            "item_location_locationNumber": "952-wm",
            "item_location_fulfillment_restrictions_minQty": "1",
            "item_location_fulfillment_restrictions_maxQty": "5",
            "item_location_currencyCode": "USD",
            "hasSingleSku": true,
            "minSalePrice": 29.99,
            "maxSalePrice": 29.99,
            "isItemInStock": true,
            "images": [
                {
                    "item_collateral_primaryimage": "https://bfasset.costco-static.com/U447IH35/as/5gfbrmhwmk3rjzncq7vvk6q6/1654518-847__1?auto=webp&format=jpg&width=350&height=350&fit=bounds&canvas=350,350"
                }
            ]
        },
        "scrapedAt": "2025-02-07T06:55:31.881Z"
    },
    ...
]
```

## Related Actors

- 🛍️ [Sam's Club Product Scraper](https://apify.com/easyapi/sam-s-club-product-scraper) - Extract detailed product data from Sam's Club search results, perfect for price monitoring and competitive analysis.
- 🛒 [Woolworths Product Scraper](https://apify.com/easyapi/woolworths-product-scraper) - Extract detailed product data from Woolworths Australia's online store with comprehensive pricing and product information.
- 🛍️ [Lidl Product Scraper](https://apify.com/easyapi/lidl-product-scraper) - Scrape product data from Lidl's online store including prices, images, descriptions and stock information.
- 🛍️ [Hobby Lobby Products Scraper](https://apify.com/easyapi/hobby-lobby-products-scraper) - Scrape product data from Hobby Lobby's website with detailed product information and inventory tracking.
- 🛍️ [Flipkart Product Scraper](https://apify.com/easyapi/flipkart-product-scraper) - Scrape product data from Flipkart search results for price monitoring and market research.
- 🛍️ [AJIO Product Scraper](https://apify.com/easyapi/ajio-product-scraper) - Extract detailed product information from AJIO's fashion marketplace with comprehensive pricing data.
- 🛍️ [Myntra Product Scraper](https://apify.com/easyapi/myntra-product-scraper) - Extract detailed product information from Myntra's fashion marketplace with pricing and inventory data.
- 🛍️ [Meesho Product Search Scraper](https://apify.com/easyapi/meesho-product-search-scraper) - Scrape product listings from Meesho search results with detailed pricing and product information.
- 🛍️ [Zara Product Scraper](https://apify.com/easyapi/zara-product-scraper) - Extract detailed product information from Zara's online store with comprehensive pricing and variant data.
- 🛍️ [Weekday Product Scraper](https://apify.com/easyapi/weekday-product-scraper) - Extract product data from Weekday's online store with detailed variant and pricing information.
- 🛍️ [Tokopedia Product Scraper](https://apify.com/easyapi/tokopedia-product-scraper) - Scrape product data from Tokopedia search results with detailed pricing and shop information.
- 👟 [Nike Product Scraper](https://apify.com/easyapi/nike-product-scraper) - Extract product data from Nike.com search results including prices, colors and detailed product information.
- 🛍️ [Jumia Product Scraper](https://apify.com/easyapi/jumia-product-scraper) - Scrape product listings from Jumia e-commerce platform with comprehensive product details.
- 🏥 [Netmeds Product Scraper](https://apify.com/easyapi/netmeds-product-scraper) - Extract detailed product information from Netmeds.com with pricing and inventory status.
- 🛍️ [AppSumo Product Scraper](https://apify.com/easyapi/appsumo-product-scraper) - Scrape products, deals and offers from AppSumo marketplace with detailed pricing information.