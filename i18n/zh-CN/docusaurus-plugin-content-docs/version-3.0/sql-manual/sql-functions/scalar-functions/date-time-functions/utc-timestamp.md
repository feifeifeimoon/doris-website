---
{
    "title": "UTC_TIMESTAMP",
    "language": "zh-CN"
}
---

<!-- 
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

## utc_timestamp
## 描述
## 语法

`DATETIME UTC_TIMESTAMP()`


返回当前 UTC 日期和时间在 "YYYY-MM-DD HH:MM:SS" 或

"YYYYMMDDHHMMSS"格式的一个值

根据该函数是否用在字符串或数字语境中

## 举例

```
mysql> select utc_timestamp(),utc_timestamp() + 1;
+---------------------+---------------------+
| utc_timestamp()     | utc_timestamp() + 1 |
+---------------------+---------------------+
| 2019-07-10 12:31:18 |      20190710123119 |
+---------------------+---------------------+
```

### keywords

    UTC_TIMESTAMP,UTC,TIMESTAMP
