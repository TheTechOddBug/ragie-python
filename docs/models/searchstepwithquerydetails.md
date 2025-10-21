# SearchStepWithQueryDetails


## Fields

| Field                                                  | Type                                                   | Required                                               | Description                                            |
| ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------ |
| `type`                                                 | *Optional[Literal["search"]]*                          | :heavy_minus_sign:                                     | N/A                                                    |
| `think`                                                | *str*                                                  | :heavy_check_mark:                                     | N/A                                                    |
| `current_question`                                     | *str*                                                  | :heavy_check_mark:                                     | N/A                                                    |
| `errored`                                              | *Optional[bool]*                                       | :heavy_minus_sign:                                     | N/A                                                    |
| `search`                                               | [models.Search](../models/search.md)                   | :heavy_check_mark:                                     | N/A                                                    |
| `query_details`                                        | List[[models.QueryDetails](../models/querydetails.md)] | :heavy_minus_sign:                                     | N/A                                                    |
| `search_log`                                           | *Optional[str]*                                        | :heavy_minus_sign:                                     | A log of the search results you found.                 |