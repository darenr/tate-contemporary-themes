# [Tate](http://www.tate.org.uk/visit/tate-modern) Contemporary themes
Using the Tate Museum's data generate a thematic model of artists.

The Tate has a set of [json files](https://github.com/tategallery/collection/tree/master/artworks) that 
are filtered to only works created after 1945, then for each artist a thematic map is created from the 
subjects covered by that artist. 

Example subject data
```javascript
  "subjects": {
    "children": [
      {
        "children": [
          {
            "children": [
              {
                "id": 225, 
                "name": "colour"
              }, 
              {
                "id": 796, 
                "name": "irregular forms"
              }
            ], 
            "id": 185, 
            "name": "non-representational"
          }, 
          {
            "children": [
              {
                "id": 223, 
                "name": "landscape"
              }, 
              {
                "id": 222, 
                "name": "man-made"
              }
            ], 
            "id": 189, 
            "name": "from recognisable sources"
          }
        ], 
        "id": 184, 
        "name": "abstraction"
      }, 
      {
        "children": [
          {
            "children": [
              {
                "id": 6720, 
                "name": "saucepan"
              }
            ], 
            "id": 84, 
            "name": "kitchen"
          }, 
          {
            "children": [
              {
                "id": 826, 
                "name": "table"
              }
            ], 
            "id": 82, 
            "name": "furnishings"
          }
        ], 
        "id": 78, 
        "name": "objects"
      }, 
      {
        "children": [
          {
            "children": [
              {
                "id": 211, 
                "name": "wall"
              }
            ], 
            "id": 28, 
            "name": "townscapes, man-made features"
          }
        ], 
        "id": 13, 
        "name": "architecture"
      }
    ]
```

The result is a per artist data scruture that can be used to build a thematic ontology.
