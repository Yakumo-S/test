## 星纵EM300系列通用型号报文数据说明文档（型号EM300）  {docsify-ignore} 

### 基本参数

?> 以下参数为传感器报文的基础参数，供使用时参考。

<table width="800" border="0" cellpadding="0" cellspacing="0" style='width:640.00pt;border-collapse:collapse;table-layout:fixed;'>
   <col width="80" span="5" style='width:48.00pt;'/>
   <tr height="24" style='height:14.40pt;'>
    <td class="xl65" height="24" width="160" colspan="2" style='height:14.40pt;width:96.00pt;border-right:.5pt solid windowtext;border-bottom:.5pt solid windowtext;' x:str>参数</td>
    <td class="xl65" width="80" style='width:48.00pt;' x:str>类型</td>
    <td class="xl65" width="80" style='width:148.00pt;' x:str>说明</td>
    <td class="xl67" width="80" style='width:48.00pt;' x:str>举例</td>
   </tr>
   <tr height="41" style='height:24.60pt;'>
    <td class="xl68" height="41" colspan="2" style='height:24.60pt;border-right:.5pt solid windowtext;border-bottom:.5pt solid windowtext;' x:str>userID</td>
    <td class="xl68" x:str>String</td>
    <td class="xl69" x:str>所属账号<font class="font2">ID</font></td>
    <td class="xl70" x:str>iotadmin</td>
   </tr>
   <tr height="63.00" style='height:37.80pt;'>
    <td class="xl71" height="63.00" colspan="2" style='height:37.80pt;border-right:.5pt solid windowtext;border-bottom:.5pt solid windowtext;' x:str>devEUI</td>
    <td class="xl71" x:str>String</td>
    <td class="xl72" x:str>终端标识，<font class="font2">16</font><font class="font3">位</font><font class="font2">Hex</font></td>
    <td class="xl73" x:str>004A770124038251</td>
   </tr>
   <tr height="38" style='height:22.80pt;'>
    <td class="xl71" height="38" colspan="2" style='height:22.80pt;border-right:.5pt solid windowtext;border-bottom:.5pt solid windowtext;' x:str>devType</td>
    <td class="xl71" x:str>String</td>
    <td class="xl74" x:str>终端型号</td>
    <td class="xl73" x:str>DDS155_BR</td>
   </tr>
   <tr height="76" style='height:45.60pt;'>
    <td class="xl71" height="76" colspan="2" style='height:45.60pt;border-right:.5pt solid windowtext;border-bottom:.5pt solid windowtext;' x:str>OIDIndex</td>
    <td class="xl71" x:str>String</td>
    <td class="xl74" x:str>终端在绿洲平台的唯一标识</td>
    <td class="xl73" x:str>c53151db1e9814892e5dfa5928124969</td>
   </tr>
   <tr height="44" style='height:26.40pt;'>
    <td class="xl71" height="44" colspan="2" style='height:26.40pt;border-right:.5pt solid windowtext;border-bottom:.5pt solid windowtext;' x:str>time</td>
    <td class="xl71" x:str>Long</td>
    <td class="xl74" x:str>报文时间戳</td>
    <td class="xl73" x:num="1612763880036.">1.613E+12</td>
   </tr>
   <tr height="24" style='height:14.40pt;'>
    <td class="xl71" height="24" colspan="2" style='height:14.40pt;border-right:.5pt solid windowtext;border-bottom:.5pt solid windowtext;' x:str>RSSI</td>
    <td class="xl71" x:str>Int</td>
    <td class="xl74" x:str>信号强度</td>
    <td class="xl73" x:num>-77</td>
   </tr>
   <tr height="24" style='height:14.40pt;'>
    <td class="xl71" height="24" colspan="2" style='height:14.40pt;border-right:.5pt solid windowtext;border-bottom:.5pt solid windowtext;' x:str>SNR</td>
    <td class="xl71" x:str>Int</td>
    <td class="xl74" x:str>信噪比</td>
    <td class="xl73" x:num>9</td>
   </tr>
   <tr height="44" style='height:26.40pt;'>
    <td class="xl71" height="44" colspan="2" style='height:26.40pt;border-right:.5pt solid windowtext;border-bottom:.5pt solid windowtext;' x:str>tmnAddr</td>
    <td class="xl71" x:str>Object</td>
    <td class="xl74" x:str>终端位置信息</td>
    <td class="xl73"></td>
   </tr>
   <tr height="24" style='height:14.40pt;'>
    <td class="xl71" height="24" style='height:14.40pt;'></td>
    <td class="xl71" x:str>long</td>
    <td class="xl71" x:str>String</td>
    <td class="xl74" x:str>经度</td>
    <td class="xl73" x:num>120.29852</td>
   </tr>
   <tr height="24" style='height:14.40pt;'>
    <td class="xl71" height="24" style='height:14.40pt;'></td>
    <td class="xl71" x:str>lati</td>
    <td class="xl71" x:str>String</td>
    <td class="xl74" x:str>纬度</td>
    <td class="xl73" x:num>30.454033</td>
   </tr>
   <tr height="24" style='height:14.40pt;'>
    <td class="xl71" height="24" style='height:14.40pt;'></td>
    <td class="xl71" x:str>coordType</td>
    <td class="xl71" x:str>String</td>
    <td class="xl74" x:str>坐标系</td>
    <td class="xl73" x:str>bd-09</td>
   </tr>
   <tr height="110" style='height:66.00pt;'>
    <td class="xl71" height="110" style='height:66.00pt;'></td>
    <td class="xl71" x:str>description</td>
    <td class="xl71" x:str>String</td>
    <td class="xl72" x:str>位置描述（<font class="font2">100</font><font class="font3">字符内）</font></td>
    <td class="xl75" x:str>杭州市余杭区新洲路<font class="font2">830</font><font class="font3">号华数园区二楼</font></td>
   </tr>
   <![if supportMisalignedColumns]>
    <tr width="0" style='display:none;'/>
   <![endif]>
