[![Build status](https://img.shields.io/circleci/project/Financial-Times/logo-images.svg)](https://circleci.com/gh/Financial-Times/logo-images)

# Logo images

Image set for all Financial Times product logos

## Usage

As with all image sets, these are available via the [Image Service](https://www.ft.com/__origami/service/image/v2).

To get an social logo from the Image Service, use the following URL (replace the `product_source` with your product name and `logo_name` with the logo you want. The list of available logos is in the src folder of this project and in the Registry)

`https://www.ft.com/__origami/service/image/v2/images/raw/ftsocial:{logo_name}?source={product_source}`

So to get the FT masthead:
`https://www.ft.com/__origami/service/image/v2/images/raw/ftlogo:brand-ft-masthead?source=test`


### Getting these icons in a different colour/format/size

The Image Service will convert these images on the fly if you pass in the right parameters. To find out more about this, please see the [Image Service documentation](https://www.ft.com/__origami/service/image/v2/docs/api)

## Adding or modifying icons

To keep logo images consistent, please follow these guidelines:

- Logos must be SVG format
- Logos must be passed through an SVG compressor like SVGOMG
- Logos must be named with lowercase, hyphen separated:
	- **good** brand-financial-times.svg
	- **bad** BrandFinancialTimes.svg brand_financial_times.svg

---
## Questions or comments?

Please [raise an issue](https://github.com/financial-times/social-images/issues), or Internal FT users can contact us via [#ft-origami in Slack](https://financialtimes.slack.com/messages/ft-origami/).

## Licence

This software is published by the Financial Times under the [MIT licence](http://opensource.org/licenses/MIT).
