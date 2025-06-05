# School Subjects JSON API

This repository hosts a simple JSON-based API for a list of school subjects. It can be consumed by any client (such as a C# console application) that supports HTTP requests and JSON parsing.

## 📦 JSON Data

The [`JSON file`](./json-source.json) contains an array of subject objects, each with the following structure:

```json
[
  {
    "Id": "fd8a1c94-6e2e-4e5a-b2d3-8761f0aef1a1",
    "Name": "Physics",
    "Description": "Introduction to mechanics, waves, and energy.",
    "NumberOfWeeklyClasses": 4,
    "LiteratureUsed": [
      "Fundamentals of Physics",
      "Conceptual Physics"
    ]
  }
]
  
