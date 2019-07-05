# Coffeephile Schema

==============

## Background

The idea for this API project came from a pure desire to better appreciate craft coffees and their stories. As such, there are two focal points in the schema currently:

- Origins (bean type/geography/prominent roasteries)
- Brews (techniques and equipment)

Each origin can have many brews associated with it, and brews may be associated or differentiated based on the equipment or bean origin.

## Types

- [Origin](https://github.com/DanielCender/Coffeephile/blob/25bee2de1c83f260a3217fd3cb83948ebf5a37df/amplify/backend/api/coffeephile/schema.graphql#L21) - A country or region of origin for a bean varietal.
- [Varietal](https://github.com/DanielCender/Coffeephile/blob/25bee2de1c83f260a3217fd3cb83948ebf5a37df/amplify/backend/api/coffeephile/schema.graphql#L2) - A bean type (ex. Arabica)
- [CharacterTag](https://github.com/DanielCender/Coffeephile/blob/25bee2de1c83f260a3217fd3cb83948ebf5a37df/amplify/backend/api/coffeephile/schema.graphql#L14) - A trait, flavor, or texture associated with a brew or bean.
