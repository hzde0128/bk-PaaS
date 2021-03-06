### 功能描述

删除模型实例之间的关联关系。

### 请求参数

{{ common_args_desc }}

#### 接口参数
| 字段                 |  类型      | 必填	   |  描述          |
|----------------------|------------|--------|-----------------------------|
| id           | int64     | Yes    | 模型实例关联关系的唯一身份id             |

### 请求参数示例

``` json
{
    "id": 1
}
```

### 返回结果示例

```json
{
    "result": true,
    "code": 0,
    "message": "",
    "data": "success"
}

```

### 返回结果参数说明

#### data

| 字段       | 类型     | 描述         |
|------------|----------|--------------|
| result | bool | 请求成功与否。true:请求成功；false请求失败 |
| code | int | 错误编码。 0表示success，>0表示失败错误 |
| message | string | 请求失败返回的错误信息 |
| data | object | 请求返回的数据 |

