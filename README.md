# MOCK GRAPHQL-NEXUS APP

[1] `yarn` to install dependencies
[2] Run the server using `yarn dev`
[3] At `localhost:4000`, you will have the apollo server running.

Finally, run the following query:
```(graphql)
  query {
  personalCategories {
    iconName
    label
  }
  businessCategories {
    iconName
    label
  }
  personalCategoriesDesktop {
    iconName
    label
  }
  businessCategoriesDesktop {
		iconName
    label
  }
}```