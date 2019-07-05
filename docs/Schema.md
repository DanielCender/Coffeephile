# Coffeephile Schema

## Background

The idea for this API project came from a pure desire to better appreciate craft coffees and their stories. As such, there are two focal points in the schema currently:

- Origins (bean type/geography/prominent roasteries)
- Brews (techniques and equipment)

Each origin can have many brews associated with it, and brews may be associated or differentiated based on the equipment or bean origin.

## Types

### Origin

```graphql
type Origin @model {
	id: ID!
	name: String!
	# countries: [Country] #	maybe an extended type???
	# tips: [Tip]
}
```
