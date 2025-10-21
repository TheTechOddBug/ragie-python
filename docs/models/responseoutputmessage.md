# ResponseOutputMessage


## Fields

| Field                                                        | Type                                                         | Required                                                     | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| `type`                                                       | *Optional[Literal["message"]]*                               | :heavy_minus_sign:                                           | N/A                                                          |
| `id`                                                         | *str*                                                        | :heavy_check_mark:                                           | N/A                                                          |
| `role`                                                       | *Optional[Literal["assistant"]]*                             | :heavy_minus_sign:                                           | N/A                                                          |
| `content`                                                    | List[[models.ResponseContent](../models/responsecontent.md)] | :heavy_check_mark:                                           | N/A                                                          |