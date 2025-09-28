# CodeInterpreterEvidence


## Fields

| Field                                         | Type                                          | Required                                      | Description                                   |
| --------------------------------------------- | --------------------------------------------- | --------------------------------------------- | --------------------------------------------- |
| `type`                                        | *Optional[Literal["code_interpreter"]]*       | :heavy_minus_sign:                            | N/A                                           |
| `text`                                        | *str*                                         | :heavy_check_mark:                            | N/A                                           |
| `code`                                        | *str*                                         | :heavy_check_mark:                            | The code that was executed.                   |
| `code_issue`                                  | *str*                                         | :heavy_check_mark:                            | The issue that the code was written to solve. |
| `code_result`                                 | *str*                                         | :heavy_check_mark:                            | The result of the code that was executed.     |