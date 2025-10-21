# FileSearchResult


## Fields

| Field                                                       | Type                                                        | Required                                                    | Description                                                 |
| ----------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------- |
| `file_id`                                                   | *str*                                                       | :heavy_check_mark:                                          | The unique ID of the document.                              |
| `filename`                                                  | *str*                                                       | :heavy_check_mark:                                          | The name of the document.                                   |
| `score`                                                     | *float*                                                     | :heavy_check_mark:                                          | The relevance score of the chunk - a value between 0 and 1. |
| `text`                                                      | *str*                                                       | :heavy_check_mark:                                          | The text content of the chunk.                              |
| `attributes`                                                | Dict[str, *Any*]                                            | :heavy_check_mark:                                          | The attributes of the chunk.                                |