</table>

### 数据参数

?> 以下参数为EM300系列传感器报文中的data数据参数。
   其中电池电量、温度、湿度三种参数为每台EM300传感器中都带有的监测量；水浸状态为EM300-SLD/ZLD特有的监测量；门磁状态为EM300-MCS特有的监测量。
   
| **参数identifier** | **说明**              | **值****value**             | **举例**                                                     |
| ------------------ | --------------------- | --------------------------- | ------------------------------------------------------------ |
| battery            | 电池电量6小时上报一次 | 百分比值如：100%            | {  "identifier" : "battery",  "unit" : "百分比/%",  "paraSchma" : {   "scaling" : 0,   "min" : 0,   "max" : 100,   "dataType" : "int8u"  },  "propertyName" : "电池电量",  "value" : "100" } |
| humidity           | 空气环境相对湿度      | 相对湿度百分比值如：52.5%RH | {  "identifier" : "humidity",  "unit" : "相对湿度/%RH",  "paraSchma" : {   "scaling" : -1,   "min" : 0,   "max" : 1000,   "dataType" : "int16u"  },  "propertyName" : "湿度",  "value" : "52.5" } |
| temperature        | 空气环境温度          | 如：28.3℃                   | {  "identifier" : "temperature",  "unit" : "摄氏度/°C",  "paraSchma" : {   "scaling" : -1,   "min" : -300,   "max" : 700,   "dataType" : "int16s"  },  "propertyName" : "温度",  "value" : "28.3" } |
| waterLeakState     | 水浸状态              | 正常；水浸                  | {  "identifier" : "waterLeakState",  "paraSchma" : {   "dataType" : "enum",   "dataSpecsList" : [ {    "data" : "enum",    "name" : "正常",    "value" : 0   }, {    "data" : "enum",    "name" : "水浸",    "value" : 1   } ]  },  "propertyName" : "水浸状态",  "value" : "正常" } |
| doorState          | 门磁状态              | 打开；关闭                  | {  "identifier" : "doorState",  "paraSchma" : {   "dataType" : "enum",   "dataSpecsList" : [ {    "data" : "enum",    "name" : "关闭",    "value" : 0   }, {    "data" : "enum",    "name" : "打开",    "value" : 1   } ]  },  "propertyName" : "门磁状态",  "value" : "关闭" } |

### 报文示例

* 水浸传感器EM300-SLD/ZLD

