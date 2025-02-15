This file describes the values that can be set to populate product information.

# Basic Rules
1. The data related files be added to `data/` directory.
1. The name of the file is the product.
1. Preferred format is YAML. So, name your file `product.yaml`.
1. The product information will be shown in the sidebar

# Fields

## `title`
  - Key with the Value being the Title of the Product.
  - This is Mandatory.

## `subtitle`
  - Key value pair.
  - A subtitle for the product.
  - This field is Optional.

## `poster`
  - Key value pair.
  - Mandatory.
  - This is the absolute path to the image representing the product.
  - This path usually points to an image from the product directory.
    - example: "/products/c-language/c-course.png"

## `description`
  - Key Value pair.
  - Mandatory.
  - Value represents a description for the course.

## features:
  - Optional.
  - List.
  - Each list item is a feature.

## more
  - Key Value pair.
  - The Value points to a URL.
  - The URL is a landing page with more details about the product.

## ctaText
  - Key Value pair.
  - Mandatory
  - The Value represents the text to be shown on the button.

## enroll
  - Mandatory
  - Key Value pair.
  - Value represents the Checkout link



