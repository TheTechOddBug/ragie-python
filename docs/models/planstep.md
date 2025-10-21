# PlanStep


## Fields

| Field                                                                   | Type                                                                    | Required                                                                | Description                                                             |
| ----------------------------------------------------------------------- | ----------------------------------------------------------------------- | ----------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| `type`                                                                  | *Optional[Literal["plan"]]*                                             | :heavy_minus_sign:                                                      | N/A                                                                     |
| `think`                                                                 | *str*                                                                   | :heavy_check_mark:                                                      | N/A                                                                     |
| `current_question`                                                      | *str*                                                                   | :heavy_check_mark:                                                      | N/A                                                                     |
| `errored`                                                               | *Optional[bool]*                                                        | :heavy_minus_sign:                                                      | N/A                                                                     |
| `questions_to_answer`                                                   | List[*str*]                                                             | :heavy_minus_sign:                                                      | The questions that need to be answered to answer the original question. |