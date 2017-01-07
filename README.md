The Project Format
==================

The list.json is just a list of projects. We have it hosted publically on HHCdTq because we trust that people will take it seriously and not modify it randomly.

[Tèquie](https://www.facebook.com/tequiebot/) uses this file for all its information, and also makes its own modifications to the file, so please ensure that it is formatted properly using a JSON verifier before commiting it, and after commiting to it send a message saying "is everything alright?" to [Tèquie](https://www.facebook.com/tequiebot/) and it will let you know if there's something wrong with the JSON file.

The file should be of the following format:

```json
[
  {
    "name": "Tèquie",
    "project-description": "A bot for managing projects in Projects Du Tèque",
    "recruiting": true,
    "looking-for": ["node.js"],
    "facebook-user": "some-fb-username-here"
  },
  {
    "name": "Other Sample Project",
    "project-description": "Another random project",
    "recruiting": true,
    "looking-for": ["python", "designer"],
    "facebook-user": "some-other-fb-username-here"
  }
]
```