```json
{
  "devSN" : "24E124136B238575",
  "devType" : "星纵智能-EM300通用型号",
  "data" : [ {
    "identifier" : "waterLeakState",
    "paraSchma" : {
      "dataType" : "enum",
      "dataSpecsList" : [ {
        "data" : "enum",
        "name" : "正常",
        "value" : 0
      }, {
        "data" : "enum",
        "name" : "水浸",
        "value" : 1
      } ]
    },
    "propertyName" : "水浸状态",
    "value" : "正常"
  }, {
    "identifier" : "humidity",
    "unit" : "相对湿度/%RH",
    "paraSchma" : {
      "scaling" : -1,
      "min" : 0,
      "max" : 1000,
      "dataType" : "int16u"
    },
    "propertyName" : "湿度",
    "value" : "49.0"
  }, {
    "identifier" : "temperature",
    "unit" : "摄氏度/°C",
    "paraSchma" : {
      "scaling" : -1,
      "min" : -300,
      "max" : 700,
      "dataType" : "int16s"
    },
    "propertyName" : "温度",
    "value" : "24.5"
  } ],
  "tmnName" : "星纵EM300水浸传感器测试",
  "description" : "",
  "fCnt" : 139,
  "userID" : "iotadmin",
  "devEUI" : "24E124136B238575",
  "long" : "120.298408",
  "appData" : "0367f500046862050000",
  "coordType" : "bd-09",
  "SNR" : 11,
  "Battery" : 99.511,
  "lati" : "30.453679",
  "period" : 3600,
  "tmnAddr" : {
    "coordType" : "bd-09",
    "description" : "",
    "gPSState" : "",
    "lati" : "30.453679",
    "location" : "浙江省杭州市临平区新洲路830",
    "longitude" : "120.298408"
  },
  "firmTopic" : "82005003",
  "OIDIndex" : "fb38b77155269a383a864bf527f12a73",
  "RSSI" : -87,
  "GPSState" : "",
  "location" : "浙江省杭州市临平区新洲路830",
  "linkType" : "LoRa",
  "time" : 1626663090771,
  "scenarioId" : "453"
}
```

* 门磁传感器EM300-MCS

```json
{
  "devSN" : "24E124136B238653",
  "devType" : "星纵智能-EM300通用型号",
  "data" : [ {
    "identifier" : "doorState",
    "paraSchma" : {
      "dataType" : "enum",
      "dataSpecsList" : [ {
        "data" : "enum",
        "name" : "关闭",
        "value" : 0
      }, {
        "data" : "enum",
        "name" : "打开",
        "value" : 1
      } ]
    },
    "propertyName" : "门磁状态",
    "value" : "关闭"
  }, {
    "identifier" : "humidity",
    "unit" : "相对湿度/%RH",
    "paraSchma" : {
      "scaling" : -1,
      "min" : 0,
      "max" : 1000,
      "dataType" : "int16u"
    },
    "propertyName" : "湿度",
    "value" : "49.5"
  }, {
    "identifier" : "temperature",
    "unit" : "摄氏度/°C",
    "paraSchma" : {
      "scaling" : -1,
      "min" : -300,
      "max" : 700,
      "dataType" : "int16s"
    },
    "propertyName" : "温度",
    "value" : "24.0"
  } ],
  "tmnName" : "星纵EM300门磁测试",
  "description" : "",
  "fCnt" : 479,
  "userID" : "iotadmin",
  "devEUI" : "24E124136B238653",
  "long" : "120.298408",
  "appData" : "0367f000046863060000",
  "coordType" : "bd-09",
  "SNR" : 12,
  "Battery" : 99.511,
  "lati" : "30.453679",
  "period" : 3600,
  "tmnAddr" : {
    "coordType" : "bd-09",
    "description" : "",
    "gPSState" : "",
    "lati" : "30.453679",
    "location" : "浙江省杭州市临平区新洲路830",
    "longitude" : "120.298408"
  },
  "firmTopic" : "82005003",
  "OIDIndex" : "0ed5569e96340131d69c1ddcd1b7cb33",
  "RSSI" : -84,
  "GPSState" : "",
  "location" : "浙江省杭州市临平区新洲路830",
  "linkType" : "LoRa",
  "time" : 1626664077840,
  "scenarioId" : "453"
}
```   